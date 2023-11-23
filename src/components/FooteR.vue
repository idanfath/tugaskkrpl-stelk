<template>
    <q-layout view="lHh Lpr lFf" style="display: flex; min-height: 200px; background-color: #e6e6e6; justify-content: space-evenly;" >
        <div id="container" class="container01"><div class="text-bold text-h4" style="color: #bd2130;">Ayo gabung dengan kami.</div></div>
        <div id="container" class="container01"><img src="https://smktelkom-mks.sch.id/assets/front-end/img/other/perisai_ao9ugl.png" style="height: 120px;"></div>
    </q-layout>
    <q-layout view="lHh Lpr lFf" class="footer0" style="display: flex; min-height: 320px; min-height: 320px; display: flex; justify-content: center; align-items: center;">
      <div class="q-py-xl q-px-xl" style="background: #04091e">
        <div
          style="
            display: flex;
            justify-content: space-around;
            color: white;
            flex-wrap: wrap;
          "
        >
          <div class="menu-utama" style="width: 380px">
            <h1 class="text-h6" style="text-align: left">Menu Utama</h1>
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Beranda</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Tentang Kami</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Profil Jurusan</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Perisai</router-link
            >
          </div>
          <div class="hubungi-kami" style="width: 380px">
            <h1 class="text-h6" style="text-align: left">Hubungi Kami</h1>
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >FAQ</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Layanan Orang Tua</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Kontak Pertanyaan</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >Pusat Bantuan</router-link
            >
          </div>
          <div class="useful-links" style="width: 380px">
            <h1 class="text-h6" style="text-align: left">Useful Links</h1>
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >iGracias TS</router-link
            >
            <router-link
              to="#"
              style="
                display: block;
                text-align: left;
                margin-bottom: 10px;
                text-decoration: none;
                color: #777777;
              "
              >YPT</router-link
            >
          </div>
        </div>
        <div class="">
          <h1
            class="text-subtitle1 q-mt-xl"
            style="color: #777777; text-align: left"
          >
            Copyright
            <span class="text-subtitle1 q-ma-none" style="color: #bd2130">SMK Telkom Makassar</span> @2023.
          </h1>
        </div>
      </div>
    </q-layout>
</template>

  <script>
  export default {};
  </script>

<style>

.title {
    font-weight: bold;
    font-size: 40px;
    margin: 0 0 10px 0;
    line-height: normal;
  }
  
.subtitle {
color: grey;
}

router-link:hover {
color: #bd2130;
}

.container01 {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.footer0 {
    background-color: #04091e;
}

.my-card1{
    padding: 50px;
    padding-left: 100px;
    text-align: left;
    background-color: transparent !important;
    color: #bd2130;
    justify-content: space-around;
}
</style>