<template>
    <StyleCSS></StyleCSS>
    <div class="header-fix">
    <q-header class="header">
        <div class="balancer" style="display: flex; justify-content: left;"><img src="https://smktelkom-mks.sch.id/assets/front-end/img/other/logo_pcpqhr.png" style="max-width: 45px;"/></div>
        <nav class="text-weight-medium" style="display: flex; font-size: 13px; gap: 15px;">
    
          <div class="dropdown row reverse text-uppercase">
                <div class="q-mx-xs">
                    HUBUNGI KAMI <span class="text-white material-icons" style="font-size: 15px;">
                        expand_more
                    </span>
                </div> 
            <div class="non-selectable dropdown-content bg-none absolute q-pt-md" style="position: absolute; top: 55px; width: 150px;">
                <div class="bg-white text-left q-pa-md">
                    <a href="/anu" class="text-dark q-pa-sm">Lorem</a>
                    <a href="/anu" class="text-dark q-pa-sm">Ipsum</a>
                    <a href="/anu" class="text-dark q-pa-sm">Dolor</a>
                </div>
            </div>
          </div>
    
          <div class="dropdown row reverse text-uppercase">
                <div class="q-mx-xs">
                    ALUMNI <span class="text-white material-icons" style="font-size: 15px;">
                        expand_more
                    </span>
                </div> 
            <div class="non-selectable dropdown-content bg-none absolute q-pt-md" style="position: absolute; top: 55px; width: 150px;">
                <div class="bg-white text-left q-pa-md">
                    <a href="/anu" class="text-dark q-pa-sm">Lorem</a>
                    <a href="/anu" class="text-dark q-pa-sm">Ipsum</a>
                    <a href="/anu" class="text-dark q-pa-sm">Dolor</a>
                </div>
            </div>
          </div>
    
          <div>
                <a href="/perisai" class="q-mx-xs">PERISAI</a> 
          </div>
        </nav>
        </q-header>
    </div>  
    </template>
    
    <style>
    
    .dropdown-content {
        display: none;
    }
    
    .dropdown-content a {
        text-decoration: none;
        display: block;
    }
    
    .dropdown-content a:hover {
        color: rgb(147, 147, 147) !important;
    }
    
    .dropdown:hover .dropdown-content {
        display: block;
    }
    
    .imgheadef{
        max-height: 200px;
    }
    .balancer{
        width: 200px;
    }
    
    .text01 {
        color: white !important;
    }
    
    .last {
        margin: 0px;
    }
    
    span.last.material-icons {
    margin-right: 0;
    }
    
    span.material-icons {
    font-size: 20px;
    margin-right: 5px;
    color: white;
    }
    
    .header-icon {
    font-size: 30px;
    }
    
    .title {
    font-size: 30px;
    }
    
    #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    text-align: center;
    color: #000000;
    text-decoration: none; 
    }
    
    .header {
    display: flex;
    align-items: center;
    padding: 0px 15%;
    justify-content: space-between; 
    height: 90px;
    background-color: transparent !important;
    }
    
    #title {
    margin: 0; 
    }
    
    nav {
    display: flex;
    }
    
    nav a {
    color: #ffffff;
    margin-right: 30px; 
    text-decoration: none; 
    }
    
    nav a:last-child {
    margin-right: 0; 
    }
    
    .router-link {
        display: flex;
        align-items: center;
        text-decoration: none; 
    }
    
    .material-symbols-outlined {
    margin-right: 5px; 
    }
    
    .scrolled-bg-color {
      background-color: #04091e !important;
    }
    
    </style>
    
    <!--a.router-link-exact-active {color: #eb6585;} #active page highlights-->
    
    <script>
    export default {
        name: 'HeadeF',
        data() {
        return {
          toolbarScrolled: false,
        };
      },
      mounted() {
        window.addEventListener('scroll', () => {
          if (window.scrollY > 0) {
            this.toolbarScrolled = true;
            document.querySelector('.q-header').classList.add('scrolled-bg-color');
          } else {
            this.toolbarScrolled = false;
            document.querySelector('.q-header').classList.remove('scrolled-bg-color');
          }
        });
      },
    };
    
    </script>