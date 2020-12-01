<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/anchor.svg" />
    <HelloWorld msg="Foghornan" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
