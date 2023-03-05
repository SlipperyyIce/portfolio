<script setup lang="ts">
import { ref } from 'vue'
import Project from './Project.vue'
import { defineComponent } from 'vue'
import Foot from './Footer.vue'
</script>



<template>
  <div class="section">
    <div class="center text-white">
    <p class="aquamarine">Hi, my name is</p>
    <h1 class="roboto">Daniel Bajomo.</h1>
    <h1 class="roboto" style="opacity: 70%;">I build things for fun (Unemployed)</h1>
    <p class="roboto" style="width: 500px;">I am London-Based computer science student who specialises in building exceptional frontend and backend systems. Currently I am a third year at <span class="aquamarine">Queen Mary London</span> who is focused on gaining more experience in the tech industry.</p>
    <button type="button" class="btn btn-outline-success roboto">Get in Touch  </button>
    </div>
  </div>
  <div class="section">
    <div class="text-white section1">
      <div class="about">
        <p class="aquamarine roboto">01.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">About Me &nbsp;</p>
        <div style="width: 300px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
      </div>
      <div style="text-align: left; width: 450px;">
      <p class="grey">Hello! My name is Daniel and i enjoy creating things that live on the internet. My interest in web development started back in 2012 when i decided.</p>
      <p class="grey">EW imaging i dont know what to type but that is fine lololol <span class="aquamarine" style="opacity: 100%!important;">IM COOL</span> apple sauce.</p>
      </div>
    </div>
  </div>
  <div class="section">
    <div class="text-white section1">
      <div class="about">
        <p class="aquamarine roboto">02.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">Recent Projects&nbsp;</p>
        <div style="width: 250px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
      </div>

      <div class="flex">
        <img class="prj-img" src=# alt="">
        <div style="text-align: right;"><p class="aquamarine roboto">Featured Project</p>
        <p style="font-size: large; font-weight: bold;">Blackjack</p></div>

      </div>
      
    </div>
  </div>

  <div class="pj">
    <Project :scroll="200" />
    <Project :scroll="300"  />
  </div>
  <Foot/>
  
</template>

<script lang="ts">
export default defineComponent({

    methods: {
        horizontal_parrallax(){
          var scrollY = window.scrollY;
          var x = (scrollY * 52) / 100;    
          var clamped_x = Math.min(x,260) // picks smaller value to clamp max value
          //this.$refs.test.style.transform = "translateX(" + clamped_x + "px)";

        },

    },
    
    mounted() {     
        document.addEventListener("scroll", this.horizontal_parrallax);
    }
    
});
</script>

<style scoped>
.par{
  transform: translateZ(-20px);
}
.flex{
  display: flex;
}
.prj-img{
  width: 500px;
  height: 300px;
}
.section{
  background-color: #000000;
  min-height: 720px;
  text-align: left;
}
.grey{
  color: #666666;
}
.about{
  display: flex;
  padding-top: 40px;
  align-items: center;
}
.aquamarine{
  color: aquamarine;
}
.section1{
  left: 25%;
  position: relative;
  width: fit-content;
}
.btn-outline-success {
    --bs-btn-color: aquamarine;
    --bs-btn-border-color: aquamarine;
    --bs-btn-hover-color: black;
    --bs-btn-hover-bg: aquamarine;
    --bs-btn-hover-border-color: aquamarine;
    --bs-btn-focus-shadow-rgb: 25, 135, 84;
    --bs-btn-active-color: #fff;
    --bs-btn-active-bg: aquamarine;
    --bs-btn-active-border-color: aquamarine;
    --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.roboto{
  font-family: Roboto-Mono;
}
.opaque{
  opacity: 40%;
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