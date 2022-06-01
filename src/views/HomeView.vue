<template>

<Navbar />
<section class="hero ">
  <div class="container  ">
    <div class="row">
      <div class="col-lg-6 mt-5">
          <div class="hero-title mt-5">
            <h2> MrAdora is here to help start your brand </h2>
            <p>MrAdora has helped many brands build their identity by using modern technologies</p>
          </div>
          <div class="hero-btn">
            <button class="btn btn-outline-white h-btn">Get a quota</button>
          </div>
      </div>
      <div class="col-lg-6 mt-5">
        <img src="../assets/hero.png" alt="">
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

</style>