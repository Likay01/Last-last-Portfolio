<template>
  <div class="heart">
    <div class="reg-1">
      <router-link to="/" class="icon"><i class="fa-solid fa-circle-arrow-left" style="color: #5e2503;"></i></router-link>
<p>"</p>
      <div class="col text">
  <h5>I was born and raised in Cape Town, South Africa, on December 25th, 2002. I am a certified full-stack web developer and graduated from Maitland High School in 2021. Despite being raised by a single mother and living with my uncle and aunt, I have remained a humble young man with a passion for creativity. In my leisure time, I enjoy drawing and music production. As a dedicated individual, I am always looking for new and innovative ideas to enhance my skills. In this rapidly evolving technological age, I am committed to finding better ways to succeed and stay ahead of the curve.</h5>
</div>
<div class="col pic">
  <img src="https://i.postimg.cc/wMk1R9Q2/DSC-3517.jpg" alt="">
</div>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
  .heart{
    height:100vh;
    background-color: #100f0f;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
  }
  .reg-1{
    display: flex;
    box-sizing: border-box;
position: absolute;
width: 95vw;
height: 100vh;
margin-left: 25px; 
background: #EF5B0E;
border: 5px solid #943707;
border-radius: 15px;
opacity: 0;
animation: fade 0.5s;
  animation-delay: 0.5s;
  animation-fill-mode: forwards;
  }
  h5{
    text-align: start;
    margin-top: 110px;
    margin-left: 40px;
    font-size: 25px;
    color: #552005;
  }
  img{
width: 477px;
height: 464px;
margin-top: 12%;
border-radius: 15px;
  }
  .icon{
    position: relative;
    top: 10px;
    left: 10px;
font-size: 60px;
  }
  p{
   font-size: 60px;
   position: absolute;
width: 103px;
height: 114px;
left: 50px;
top: 95px;
font-family: 'Abhaya Libre';
font-style: normal;
font-weight: 400;
font-size: 200px;
line-height: 122px;
/* or 61% */
color: rgba(148, 54, 7, 0.479);
  }
  .text{
    word-wrap: break-word;
  }
  @keyframes fade {
  from{
      opacity: 0;
  }
  to{
      opacity: 1;
  }
}

  @media screen and (max-width: 1440px){
    .heart{
      height:100vh;
    }
    h5{
  margin-top: 40px;
  font-size: 34px;
}
    p{
      display: none;
    }
    .text{
      margin: 40px;
    }
    .reg-1{
height:90vh;
margin: 30px;
    }
img{
  display: none;
} 
.pic{
  display: none;
}
p{
 margin: auto;
  word-wrap: break-word;
}
h5{
    text-align: start;
  margin:0;
    color: #552005;
  }
  }
  @media screen and (max-width: 1024px){
.heart{
  height: 100vh;
}
.reg-1{
  height: 90vh;
}
h5{
  margin-top: 40px;
  font-size: 30px;
}
  }
  @media screen and (max-width: 768px){
.heart{
  height: 100vh;
}
.reg-1{
  height: 90vh;
}
h5{
  font-size: 28px;
}
  }
  @media screen and (max-width: 425px){
.heart{
  height:145vh;
}
.reg-1{
height: 140vh;
} 
 }
 @media screen and (max-width: 375px){
 .reg-1{
  height: 80vh;
 }
 .heart{
  height: 200vh;
 }
 }
 @media screen and (max-width: 320px){
 .reg-1{
  height: 180vh;
 }
 .heart{
  height: 185vh;
 }
 }
</style>
