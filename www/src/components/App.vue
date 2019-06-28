<template>
  <div id="app">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    
    <router-view>
      <Home/>
    </router-view>
  </div>
</template>
<script>
import Home from "../views/Home";
export default {
  name: "App",
  components: {
    Home
  }
};
</script>