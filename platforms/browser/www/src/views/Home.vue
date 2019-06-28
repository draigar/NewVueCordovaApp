<template>
  <div class="app">
    <h1>Apache Cordova</h1>
    <div id="deviceready" class="blink">
      <p class="event listening">Connecting to Device</p>
      <p class="event received">Device is Ready</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  mounted() {
    app.receivedEvent("deviceready");
  }
};
</script>
