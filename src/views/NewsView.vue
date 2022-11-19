<template>
  <div class="about">
    <h1>This is news page</h1>
    <HelloWorld title="nani1" msg="Welcome to Your Vue.js App"/>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'NewsView',
  components: {
    HelloWorld
  }
}
</script>