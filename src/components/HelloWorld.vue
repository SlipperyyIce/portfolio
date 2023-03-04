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
  
  <div class="pj">
    <Project :scroll="200" />
    <Project :scroll="300"  />
  </div>
  <div class="grey">
    <div class="par">
      
      <h1 ref="test" class="about">ABOUT ME</h1>
      <p>I am a dude with a specific set of skills help me why cuz im cool so i need a job pls hire me i want money i am BROKE.</p>
    </div>
  </div>
</template>

<script lang="ts">
export default defineComponent({

    methods: {
        horizontal_parrallax(){
          var scrollY = window.scrollY;
          var x = (scrollY * 52) / 100;    
          var clamped_x = Math.min(x,260) // picks smaller value to clamp max value
          this.$refs.test.style.transform = "translateX(" + clamped_x + "px)";

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
.intro{
  background-color: #000000;
  min-height: 720px;
}
.grey{
  background-color: #c3c1c1;
  min-height: 600px;
}
.about{
  width: fit-content; 
  color: #000000;
  font-size: 100px;
  opacity: 60%;
  padding-top: 40px;
}
.pj{
  background-color: #000000;
  min-height: 600px;
  padding: 10px;
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