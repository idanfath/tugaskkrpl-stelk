<template>
  <q-layout view="lHh Lpr lFf" class="bg-image c">
    <div class="dimmed"></div>
    <HeadeF></HeadeF>
    <q-card class="absolute-center card01 bg-transparent text-white no-shadow">
      <div class="text-bold text-h4">THE REAL INFORMATICS SCHOOL</div>
      <div class="text-caption" style="padding-top: 5px;">Pelopor SMK bidang Teknologi Informasi dan Komunikasi di Indonesia.</div>
    </q-card>
  </q-layout>
  <q-layout view="lHh Lpr lFf" class="bg-white" style="min-height: 320px;">
    <div style="padding-top: 120px;">    
      <div class="text-bold text-h4 text-dark">Kenapa Harus <span class="text-bold text-h4" style="color: #bd2130;">SMK Telkom Makassar</span>?</div>
      <div class="text-caption text-grey-8" style="padding-top: 5px;">Alasan kenapa harus memilih untuk bergabung dengan <span class="text-caption q-ma-none" style="color: #bd2130;">SMK Telkom Makassar</span>.</div>
    </div>
    <CarouseL style="margin-bottom: 70px;"></CarouseL>
  </q-layout>
  <q-layout view="lHh Lpr lFf" class="layout01" style="display: flex; min-height: 320px;">
    <div style="display: flex; justify-content: space-evenly;">
      <q-card flat class="my-card">
      <q-card-section>
        <div class="text-h5 text-bold">Assalamualaikum Wr. Wb</div>
      </q-card-section>
      <q-card-section class="q-pt-none text-subtitle size0">
        Puji Syukur Alhamdulillah kita panjatkan ke hadirat Allah SWT, atas segala rahmat dan hidayah-Nya sehingga kita masih diberi kesempatan untuk bekerja dan berkarya di bidang pendidikan. Karena pendidikan merupakan upaya kita untuk menyiapkan generasi penerus bangsa, yang akan menggantikan estafet kepemimpinan kita di masa mendatang.
        <br><br>
        Kami mengucapkan selamat datang di website resmi SMK Telkom Makassar yang dapat digunakan sebagai salah satu media komunikasi, dan interaksi antara civitas akademika dan masyarakat pada umumnya.
        <br><br>
        Mari kita bekerja dan berkarya dengan mengharap ridho-Nya dan keikhlasan yang tulus demi menyiapkan generasi bangsa yang berintegritas dan berprestasi.
        <br><br>
        Wassalamualaikum Wr. Wb
      </q-card-section>
      <q-card-section style="padding-top: 0;">
        <div class="text-h8 text-bold">Drs. Abd. Halim Samad, MM</div>
      </q-card-section>
    </q-card>

    <q-card flat class="my-card" style="border-radius: 0px;">
      <div class="imghomecontainer" style="margin: -30px; height: 374px;">
        <img class="imghome" src="https://smktelkom-mks.sch.id/assets/front-end/img/other/fotobapak4_xuztb6.png "/>
      </div>
    </q-card>
    </div>
  </q-layout>
  <q-layout view="lHh Lpr lFf" class="bg-white text-center" style="min-height: 320px;">
    <div style="padding-top: 120px;">    
      <div class="text-bold text-h4 text-dark">Program Keahlian</div>
      <div class="text-caption text-grey-8" style="padding-top: 5px;">Pilihan program keahlian di <span class="text-caption q-ma-none" style="color: #bd2130;">SMK Telkom Makassar</span>.</div>
    </div>
    <KiKards></KiKards>
  </q-layout>
  <q-layout view="lHh Lpr lFf" class="bg-white text-center" style="min-height: 320px;">
    <div style="padding-top: 70px;">    
      <div class="text-bold text-h4 text-dark">Berita Terbaru</div>
      <div class="text-caption text-grey-8" style="padding-top: 5px;">Ikuti terus informasi dan berita-berita terbaru tentang <span class="text-caption q-ma-none" style="color: #bd2130;">SMK Telkom Makassar</span>.</div>
    </div>
    <div style="margin: 30px; margin-bottom: 120px;"><KaKards></KaKards></div>
    
  </q-layout>
  <FooteR></FooteR>
</template>

<script>
// @ is an alias to /src
import CarouseL from '@/components/CarouseL.vue';
import HeadeF from '@/components/HeadeF.vue';
import FooteR from '@/components/FooteR.vue';
import KiKards from '@/components/KiKards.vue';
import KaKards from '@/components/KaKards.vue';

export default {
  components: {
    CarouseL,
    HeadeF,
    FooteR,
    KiKards,
    KaKards
  }
}

</script>

<style>

.bg-image.c {
  background-image: url(https://smktelkom-mks.sch.id/assets/front-end/img/other/DSCF8979_jtyuim.jpg);
  background-size: cover;
}

.imghomecontainer {
  background-color: rgb(255, 255, 255, 0.1); 
}

.imghome {
  max-height: 300px; 
  margin-top: 30px;
}

.size0 {
  font-size: 10px;
}

.my-card {
    margin: 30px;
    text-align: left;
    background-color: transparent !important;
    color: white;
    max-width: 30%;
}

.layout01 {
  background-color: #bd2130;
}

.card01{
  opacity: 1;
}

.text02 {
  position: relative;
}

</style>