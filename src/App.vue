<template>
  <nav>
 <NavPort/>
  </nav>
  <body>
     <router-view/>
 
  </body>
  <footer>
    <FootPort/>
  </footer>
</template>
<script>
import NavPort from '@/components/NavPort.vue';
import FootPort from '@/components/FooterPort.vue';
export default {
  components: {
NavPort,
FootPort
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap');

#app {
font-family: 'Montserrat', sans-serif;font-style: normal;
text-align: center;
font-weight: 400;
}
body{
  min-height: 100vh; 
  overflow-x: hidden;
  background-color:#100f0f ;
  width: 100%;
}
nav {
  padding: 0;
}

nav a {
  font-weight: bold;
  color: #f1f1f1;
}

nav a.router-link-exact-active {
  color: #f1f1f1;
}
footer{
  background-color: #f1f1f1;
  text-align: center;
  color: #100f0f;
}
@media screen and (max-width: 600px) {
  body{
    overflow-x: hidden;
  }
}
</style>
