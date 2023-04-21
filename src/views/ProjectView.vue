<template>
    <div class="heart">
          <div class="band">
           <h1>Projects</h1> 
            <div class="banding row">
  
  <div class="card vinyl col-12" style="width: 30rem;">
    <div class="card-body">
      <h5 class="card-title">Vinylique</h5>
      <h6 class="card-subtitle mb-2">E-commerce </h6>
      <p class="card-text">This is a vinyl-selling store I made, called Vinylique.</p>
      <a href="https://github.com/Likay01/E-com-EOM-project.git" class="card-link text-black">Git</a>
      <a href="https://leafy-froyo-7e1c3b.netlify.app/" class="card-link live">Live</a>
    </div>
  </div>
  
  <div class="card crtv col-12" style="width: 30rem;">
    <div class="card-body">
      <h5 class="card-title">Crtv Studios.</h5>
      <h6 class="card-subtitle mb-2">E-commerce</h6>
      <p class="card-text">This is a art-selling store, which has painting and photographs.</p>
      <a href="https://github.com/Likay01/CRTVstudios.git" class="card-link text-black">Git</a>
      <a href="https://jolly-begonia-c084b5.netlify.app" class="card-link live">Live</a>
    </div>
  </div>
  
  <div class="card proud col-12" style="width: 30rem;">
    <div class="card-body">
      <h5 class="card-title">Proud Black</h5>
      <h6 class="card-subtitle mb-2">Grid practise</h6>
      <p class="card-text">This is what I accomplish using grid.</p>
      <a href="https://github.com/Likay01/homework-tryout.git" class="card-link text-black">Git</a>
      <a href="https://blackpower.netlify.app/" class="card-link live">Live</a>
    </div>
  </div>
  
  <div class="card big col-12" style="width: 30rem;">
    <div class="card-body">
      <h5 class="card-title">Big Stepper</h5>
      <h6 class="card-subtitle mb-2">E-commerce (collaboration with Siphamandla)</h6>
      <p class="card-text">A sneaker-selling store that my colleague and I built, I was on the front-end.</p>
      <a href="https://github.com/Likay01/BigStepper-Fullstack-EOMP.git" class="card-link text-black">Git</a>
      <a href="https://big-stepper.web.app/" class="card-link live">Live</a>
    </div>
  </div>
  
  <div class="card cap col-12" style="width: 30rem;">
    <div class="card-body">
      <h5 class="card-title">Capital Control</h5>
      <h6 class="card-subtitle mb-2">E-commerce (collaboration with a group)</h6>
      <p class="card-text">this was a group activity, where we had to build an app to prevent and help people from falling into debt. </p>
      <a href="https://github.com/Likay01/Cap-ctrl.git" class="card-link text-black">Git</a>
      <a href="https://capitalcontrol.netlify.app/" class="card-link live">Live</a>
    </div>
  </div>
  
  <div class="card cal col-12" style="width: 30rem;">
    <div class="card-body">
      <h5 class="card-title">Calculator</h5>
      <h6 class="card-subtitle mb-2">Calculator</h6>
      <p class="card-text">This is a Calculator I accomplished with JS.</p>
      <a href="https://github.com/Likay01/Calculator.git" class="card-link text-black">Git</a>
      <a href="https://lkcalculator.netlify.app" class="card-link live">Live</a>
    </div>
  </div>
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
      height:auto;
      background-color: #100f0f;
      font-family: 'Montserrat';
      font-style: normal;
      font-weight: 400;
      display:flex;
  position: relative;
  place-items: center;
  overflow: hidden;
    }
    .card-body{
      margin-top: 14rem;
      text-align: start;
      font-weight: 700;
      color: white;
      background-color: #100f0f82;
    }
    .card{
      width: 30rem;
      height: 25rem;
      background-color: #C0BB05;
      transition: transform 2s;
      object-fit: contain;
  margin: 5px;
  padding: 0;
    }
    h1{
    color: #C0BB05;
    }
    .live{
      color: rgb(113, 0, 0);
    }
    .card-link{
      text-decoration: none;
    }
    #cards{
       display: flex;
       flex-direction: column; 
       flex-wrap: wrap;
       gap: 3rem;
       position: relative;
   height:30rem;
   margin: 0;
   width: 30rem;
   display: grid;
   place-items: center;
  padding: 10px;
  perspective: 700px;
      }
  
  img{
  height: 200px;
  width: 100%;
  }
  .band{
      background-color:#FFF804; 
      height: auto;
      width: 100vw;
      opacity: 0;
      animation: fade 0.5s;
animation-delay: 0.5s;
animation-fill-mode: forwards;
  }
  .banding{
    height: auto;
    margin: 15px;
  }
  .vinyl{
    background-image: url(https://i.postimg.cc/CxpRLM7q/Vinylique-1.png);
    background-position: center;
    background-size: cover;
  }
  
  .crtv{
    background-image: url(https://i.postimg.cc/YqhPqM0M/My-project-1.png);
    background-position: center;
    background-size: cover;
  }
  
  .proud{
    background-image: url(https://i.postimg.cc/nc43LrZ8/proudblack-1.png);
    background-position: center;
    background-size: cover;
  
  }
  
  .big{
    background-image: url(https://i.postimg.cc/RFpjXFhp/My-project-1-1.png);
    background-position: center;
    background-size: cover;
  
  }
  
  .cap{
    background-image: url(https://i.postimg.cc/WzpjW3MQ/My-project-1-3.png);
    background-position: center;
    background-size: cover;
  
  }
  
  .cal{
    background-image: url(https://i.postimg.cc/Bv5dr3Qs/My-project-1-2.png);
    background-position: center;
    background-size: cover;
  
  }
  @keyframes fade {
  from{
      opacity: 0;
  }
  to{
      opacity: 1;
  }
}
  @media screen and (max-width: 1000px) {
    .card{
      margin-bottom: 30px;
    }
    .banding{
        margin: 12px;
    }
    .band{
        margin: auto;
    }
  }
  </style>