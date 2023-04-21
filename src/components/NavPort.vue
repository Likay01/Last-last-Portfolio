<template>
    <div class="main">
        <nav class="navbar navbar-light">
  <div class="container p-0">
    <a class="navbar-brand" href="/">
      <img src="https://i.postimg.cc/sg3wGdBx/LINDOKUHLE-MGOQI-logo-2-1.png" alt="" width="90" height="35">
    </a>
  </div>
  <div class="container-fluid m-0">
      <ul class="navbar-nav m-0 mb-2 mb-lg-0">
        <router-link to="/">
          <li class="nav-item">
          <a class="nav-link text-white active" aria-current="page" href="#">Home</a>
        </li>
        </router-link>
        <router-link to="/about">
        <li class="nav-item">
        <a class="nav-link text-white" href="#">About</a>
        </li>
        </router-link>
        <router-link to="/contact">

        <li class="nav-item">
        <a class="nav-link touch" href="#">Contact</a>
        </li>
        </router-link>
      </ul>
    </div>
</nav>  
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
nav{
  background-color:#100f0f;
  width: 100%;
}
.container{
    margin-left: 2px;
    margin-right: 2px;
    width: fit-content;
}
.touch{
    color: #EF5B0E;
}
.container-fluid{
    width: 250px;
}
ul{
    width: 100%;
    display: flex;
    flex-direction: row;
gap: 25px;
}
@media screen and (max-width: 400px){
    img{
        display: none;
    }
    .container{
        display: none;
        margin: auto;
    }
    .navbar{
        padding: 0;
        width: 0;
    }
   .container-fluid{
    padding-left:23vw ;
   }
    .main{
        width: 100vw;
        background: #100f0f;
    }
    }
a{
    text-decoration: none;
}
</style>