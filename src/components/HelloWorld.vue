<template>
  <div class="hello" :class="type">
    <div class="img" v-for="item in 3" :key="item">
      
      <img :src="require(`@/assets/images/avatar/${item}.jpg`)" alt="">
      
    </div>
    <div>
      <h1>{{ title }}</h1>
      <h1>{{ msg }}</h1>
      <p>2321321321312</p>
      <button>nani</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title: String,
    msg: String,
    type: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello{
  width: 100%;
  display: inline-flex;
}

.img{
  width: 50px;
  height: 50px;
}
</style>
