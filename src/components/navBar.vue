<script lang="ts">
import { defineComponent } from 'vue'
export default {
};
</script>
<template>
<div>
<nav class="navbar navbar-expand">
  
  <a class="navbar-brand text-white" href="#" style="padding-left: 30px;"><img src="./assets/logo.png" style="height: 50px;" /></a>


  <div class="position-absolute end-0 " id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto ">
      <li class="nav-item active">
        <a class="nav-link text-white roboto" href="#"><span class="num_labels">01.</span>&nbsp;CV </a>          
      </li>
      <li class="nav-item active">
        <a class="nav-link text-white roboto" href="#"><span class="num_labels">02.</span>&nbsp;Projects</a>          
      </li>
       
      <li class="nav-item active">
        <a class="nav-link text-white roboto" href="#"><span class="num_labels">03.</span>&nbsp;Contact</a>          
      </li>
      
           
    </ul>
    
  </div>

</nav>
</div>
</template>

<style scoped>

nav {
    background-color: #000000;   
    height: 50px;   
}

.roboto{
  font-family: Roboto-Mono;
  font-size: small;
}
.num_labels{

    color: aquamarine;
}
</style>

