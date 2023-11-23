<template>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0" />
  <q-layout>
  <div class="header-fix">
  <q-header class="header bg-dark">
      <h1 id="title" class="title" style="color: white;">SCHOENE</h1>
      <nav style="display: flex;">
        <router-link to="/">Home</router-link> 
        <router-link to="/shop">About</router-link>
        <router-link to="/Blog">Erik</router-link> 
        <router-link to="/Contact">Vmxk?</router-link> 
        <router-link to="/shopping_bag" class="router-link"><span class="material-icons"> shopping_bag</span>(10)</router-link>
        <router-link to="/person"><span class="material-icons" >person</span></router-link>
      </nav>
    </q-header>
  </div>  


  <q-page-container>
    <RouterView/>
  </q-page-container>

  </q-layout>
</template>

<style>

span.last.material-icons {
  margin-right: 0;
}

span.material-icons {
  font-size: 20px;
  margin-right: 5px;
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
  padding: 0px 106px;
  justify-content: space-between; 
}

#title {
  margin: 0; 
}

nav {
  display: flex;
}

nav a {
  color: #ffffff;
  margin-right: 25px; 
  text-decoration: none; 
}

nav a:last-child {
  margin-right: 0; 
}
 
span {
  margin-right: 20px;
  font-size: 50px;
  
}

.router-link {
    display: flex;
    align-items: center;
    text-decoration: none; 
  }

.material-symbols-outlined {
  margin-right: 5px; 
}

</style>

<!--a.router-link-exact-active {color: #eb6585;} #active page highlights-->

<script>

</script>
