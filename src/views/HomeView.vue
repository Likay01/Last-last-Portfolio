<template>
  <body>
    <div class="main">
      <div class="reg-1">
        <div class="in">
          <div class="board">
          <h6 class="intro">HI THERE, I'M </h6>
          <h3 class="name">LINDOKUHLE MGOQI</h3>
          <div class="box">
              <h6>Intern Full-Stack Developer</h6>
      </div>
    </div>
    <div class="pro">
      <img class="imgs" src="https://i.postimg.cc/wMk1R9Q2/DSC-3517.jpg" width="250">
    </div>
        </div>
    </div>
    <div class="three">
      <router-link to="/resume">
      <div class="resume">
  <div class="block">
    <h3 class="res">RESUME</h3>
  </div>
      </div>
      </router-link>
      <router-link to="/projects">
      <div class="projects">
  <div class="block">
    <h3 class="proj">PROJECTS</h3>
  </div>
      </div>
      </router-link>
      <router-link to="/testimonials">
      <div class="testimonial">
  <div class="block">
    <h3 class="test">TESTIMONIALS</h3>
  </div>
      </div>
      </router-link>
    </div>
  </div>
  </body>
</template>
<script>
export default {
  
}
</script>
<style scoped>
body{
  background-color: #100f0f;
}
  .main{
    width: 100vw;
    display: grid;
    margin: 5px;
    gap: 5px;
    opacity: 0;
    animation: fade 0.5s;
animation-delay: 0.5s;
animation-fill-mode: forwards;
  }
  .reg-1{
    width: 98.5vw;
background: #268D8F;
border: 5px solid #0C2B2C;
border-radius: 15px;
height: 50vh;
  }
  .in{
    display: flex;
    margin: auto;
    width: 100vw;
  }
  .three{
    display: flex;
    flex-wrap: wrap;
    height: 50vh;
    gap: 10px;
  }
  .resume{
background: url(https://i.postimg.cc/9XtrzqQj/My-project-1-5.png);
background-size: cover;
border: 5px solid #943707;
border-radius: 15px;
width: 32vw;
opacity: 0;
    animation: fade 0.5s;
animation-delay: 1s;
animation-fill-mode: forwards;
  }
  .resume:hover{
    transform: translateZ(3rem);
  }
  .projects{
    background: url(https://i.postimg.cc/VLgg964x/My-project-1-6.png);
background-size: cover;
border-radius: 15px;
border: 5px solid #C0BB05;
width: 32vw;
opacity: 0;
    animation: fade 0.5s;
animation-delay: 1.5s;
animation-fill-mode: forwards;
  }
  .projects:hover{
    transform: translateZ(3rem);

  }
  .testimonial{
    background: url(https://i.postimg.cc/kG0mfsn5/My-project-1-7.png);
background-size: cover;border-radius: 15px;
border: 5px solid #24722D;
width: 33vw;
opacity: 0;
    animation: fade 0.5s;
animation-delay: 2s;
animation-fill-mode: forwards;
  }
  .testimonial:hover{
    transform: translateZ(3rem);

  }
  .board{
    text-align: start;
    margin:80px ;
  }
  .intro{
font-size: 30px;
font-weight: 200;
color: #f1f1f1;
text-align: start;

  }
  .name{
font-size: 70px;
font-weight: 200;
  }
  .box{
   border: #0C2B2C solid; 
   width: 250px;
   border-radius: 15px;
   margin-left: 190px;
  }
  h3{
    text-decoration: none;
  }
  h6{
    text-align: center;
  }
  .pro{
    margin: auto;  
  }
  img{
    border: #0c2b2c74 solid 3px;
     border-radius: 50%;
  }
  .res{
    font-size: 70px;
    text-align: start;
    margin-top:160px ;
    color: #4b1b038d;
    text-decoration: none;
  }
  .proj{
    font-size: 70px;
    text-align: start;
    margin-top:160px ;
    color: #5f5c038f;
    text-decoration: none;

  }
  .test{
    font-size: 70px;
    text-align: start;
    margin-top:160px ;
    color: #16461cba;
  }
  a{
    text-decoration: none;
  }
  @keyframes scroll {
    0%{
      transform: translateX(0);
    }
    100%{
      transform: translateX(calc(-250px * 9));
    }
  }
  @keyframes fade {
  from{
      opacity: 0;
  }
  to{
      opacity: 1;
  }
}
@media screen and (max-width: 1440px) {
.in{
  height: 50vh;
}
img{
  height: 40vh;
  width: 10vw;
}
.box{
  margin-left: 130px;
  width: 200px;
  height: 8vh;
}
h6{
  font-size: 12px;
  margin-top: 3px;
}
.intro{
  font-size: 25px;
}
.name{
  font-size: 50px;
}
.board{
  width: 50vw;
  margin: auto;
}
}
@media screen and (max-width: 1024px) {
  img{
    width: 15vw;
  }
}
  @media screen and (max-width: 1000px) {
    .pro{
      display: none;
    }
    .board{
      margin: auto;
      text-align: center;
    }
    .in{
      width: 90vw;
      margin-top: 100px;
    }
    .name{
      font-size: 50px;
    }
    .intro{
      text-align: center;
      font-size: 20px;
    }
    .box{
      margin: auto;
      width: 150px;
      height: 20px;
    }
    .reg-1{
      width: 97vw;
    }
    h6{
      font-size: 10px;
    }
    .resume{
      width: 97vw;
    }
    .projects{
      width: 97vw;
    }
    .testimonial{
      width: 97vw;
    }
  }
  @media screen and (max-width: 768px) {
    .in{
margin: auto;
    }
    .name{
      font-size: 37px;
    }
  }
  @media screen and (max-width: 375px) {
    .intro{
      font-size: 12px;
    }
    .name{
      font-size: 27px;
      text-align: center;
    } 
    .box{
  margin-left: px;
  width: 150px;
  height: 5vh;
}
h6{
  font-size: 10px;
  margin-top: 1px;
}
  }
  @media screen and (max-width: 320px) {
    .intro{
      font-size: 12px;
    }
    .name{
      font-size: 27px;
      text-align: center;
    } 
    .box{
  margin-left: px;
  width: 150px;
  height: 5vh;
}
h6{
  font-size: 10px;
  margin-top: 1px;
}
  }
</style>