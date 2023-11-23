<template>
    <div class="q-pa-md">
    <q-carousel
      v-model="slide"
      infinite
      :autoplay="autoplay"
      :vertical="vertical"
      arrows
      height="300px"
      class="bg-transparent text-black rounded-borders"
    >
      <q-carousel-slide name="1" class="column no-wrap flex-center">
        <img style="width: 100px;" src="https://smktelkom-mks.sch.id/assets/front-end/img/icon/school_jfslqk.png">
        <div class="q-mt-md text-center text-bold" style="font-size: 20px;">Lingkungan Nyaman</div>
        <div class="q-mt-sm text-center" style="font-size: 15px;">Berada di lingkungan yang asri, aman dan kondusif.</div>
      </q-carousel-slide>
      <q-carousel-slide name="2" class="column no-wrap flex-center">
        <img style="width: 100px;" src="https://smktelkom-mks.sch.id/assets/front-end/img/icon/presentation_dai7nn.png">
        <div class="q-mt-md text-center text-bold" style="font-size: 20px;">Pengajar Kompeten</div>
        <div class="q-mt-sm text-center" style="font-size: 15px;">Lorem ipsum, dolor sit amet.</div>
      </q-carousel-slide>
      <q-carousel-slide name="3" class="column no-wrap flex-center">
        <img style="width: 100px;" src="https://smktelkom-mks.sch.id/assets/front-end/img/icon/team_lxvtyk.png">
        <div class="q-mt-md text-center text-bold" style="font-size: 20px;">Kerjasama Luas</div>
        <div class="q-mt-sm text-center" style="font-size: 15px;">Lorem ipsum, dolor sit amet.</div>
      </q-carousel-slide>
      <q-carousel-slide name="4" class="column no-wrap flex-center">
        <img style="width: 100px;" src="https://smktelkom-mks.sch.id/assets/front-end/img/icon/laptop_ksosxp.png">
        <div class="q-mt-md text-center text-bold" style="font-size: 20px;">Fasilitas Lengkap</div>
        <div class="q-mt-sm text-center" style="font-size: 15px;">Lorem ipsum, dolor sit amet.</div>
      </q-carousel-slide>
    </q-carousel>
  </div>
  </template>
  
  <script>
  import { ref } from 'vue'
  
  export default {
    setup () {
      return {
        slide: ref('style'),
        autoplay: ref(true)
      }
    }
  }
  </script>
  