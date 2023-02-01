<template>
  <div class="home">
    <NavBar />
    <HelloWorld />
    <Fotter />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import NavBar from "@/components/NavBar.vue";
import Fotter from "@/components/FotterView.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    NavBar,
    Fotter,
  },
};
</script>
