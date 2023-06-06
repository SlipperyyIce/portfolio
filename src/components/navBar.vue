<script lang="ts">
import { defineComponent } from 'vue'
export default {
};
</script>
<template>
<nav class="navbar navbar-expand-sm bg-black">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img src="./assets/logo.png" style="height: 50px;" /></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span ><i class="fa-solid fa-code" style="color:#7fffd4;"></i></span>
    </button>
    <div class="collapse navbar-collapse justify-content-sm-end" id="navbarSupportedContent">
      <span>
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 text-right">
        <li class="nav-item">
          <a class="nav-link active text-white roboto" href="#aboutme"><span class="num_labels">01.</span>&nbsp;About Me </a> 
        </li>
        <li class="nav-item">
          <a class="nav-link text-white roboto" href="#project"><span class="num_labels">02.</span>&nbsp;Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white roboto" href="#contact"><span class="num_labels">03.</span>&nbsp;Contact</a> 
        </li>
        
      </ul>
    </span>
    
      
    </div>
  </div>
</nav>

</template>

<style scoped>
.m10 {
  margin-top: -10px;
}

.text-right{
  text-align: right;
}

.roboto{
  font-family: Roboto-Mono;
  font-size: small;
}
.num_labels{

    color: aquamarine;
}

</style>

