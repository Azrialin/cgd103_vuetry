<template>
  <div class="img">
    <img :src="link" alt="">
  </div>
    
</template>

<script>
export default {
  name: 'Images',
  props: {
    link: String
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.img{
  width: 100px;
  height: 100px;
  background-color: navy;
  color: white;
}
</style>
