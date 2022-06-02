<template>

<Navbar />
<section class="hero ">
  <div class="container  ">
    <div class="row">
      <div class="col-lg-6 col-md-6 col-sm-12 mt-5">
          <div class="hero-title mt-5">
            <h2> MrAdora is here to relieve your depression </h2>
            <p>MrAdora has helped several people overcome their fears through proper counselling</p>
          </div>
          <div class="hero-btn">
            <button class="btn btn-outline-white shadow-none h-btn"> Message MrAdora </button>
          </div>
      </div>
      <div class="col-lg-6 col-md-6  d-none d-sm-block mt-5">
        <img src="../assets/hero.png" alt="">
      </div>
    </div>
  </div>
</section>

<section class="about">
  <div class="container">
    <div class="row justify-content-center mt-5">
      <div class="col-lg-5 text-center col-md-6">
        <img src="../assets/questionman.png" alt="">
      </div>
      <div class="col-lg-7 col-md-6 mt-5">
        <div class="about-heading">
          <h1 class="text-main heading-lg mt-5">What is MrAdora?</h1>
        </div>
        <div class="about-words text-justify">
          <p class="text-md">
            MrAdora was birthed from the continuous growth of depression and mortality rate in the universe. MrAdora helps you overcome your depression and fears by having few private conversations with you.
          </p>
        </div>
      </div>
      
    </div>
  </div>

  <div class="container">
    <div class="row justify-content-center mt-5">
        <div class="col-lg-5 text-center col-md-6">
        <img src="../assets/questionwoman.png" alt="">
      </div>
      <div class="col-lg-7 col-md-6 mt-5">
        <div class="about-heading">
          <h1 class="text-main heading-lg mt-5">Are my chats secure with MrAdora?</h1>
        </div>
        <div class="about-words text-justify">
          <p class="text-md">
           MrAdora would never leak your chats. Your chats are 100% secured with MrAdora.
          </p>
        </div>
      </div>
   
    </div>
  </div>


<div class="container">
    <div class="row justify-content-center mt-5">
        
      <div class="col-lg-7 col-md-6 mt-5">
        <div class="about-heading">
          <h1 class="text-main heading-lg mt-5">Can MrAdora help with my longtime depression?</h1>
        </div>
        <div class="about-words text-justify">
          <p class="text-md">
           MrAdora has been around for a very long time dealing with depression of over several years. Give MrAdora a chance
           to help you forget your depressions.
          </p>
        </div>
      </div>

      <div class="col-lg-5 text-center col-md-6">
        <img src="../assets/ladyconfused.png" alt="">
      </div>
   
    </div>
  </div>


  <div class="container">
    <div class="row justify-content-center mt-5">
        <div class="col-lg-5 text-center col-md-6">
        <img src="../assets/questionwoman.png" alt="">
      </div>
      <div class="col-lg-7 col-md-6 mt-5">
        <div class="about-heading">
          <h1 class="text-main heading-lg mt-5">How do I get started with MrAdora?</h1>
        </div>
        <div class="about-words text-justify">
          <p class="text-md">
           Getting started is easy, all you have to do is fill the get in touch form <a href="" class="btn btn-outline-white a-btn">below</a> 
          </p>
        </div>
      </div>
   
    </div>
  </div>

</section>


</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar
  }
}
</script>
<style scoped>


.heading-lg{
  font-size: 3rem;
}


.heading-md{
  font-size: 2rem;
}

.heading-sm{
  font-size: 1.5rem;
}

.heading-lg-md{
  font-size: 2.5rem;
}

.heading-xs{
  font-size:1rem;
}

.text-main{
  color: var(--main-color);
}

.text-lg{
  font-size: 2rem;
}

.text-md{
  font-size: 1.5rem;
}

.text-sm{
  font-size: 1rem;
}

.text-xs{
  font-size: .9rem;
}

.text-lg-md{
  font-size: 1.7rem;
}
.text-md-md{
  font-size: 1.2rem;
}






.hero{
  padding:60px 0;
  background-image: linear-gradient(to right, rgb(255, 87, 51) 45%,rgb(223, 97, 69) );
  color: #ffffff;
}

.hero h2{
  font-size:3.5rem;
}

.hero p{
  font-size:1.4rem;
}

.hero img{
  width:100%;
}
.hero-title{
  padding: 3px;
}

.h-btn{
  padding: 15px 60px;
  background:#ffffff;
  border: 2px var(--main-color) solid;
  border-radius: 15px;
}

.a-btn{
  padding: 10px;
  background:var(--main-color);
  border: 2px #ffffff solid;
  border-radius: 15px;
}


.about{
  padding: 60px 0;
}

.about img{
  width: 450px;
}




</style>