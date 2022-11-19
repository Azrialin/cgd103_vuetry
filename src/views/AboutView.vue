<template>
  <div class="about">
    <h1>This is an about page</h1>

            <Button>Default</Button>
            <Button type="primary">Primary</Button>
            <Button type="dashed">Dashed</Button>
            <Button type="text">Text</Button>
        <hr>
        <Carousel v-model="value" loop>
            <CarouselItem v-for="item in 5" :key="item">
                <div class="demo-carousel">
                    <img :src="require(`@/assets/images/avatar/${item}.jpg`)" alt=""/>
                </div>
            </CarouselItem>
        
    </Carousel>
  </div>
</template>

<script>
    export default {
        data () {
            return {
                value: 0
            }
        }
    }
</script>
