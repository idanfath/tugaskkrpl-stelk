<template>
  <q-layout>

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
