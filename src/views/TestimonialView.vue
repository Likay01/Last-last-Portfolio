<template>
    <div class="heart">
          <div class="band">
            <div class="banding">
           <div class="container " id="cards">
      <div class="card sorted " style="width: 27rem;" >
          <img src="https://i.postimg.cc/W39QpKyp/Joel-Profile.jpg" class="images card-img-top" alt="...">
    <div class="card-bodyspace">
      <h5 class="card-title">Joel Mukanya </h5>
      <p class="card-text">Lindokuhle is a very creative and well-behaved student. He does enjoy working with his classmates and works well on his project.I will be very delighted to see him get hired as a developer</p>
          </div>
            </div>
              </div>
  
              <div class="container " id="cards">
      <div class="card sorted " style="width: 27rem;" >
          <img src="https://i.postimg.cc/BZk3FGs8/Screenshot-20221103-143935-1-1.jpg" class="images card-img-top" alt="...">
    <div class="card-bodyspace">
      <h5 class="card-title">Sive Shabane </h5>
      <p class="card-text">Always willing to lend a helping hand whenever he can. He creates a good working environment by being supportive. Focused on the task at hand and does it to the point of perfecting it. Respecting of his colleagues.</p>
          </div>
            </div>
              </div>
  
  
              <div class="container " id="cards">
      <div class="card sorted " style="width: 27rem;" >
          <img src="https://i.postimg.cc/Kz8bHftL/Sakhe.jpg" class="images card-img-top" alt="...">
    <div class="card-bodyspace">
      <h5 class="card-title">Sakhe Mzolisa</h5>
      <p class="card-text">Lindo is a charismatic and bubbly person, innovative would be the word to describe him as he is tree with filled with fresh ideas. A great person to work with, always willing to assist. He standouts amongst a crowd.</p>
          </div>
            </div>
              </div>
  
  
              <div class="container " id="cards">
      <div class="card sorted " style="width: 27rem;" >
          <img src="https://i.postimg.cc/9MxgMX7y/candice-2022.jpg" class="images card-img-top" alt="...">
    <div class="card-bodyspace">
      <h5 class="card-title">Candice Amon </h5>
      <p class="card-text">Has a great sense of humor but also has a very mature attitude. Good communication skills and understand his responsibilities are a priority. Has the ability to know when necessary to have a courageous attitude.</p>
          </div>
            </div>
              </div>
  
  
              <div class="container " id="cards">
      <div class="card sorted " style="width: 27rem;" >
          <img src="https://i.postimg.cc/mkdHQ5mM/1679909303854.jpg" class="images card-img-top" alt="...">
    <div class="card-bodyspace">
      <h5 class="card-title">Timothy Jennike </h5>
      <p class="card-text">'Lindokuhle is a guy that can accomplish anything he puts his mind too.  He enjoys learning about new things and helping others when they have trouble with something.</p>
          </div>
            </div>
              </div>
  
  
              <div class="container " id="cards">
      <div class="card sorted " style="width: 27rem;" >
          <img src="https://i.postimg.cc/T1nwCH2h/C11-Brandon-Swinton-1.jpg" class="images card-img-top" alt="...">
    <div class="card-bodyspace">
      <h5 class="card-title">Brandon Swinton</h5>
      <p class="card-text">Lindokuhle Mgoqi is hard worker, Always finds solutions to any problem .He is very committed to the work he represents .I enjoy working with lindokuhle  as a fellow developer.</p>
          </div>
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
      height:100vh;
      background-color: #100f0f;
      font-family: 'Montserrat';
      font-style: normal;
      font-weight: 400;
      display:flex;
  position: relative;
  place-items: center;
  overflow: hidden;
    }
    .card{
      width: 0;
      height: 30rem;
      background-color: #25742e94;
      transition: transform 2s;
      object-fit: contain;
    }
    #cards{
       display: inline-flex; 
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
  height: 20rem;
  width: 100%;
  }
  .card:hover{
    transform: translateZ(3rem);
  }
  .banding{
    display: flex;
    width: calc(250px * 18);
    animation: scroll 40s linear infinite;
    margin-top: 4rem;
  }
  .band{
      background-color:#3CCF4E; 
      height: 90vh;
  }
  .banding:hover{
    animation-play-state: paused;
  }
  @keyframes scroll {
    0%{
      transform: translateX(0);
    }
    100%{
      transform: translateX(calc(-250px * 9));
    }
  }
  @media screen and (max-width: 1000px) {
    .banding{
        margin-top: 2.5%;
    }
.card-bodyspace{
    font-size: 12px;
    margin: 30px;
    font-weight: 400;
}
 .card{
    height: 33rem;
    widows: 7rem;
 }
  }
  </style>