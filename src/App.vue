<template>
  <div id="app">
    <hello-world :person="{name: 'ligang'}"></hello-world>
    <input v-model="name">
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      name: ""
    };
  }
};
</script>
