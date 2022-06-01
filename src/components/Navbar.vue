<template>
     <nav class="navbar navbar-expand-lg  fixed-top  " id="navbar">
        
    <div class="container-fluid"> 
    <router-link to="/" class="navbar-brand">

  <h2>MrAdora</h2>
    </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="fa fa-bars"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 p-3 text-center mb-lg-0">
        <li class="nav-item">
          <router-link :to="{'name':'home'}" class="nav-link">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link :to="{'name':'home'}" class="nav-link">About</router-link>
        </li>

        
        <li class="nav-item">
          <router-link to="#" class="nav-link">Services</router-link>
        </li>
         <li class="nav-item">
          <router-link to="#" class="nav-link">Team</router-link>
        </li>
        <li class="nav-item">
          <router-link to="#" class="btn btn-outline-white n-btn nav-link shadow-none">Get a quota</router-link>
          
        </li>
      </ul>
    </div>
        </div>
    </nav>
</template>

<script>
export default {
  name: 'Navbar',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}



nav{
  background-color:rgb(255, 87, 51) ;
}

nav .nav-link{
  color: #ffffff;
  font-size: 1rem;
}

.navbar-brand{
  color: #ffffff;
  margin: 0 10px;
  font-size: 2.3rem;
}

</style>
