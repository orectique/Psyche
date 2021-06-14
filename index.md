## Welcome to Psyche

This is part of a project that aimed to create a virtual chat buddy. To try it out, hit the chat icon at the bottom right.
<script>
  window.watsonAssistantChatOptions = {
      integrationID: "986c463d-c772-4ae5-92d2-7297de6f5269", // The ID of this integration.
      region: "eu-gb", // The region your integration is hosted in.
      serviceInstanceID: "e7e04de8-2fb6-41f8-8e71-265f811c0878", // The ID of your service instance.
      onLoad: function(instance) { instance.render(); }
    };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
    document.head.appendChild(t);
  });
</script>
