<script lang="ts">
import { defineComponent } from 'vue'

    export default defineComponent({

      props: {
        scroll: { required: true, type: Number },
        
      },

      methods: {
        play_onView(){
          var scrollY = window.scrollY;
          
          if(scrollY > this.scroll){
            this.$refs.main.classList.add('animate-in');
            this.$refs.txt.classList.add('show-txt');     
          }

        },

    },
    
    mounted() {     
        document.addEventListener("scroll", this.play_onView);
    }
    })
</script>

<template>
  
  <div class="rounded-container">
    <div class="white"  ref="main"></div>
    <div class="info-div" ref="txt">

      <a href="https://github.com/SlipperyyIce/VidaVodka"></a>
    </div>
  </div>
  
</template>

<style scoped>
.rounded-container {
  
  background: #000000;
  border: 1px solid #fff;
   
  width: 1000px;
  height: 150px; 
  
  margin-bottom: 30px;
  position: relative;
  left: 50%;
  transform: translate(-50%, 0%);
}
.white{
  height: 150px;
  background: #fff;
  width: 0px;

}
.animate-in{
  animation: example 1s forwards;
}
.show-txt{
  animation: reveal 1s 1s forwards;
}

.info-div{
  opacity: 0;
}

@keyframes example {
  from {width: 1000px;}
  to {width:  0px;}
}

@keyframes reveal {
  from {opacity: 0;}
  to {opacity: 100;}
}


</style>
