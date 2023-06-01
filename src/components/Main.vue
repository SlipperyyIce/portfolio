<script setup lang="ts">
import { ref } from 'vue'
import { defineComponent } from 'vue'
import Foot from './Footer.vue'
</script>

<template>
  <div class="section">
    <div class="center text-white">
    <p class="aquamarine">Hi, my name is</p>
    <h1 class="roboto">Daniel Bajomo.</h1>
    <h1 class="roboto" style="opacity: 70%;">Computer Systems Gradaute (2023)</h1>
    <p class="roboto" style="width: 500px;">I am an ambitious and dedicated London-based computer science student with a passion for building exceptional frontend and backend systems. Currently I’m a graduate of <span class="aquamarine">Queen Mary</span> University of London and am actively seeking opportunities to contribute to the tech industry. I strive to create innovative solutions that exceed expectations. </p>
    <p class="roboto" style="width: 500px;">In this portfolio, I invite you to explore the projects I have undertaken, showcasing my skills, dedication.</p>
    <button type="button" class="btn btn-outline-success roboto" onclick="document.getElementById('contact').scrollIntoView({ behavior: 'smooth' })">Get in Touch  </button>
    </div>
  </div>
  <div class="small_section">
    <div class="text-white section1">
      <div class="about">
        <p id="aboutme" class="aquamarine roboto">01.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">About Me &nbsp;</p>
        <div style="width: 300px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
      </div>
      <div style="text-align: left; width: 450px;">
      <p class="white roboto">I am a <span class="aquamarine" style="opacity: 100%!important;">highly motivated</span> computer science graduate with a strong foundation in programming and software development.</p>
      <p class="white roboto"> I have experience in full-stack web development, database management, and system design. Passionate about technology, I actively seek out opportunities to stay updated with the latest advancements in the field. With excellent problem-solving skills and a drive for excellence, I am eager to contribute my expertise to a dynamic and innovative company. Let's create groundbreaking solutions together!</p>
      </div>
    </div>
  </div>
  <div class="section">
    <div class="text-white section1">
      <div class="about">
        <p id="project" class="aquamarine roboto">02.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">Recent Projects&nbsp;</p>
        <div style="width: 250px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
      </div>

      <div class="flex" style="width: 700px; justify-content: space-between;">
        <img class="prj-img" src='./assets/Expense_Cover.png' >
        <div style="text-align: right; position: relative; left: -100px;">
          <p class="aquamarine roboto">Featured Project</p>
          <p style="font-size: large; font-weight: bold; margin-top: -10px;">Expenses App</p>
          <div class="prj-overview roboto">This project shows an expense application I made using Google's Firebase api. Allowing users to submit expenses which can then be approved or rejected by a line manager.</div>
          <p class="grey">Firebase API&nbsp;&nbsp;  Next.js</p>
          <span>
            <a href="https://github.com/SlipperyyIce/fdm-expenses-app-main" target="_blank"><img src="./assets/git_icon.png" class="icon "></a>
            <a href="https://slipperyyice.github.io/fdm-expenses-app-main/" target="_blank"><img src="./assets/hyperlink_icon.png" class="icon2"></a>
          </span>          
        </div>
      </div>

      <div class="flex" style="width: 700px; justify-content: space-between;">
        <div>
          <p class="aquamarine roboto">Featured Project</p>
          <p style="font-size: large; font-weight: bold; margin-top: -10px;">Deep Learning Classification</p>
          <div class="prj-overview roboto" style="z-index: 1; position: relative;">MATLAB code for the deep learning model I trained for my final year project to classiy different signals.</div>
          <p class="grey">MATLAB</p>
          <span>
            <a href="https://github.com/SlipperyyIce/DeepLearning-SpectrumSensing" target="_blank"><img src="./assets/git_icon.png" class="icon "></a>
            
          </span>
          
        </div>
        <img class="prj-img" src='./assets/DL_Cover.png' style="position: absolute; left: 400px;">
        
      </div>

      <div class="flex" style="width: 700px; justify-content: space-between;">
        <img class="prj-img" src='./assets/Blackjack_Cover.png' >
        <div style="text-align: right; position: relative; left: -100px;">
          <p class="aquamarine roboto">Featured Project</p>
          <p style="font-size: large; font-weight: bold; margin-top: -10px;">Blackjack</p>
          <div class="prj-overview roboto">A blackjack website I crafted from scratch, showcasing my  technical skills and expertise as a developer with a passion for creating immersive gaming experiences.</div>
          <p class="grey">Vue.js</p>
          <span>
            <a href="https://github.com/SlipperyyIce/blackjack" target="_blank"><img src="./assets/git_icon.png" class="icon "></a>
            <a href="https://slipperyyice.github.io/blackjack/" target="_blank"><img src="./assets/hyperlink_icon.png" class="icon2"></a>
          </span>          
        </div>
      </div>

      <div class="flex" style="width: 700px; justify-content: space-between;">
        <div>
          <p class="aquamarine roboto">Project</p>
          <p style="font-size: large; font-weight: bold; margin-top: -10px;">Topdown Shooter Game</p>
          <div class="prj-overview roboto" style="z-index: 1; position: relative;">A game that I made for fun to see what I could build in a 48 hour timeframe for windows, where the aim to surive as long as possible to get the highest score.</div>
          <p class="grey">Unreal Engine </p>
          <span>
            <a href="https://drive.google.com/file/d/1ul1SLk3j_DAZgh45coOdBps6bWz9aTHy/view?usp=share_link" target="_blank"><img src="./assets/windows_icon.png" class="icon "></a>
          </span>
          
        </div>
        <img class="prj-img" src='./assets/Shooter_Cover.png' style="position: absolute; left: 400px;">      
      </div>

      
      
    </div>
    <div class="small_section">
      <div class="text-white section1">
        <div class="about">
          <p id="contact" class="aquamarine roboto">03.&nbsp;</p>
          <p style="font-size: x-large; font-weight: bold;">Contact &nbsp;</p>
          <div style="width: 300px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
        </div>
        <div style="text-align: left; width: 450px;">
        <p class="white roboto">Have any questions or inquiries? Get in touch with me!</p>
        <p class="white roboto">Email: <span style="opacity: 100%!important;"><a class="aquamarine" href="mailto:example@example.com">btt.bajomo@gmail.com</a></span> </p>
        </div>
      </div>
    </div>
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
  margin-bottom: 120px;
}
.prj-img{
  width: 500px;
  height: 300px;
  filter: grayscale(1);
  outline: 1px dotted white;
}

.section{
  background-color: #000000;
  min-height: 720px;
  text-align: left;
}

.small_section{
  min-height: 420px!important;
}
.grey{
  color: #666666;
}

.prj-overview{
  padding: 20px;
  background-color: #202124;
  height: fit-content;
  width: 500px;
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
.icon{
  width: 35px; 
  height: 35px;
  margin-right: 10px;
}
.icon2{
  width: 27px; 
  height: 27px;
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