<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld title="nani1" msg="Welcome to Your Vue.js App" type="wide"/>
    <HelloWorld title="nani2" msg="NICE"/>
    <HelloWorld title="nani3" msg="Awesome"/>
    <!-- <Images link="sdasda" msg="dsadsa"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Images from '@/components/Images.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    Images
  }
}
</script>
