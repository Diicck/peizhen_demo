<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from "@/layout/index.vue";

export default {
  name: 'HomeView',
  components: {
    Home
  }
}
</script>
