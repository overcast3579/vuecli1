<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Button type="primary">Primary</Button>
  </div>
  <div>
    <Carousel v-model="value" loop>
        <CarouselItem v-for="item in 10" :key="item">
          <img :src="require('@/assets/logo.png')" alt="" />
            <!-- <div class="demo-carousel">1</div> -->
        </CarouselItem>
        <!-- <CarouselItem>
            <div class="demo-carousel">2</div>
        </CarouselItem>
        <CarouselItem>
            <div class="demo-carousel">3</div>
        </CarouselItem>
        <CarouselItem>
            <div class="demo-carousel">4</div>
        </CarouselItem> -->
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
