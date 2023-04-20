<template>
    <div class="heart">
     <div class="reg-1">
      <h1>RESUME</h1>
      <div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2017</h2>
      <h6 class="card-Subtitle text-dark">Maitland High School</h6>
      <p>I attended high school at Maitland High School</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2021</h2>
      <h6 class="card-Subtitle text-dark">Maitland High School</h6>
      <P>Became a RCL Member and my role was treasurer.</P>
      <p>matriculated with a Bachelor Pass.</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2022</h2>
      <h6 class="card-Subtitle text-dark">Life Choices Academy</h6>
      <p>Aspiring to become a Wed developer</p>
    </div>
  </div>
    <div class="container right">
    <div class="content">
      <h2>2023</h2>
      <h6 class="card-Subtitle text-dark">Life Choices Academy</h6>
      <p>Graduated from the Academy. </p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2023</h2>
      <h6 class="card-Subtitle text-dark">Life Choices Studio</h6>
      <p>Doing my first phase internship at LC studio</p>
    </div>
  </div>
  </div>
  <h1 class="skills">SKILLS</h1>
  <div class="box row">
    <img src="https://i.postimg.cc/T3q2sGnq/HTML.png" alt="HTML" class="col-6">
    <img src="https://i.postimg.cc/44V3cznS/CSS.png" alt="CSS" class="col-6">
    <img src="https://i.postimg.cc/ZRmMMtF3/bootstrap.png" alt="BOOTSTRAP" class="col-6">
    <img src="https://i.postimg.cc/HsWCL5M5/CSS-1.png" alt="JAVASCRIPT" class="col-6">
    <img src="https://i.postimg.cc/1Rrg8LWd/vue.png" alt="VUE.JS" class="col-6">
    <img src="https://i.postimg.cc/1RfTXQ5m/MySQL.png" alt="MYSQL" class="col-6">
    <img src="https://i.postimg.cc/nz4gTfL9/CSS-2.png" alt="NODE.JS" class="col-6">
    <img src="https://i.postimg.cc/QMwVcD5Q/Screenshot-2023-04-17-143315.png" alt="figma" class="col-6">

  </div>
  <div class="mine">
    
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
    height:250vh;
    background-color: #100f0f;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
  }
  .reg-1{
    box-sizing: border-box;
width: 97vw;
height: 250vh;
margin: auto; 
background: #EF5B0E;
border: 5px solid #943707;
border-radius: 15px;
  }
  h1{
    color: #943707;
    font-size: 68px;
  }
  .box{
    margin-left: 20px;
  }
  .skills{
    margin-top:8rem;
  }
  
/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin-right: 32rem;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: #943707;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: 15.2rem;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: #EF5B0E;
  border: 4px solid #943707;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50.8%;
}

/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid #943707;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent #943707;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent #943707 transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: rgba(255, 255, 255, 0.299);
  position: relative;
  border-radius: 6px;
  color: #562005;
}
@media screen and (max-width: 770px) {
    .left::after, .right::after {
        display: none;
    }
}
/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 1000px) {
  /* Place the timelime to the left */
  .timeline::after {
 display: none;
  }
  .timeline{
    margin: auto;
  }
  .content{
    margin:auto;
    width:50vw;
  }
  /* Full-width containers */
  .container {
  width: 100vw;
  }
  
  /* Make sure that all arrows are pointing leftwards */
  .container::before {
display: none;  
}

  /* Make sure all circles are at the same spot */
  .left::after, .right::after {
  left: 90px;
  }
  
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
img{
  width: 10rem;
  margin: auto;
}
.box{
  margin:auto;
}
</style>