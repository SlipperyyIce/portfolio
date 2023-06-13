<script setup lang="ts">
import { ref } from 'vue'
import { defineComponent } from 'vue'

</script>

<template>
  <div class="container mt-4">
    <div class="text-white text-start">
    <p class="aquamarine">Hi, my name is</p>
    <h1 class="roboto">Daniel Bajomo.</h1>
    <h1 class="roboto" style="opacity: 70%;">Computer Systems Engineering Graduate (2023)</h1>
    <p class="roboto" style="max-width: 540px;" >I am a conscientious and dedicated London-based computer science graduate with a passion for building exceptional frontend and backend systems. I recently graduated from <span class="aquamarine">Queen Mary</span> University of London and am actively seeking opportunities to contribute to the tech industry. I strive to create innovative solutions that exceed expectations.</p>  
    <p class="roboto" style="max-width: 540px;" >In addition to my studies, I have participated in several projects that have allowed me to delve into the world of machine learning. These experiences have equipped me with a solid foundation in fundamental concepts such as supervised and unsupervised deep learning and classification.</p>
    <p class="roboto" style="max-width: 540px;" >In this portfolio, I invite you to explore the projects I have undertaken, showcasing my skills, dedication.</p>
    <button type="button" class="btn btn-outline-success roboto" onclick="document.getElementById('contact').scrollIntoView({ behavior: 'smooth' })">Get in Touch  </button>
    </div>
  </div>
  <div class="container container-s">
    <div class="text-white text-start">
      <div class="about">
        <p id="aboutme" class="aquamarine roboto">01.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">About Me &nbsp;</p>
        <div style="width: 300px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
      </div>
      <div>
      <p class="white roboto" style="max-width: 540px;">I am a <span class="aquamarine" style="opacity: 100%!important;">highly motivated</span> computer science graduate with a strong foundation in programming and software engineering.</p>
      <p class="white roboto" style="max-width: 540px;"> I have experience in full-stack web development, database management, and system design. Passionate about technology, I actively seek out opportunities to stay updated with the latest advancements in the field. With excellent problem-solving skills and a drive for excellence, I am eager to contribute my expertise to a dynamic and innovative company. Let's create groundbreaking solutions together!</p>
      </div>
    </div>
  </div> 

  <div class="container text-white">
    <div class="about text-start">
        <p id="project" class="aquamarine roboto">02.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">Recent Projects&nbsp;</p>
        <div style="width: 250px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
      </div>
      
      <div class="card bg-black text-end position-relative">
        <div class="card-body position-absolute top-0 start-0 p-0">
          <img src="./assets/Expense_Cover.png" class="card-img-top prj-img position-relative start-0 " alt="...">       
        </div>
        <div class="position-absolute end-0">
            <p class="aquamarine roboto">Featured Project</p>
            <h5 class="card-title pb-2">Expenses App</h5>
            <div class="prj-info">
              <p class="card-text roboto bg-dark prj-overview">This project shows an expense application I made using Google's Firebase api. Allowing users to submit expenses which can then be approved or rejected by a line manager.</p>            
              <p class="grey">Firebase API&nbsp;&nbsp;  Next.js</p>
            
              <span>
                <a href="https://github.com/SlipperyyIce/fdm-expenses-app-main" target="_blank"><img src="./assets/git_icon.png" class="icon "></a>
                <a href="https://slipperyyice.github.io/fdm-expenses-app-main/" target="_blank"><img src="./assets/hyperlink_icon.png" class="icon2"></a>
              </span> 
            </div>             
        </div>        
      </div> 
      
      <div class="card bg-black text-start position-relative">
        <div class="card-body position-absolute top-0 end-0 p-0">
          
          <img src='./assets/DL_Cover.png' class="card-img-top prj-img position-relative end-0 " alt="...">       
        </div>
        <div class="position-absolute start-0">
            <p class="aquamarine roboto">Featured Project</p>
            <h5 class="card-title pb-2">DL Classification</h5>
            <div class="prj-info">
              <p class="card-text roboto bg-dark prj-overview">MATLAB code for the deep learning model I trained for my final year project to classiy different signals.</p>
              
              <p class="grey">MATLAB</p>
              
              <span>
                <a href="https://github.com/SlipperyyIce/DeepLearning-SpectrumSensing" target="_blank"><img src="./assets/git_icon.png" class="icon "></a>
              </span> 
            </div>             
        </div>        
      </div>

      <div class="card bg-black text-end position-relative">
        <div class="card-body position-absolute top-0 start-0 p-0">
          <img class="card-img-top prj-img position-relative start-0 " src='./assets/Blackjack_Cover.png' >      
        </div>
        <div class="position-absolute end-0">
            <p class="aquamarine roboto">Featured Project</p>
            <h5 class="card-title pb-2">Blackjack</h5>
            <div class="prj-info">
              <p class="card-text roboto bg-dark prj-overview">A blackjack website I crafted from scratch, showcasing my  technical skills and expertise as a developer with a passion for creating immersive gaming experiences.</p>
              
              <p class="grey">Vue.js</p>
              
              <span>
                <a href="https://github.com/SlipperyyIce/blackjack" target="_blank"><img src="./assets/git_icon.png" class="icon "></a>
                <a href="https://slipperyyice.github.io/blackjack/" target="_blank"><img src="./assets/hyperlink_icon.png" class="icon2"></a>
              </span>   
            </div>           
        </div>        
      </div> 

      <div class="card bg-black text-start position-relative">
        <div class="card-body position-absolute top-0 end-0 p-0">
          
          <img src='./assets/Shooter_Cover.png'  class="card-img-top prj-img position-relative end-0 " alt="...">       
        </div>
        <div class="position-absolute start-0">
            <p class="aquamarine roboto">Featured Project</p>
            <h5 class="card-title pb-2">Topdown Shooter Game</h5>
            <div class="prj-info">
              <p class="card-text roboto bg-dark prj-overview">A game that I made for fun to see what I could build in a 48 hour timeframe for windows, where the aim to surive as long as possible to get the highest score.</p>         
              <p class="grey">Unreal Engine </p>
              
              <span>
                <a href="https://drive.google.com/file/d/1ul1SLk3j_DAZgh45coOdBps6bWz9aTHy/view?usp=share_link" target="_blank"><img src="./assets/windows_icon.png" class="icon "></a>
              </span>  
            </div>            
        </div>        
      </div>
  </div>
  <div class="container container-s text-white">
    <div class="about text-start">
        <p id="contact" class="aquamarine roboto">02.&nbsp;</p>
        <p style="font-size: x-large; font-weight: bold;">Contact &nbsp;</p>
        <div style="width: 250px; border: 1px solid white; margin-bottom: 1rem; opacity: 40%;"></div>
    </div>
    <div style="text-align: left; max-width: 450px;">
        <p class="white roboto">Have any questions or inquiries? Get in touch with me!</p>
        <p class="white roboto">Email: <span style="opacity: 100%!important;"><a class="aquamarine" href="mailto:btt.bajomo@gmail.com">btt.bajomo@gmail.com</a></span> </p>
        <button type="button" class="btn btn-outline-success roboto" @click="downloadPDF">Download CV </button>
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
          //this.$refs.test.style.transform = "translateX(" + clamped_x + "px)";

        },
        downloadPDF() {
          var fileUrl = 'CV.pdf';
          var link = document.createElement('a');
          link.href = fileUrl;
          link.download = 'CV.pdf';
          link.click();
        },

    },
    
    mounted() {     
        document.addEventListener("scroll", this.horizontal_parrallax);
    }
    
});
</script>

<style scoped>
@media (max-width: 765px) {
  .prj-img{
    margin-top: 80px;
  }
  .prj-info{
    margin-top: 285px;
  }
  .card{
    
    margin-bottom: 260px;
  }
}
.prj-img{
  max-width: 500px;
  max-height: 300px;
  filter: grayscale(1);
  outline: 1px dotted white;
  padding: 0;
}

.card{
  min-height: 400px;
  padding: 0;
}
.container{
  max-width: 760px;
  min-height: 580px;
}

.container-s{
  max-width: 760px;
  min-height: 400px;
}

.grey{
  color: #666666;
}

.prj-overview{
  padding: 20px;
  background-color: #202124;
  height: fit-content;
  max-width: 500px;
}
.about{
  display: flex;
  padding-top: 40px;
  align-items: center;
}
.aquamarine{
  color: aquamarine;
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

</style>