<template lang=pug>
  .Container
    .slide
     .title {{title}}
     .title2 {{title2}}
     .middle
     .bottommm
     .lds-circle
     .tree1
     .tree2
     .w4 {{w4}}
     .w5 {{w5}}  
     .n1
     .n2
     .v1
     .v2
     .v3
     .v4
     .v5
     .v6
     .v7
     .v8
    
     
</template>  

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  },
  data(){
    return{
      title: 'Miho Hirano',
      w4: 'Read',
      w5: 'More',
      title2: 'Home      |      News      |      Shop     |       About    |        Contact ',
      }
  }
}
    </script>

<style lang="sass">
   .Container
     width: 1518px
     height: 2650px
     top: 80px
     left: 0px
     position: absolute
     background: #99B0D1
   .middle
     background-image: url("../assets/mid.png") 
     position: absolute
     width: 1518px
     height: 500px
     left: -349px
     top: 1800px
     background-size: cover 
     opacity:0.7
     transition: 0.3s
     &:hover 
        opacity: 0.5
   .v1
     background-image: url("../assets/v6.png") 
     position: absolute
     width: 300px
     height: 300px
     left: -190px
     top: 855px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
   .v2
     background-image: url("../assets/v2.png") 
     position: absolute
     width: 300px
     height: 300px
     left: 160px
     top: 855px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
   .v3
      background-image: url("../assets/v5.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 515px
      top: 855px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .v4
      background-image: url("../assets/v4.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 870px
      top: 855px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .v5
      background-image: url("../assets/v1.png") 
      position: absolute
      width: 300px
      height: 300px
      left: -349px
      top: 1355px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .v6
      background-image: url("../assets/v3.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 3px
      top: 1355px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .v7
      background-image: url("../assets/v7.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 355px
      top: 1355px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .v8
      background-image: url("../assets/v8.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 707px
      top: 1355px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .tree1
     background-image: url("../assets/back1.png") 
     position: absolute
     width: 500px
     height: 800px
     left: 668px
     top: 1100px
     background-size: cover
     opacity:0.7
   .tree2
     background-image: url("../assets/back2.png") 
     position: absolute
     width: 550px
     height: 800px
     left: -349px
     top: 500px
     background-size: cover
     opacity: 0.7
   .n1
     background-image: url("../assets/n1.png") 
     position: absolute
     width: 300px
     height: 700px
     left: -349px
     top: 0px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
   .n2
     background-image: url("../assets/n2.png") 
     position: absolute
     width: 300px
     height: 700px
     left: 868px
     top: 0px
     background-size: cover 
     transition: 0.3s
     &:hover 
        opacity: 0.7
   .slide
      position: absolute
      top: 150px
      left: 350px
      width: 800px
      height: 495px
      margin: 20px auto
      background-size: over
      background-position: center
      -webkit-animation-name: 'loop'
      -webkit-animation-duration: 20s
      -webkit-animation-iteration-count: infinite
      @-webkit-keyframes "loop" 
          0% 
            background: url("../assets/ss2.png") repeat
          25% 
            background: url("../assets/ss4.png") repeat      
          50% 
            background: url("../assets/ss3.png") repeat        
          75% 
            background: url("../assets/s5.png") repeat    
          100% 
            background: url("../assets/ss1.png") repeat
   .title  
      position: absolute
      width: 900px
      height: 100px
      left: -50px
      top: -115px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 80px
      line-height: 39px
      color: #847367   
   .title2
      position: absolute
      width: 800px
      height: 100px
      left: 12px
      top: -55px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367 
      opacity: 0.8
      letter-spacing: 4px
   .lds-circle //會轉的圓形
      position: absolute
      top: 2330px
      left: 390px
      display: inline-block
      transform: translateZ(1px)
      display: inline-block
      width: 64px
      height: 64px
      margin: 8px
      border-radius: 50%
      background: #fdd
      animation: lds-circle 2.4s cubic-bezier(0, 0.2, 0.8, 1) infinite
      @keyframes lds-circle
          0%,100% 
              animation-timing-function: cubic-bezier(0.5, 0, 1, 0.5)
          0% 
              transform: rotateY(0deg)
          50% 
              transform: rotateY(1800deg)
              animation-timing-function: cubic-bezier(0, 0.5, 0.5, 1)
          100% 
              transform: rotateY(3600deg)
   .w4 //read
      position: absolute
      width: 100px
      height: 100px
      left: 285px
      top: 2350px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 35px
      line-height: 39px
      color: #847367  
   .w5 //more
      position: absolute
      width: 100px
      height: 100px
      left: 470px
      top: 2349px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 35px
      line-height: 39px
      color: #847367  
   .bottommm //藍色方塊
      width: 350px
      height: 100px
      top: 2320px
      left: 256px
      position: absolute
      background: #FFE1E1
      opacity :0.2
      transition: 0.3s
      &:hover 
        opacity: 0.7
  

</style>