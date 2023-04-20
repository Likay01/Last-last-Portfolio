<template>
        <div class="heart">
        <form  
        action="https://formspree.io/f/myyvbyod"
        method="POST">
      <div class="mb-3">
    <label for="exampleInputName1" class="form-label">Name</label>
    <input type="text" class="form-control" id="exampleInputName1">
  </div>        
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputMassage1" class="form-label">Message </label>
    <textarea type="message"  name="message" class="form-control" id="exampleInputMessage1"></textarea>
  </div>
  <button type="submit" class="btn">Send</button>
</form>

<div class="addy">
    <div class="cell col">
        <p>(061)337-9806</p>
    </div>
    <div class="home col">
        <p>
        7 Donana Galo
        Gugulethu<br/>
        7750
        </p>
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
 background-image: url(https://i.postimg.cc/CM388GYZ/My-project-1-4.png);
 background-position: center;
 background-size: cover;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    display:flex;
position: relative;
place-items: center;
overflow: hidden;
  }
  form{
    margin-left: 25px;
    color: white;
    text-align: start;
  }
  h1{
       margin-left: 25px;
    color: white;
    text-align: start; 
  }
  input{
    width: 600px;    
  }
.btn{
    background-color: #EF5B0E;
    color: black;
    font-weight: 700;
}
.form-text{
    color: #EF5B0E;

}
.addy{
    display: flex;
    position: relative;
    text-align: start;
    top: 15rem;
    right: 37.5rem;
}
.cell{
    color: #EF5B0E;
}
.home{
    color: white;
}

@media screen and (max-width: 1000px) {
   input{
        margin: auto;
        width: 90vw;
    }
    p{
    width: 150px;
}
.addy{
margin-left: 240px;   
    }
}
</style>