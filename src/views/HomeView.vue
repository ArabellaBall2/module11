<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <GoBack />
  </div>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import GoBack from '@/components/GoBack.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    GoBack
  }
}
  
</script>