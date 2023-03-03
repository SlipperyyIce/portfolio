<script setup lang="ts">
import { ref } from 'vue'
import Project from './Project.vue'
import { defineComponent } from 'vue'

</script>

<template>
  <div class="intro">
    <div class="center text-white">
    <h1 class="text-white scrip_font">Daniel Bajomo</h1>
    <p style="margin-top: 70px;">Comp Science Graduate</p>
    </div>
  </div>
  <div class="grey">
    <div class="par">
      
      <p id="test">sssssss</p>
    
    </div>
  </div>
  <div class="pj">
    <Project/>
    <Project/>
  </div>
</template>

<style scoped>
.par{
  transform: translateZ(-20px);
  
}
.intro{
  background-color: #000000;
  min-height: 720px;
}
.grey{
  background-color: #c3c1c1;
  min-height: 600px;
}
.pj{
  background-color: #ffffff;
  min-height: 600px;
}
.scrip_font{
  font-family: "Scriptin";
  font-size: 80px;
}
.center{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>
