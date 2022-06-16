<template>

<div class="container">
  <h1 class="mb-4">Bubbelroom</h1>
<carousel class="carousel mb-5 " :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="true">
  <slide>
    <img class="foto" src="../assets/bubbelHanna355.jpg" style="">
  </slide>
  <slide>
    <img class="foto" src="../assets/bubbelHanna14.jpg" alt="">
  </slide>
    <slide class="d-flex justify-content-evenly" >
    <img class="foto" src="../assets/bubbelHanna13.jpg" alt="">
    <img class="foto" src="../assets/bubbelHanna12.jpg" alt="">
  </slide>
</carousel>

  <h1 class="mb-4">Corline Eyewear</h1>
<carousel class="carousel" :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="true">
  <slide>
    <img class="foto" src="../assets/hannacorline5.png" style="">
  </slide>
  <slide class="d-flex justify-content-evenly">
    <img class="foto" src="../assets/hannacorline4.jpg" alt="">
    <img class="foto" src="../assets/hannacorline3.jpg" alt="">
    <img class="foto" src="../assets/hannacorline2.jpg" alt="">
  </slide>
    <slide>
    <img class="foto" src="../assets/hannacorline1.jpg" style="max-width: 60rem">
  </slide>
</carousel>
</div>





</template>

<script>
import Vue from 'vue';
import VueCarousel from 'vue-carousel';
Vue.use(VueCarousel);

import { Carousel, Slide } from 'vue-carousel';
  export default {
  components: {
    Carousel,
    Slide
  }
};

</script>

<style>
.foto{
 max-height: 30rem;
}
</style>