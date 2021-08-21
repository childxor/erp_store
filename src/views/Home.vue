<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/ip.jpg" width="30%"> <br>
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template> 

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({ 
  components: {
    HelloWorld,
  },
})
export default class Login extends Vue {}
</script>
