<template lang=pug>
  .Container
    .slide
     .title {{title}}
     .title2 {{title2}}
     .bottomr
     .w1 {{w1}}
     .w2 {{w2}}
     .w3 {{w3}}
     .lds-circle
     .image1
     .image2
     .image3
     .image4
     .image5
     .image6
     .image7
     .image8
     .p1
     .p2
     .p3
     .p4
     .p5
     .p6
     .p7
     .p8
     .w4 {{w4}}
     .w5 {{w5}}
     
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
      title: 'Mayumi Konno',
      w1: '- Art -',
      w2: ' 2020',
      w3: '2019',
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
     height: 2750px
     top: 80px
     left: 0px
     position: absolute
     background: #FEFEFF
   .slide
      position: absolute
      top: 150px
      left: 270px
      width: 1000px
      height: 510px
      margin: 20px auto
      background-size: over
      background-position: center
      -webkit-animation-name: 'loop'
      -webkit-animation-duration: 20s
      -webkit-animation-iteration-count: infinite
      @-webkit-keyframes "loop" 
          0% 
            background: url("../assets/a1.png") repeat
          25% 
            background: url("../assets/a2.png") repeat      
          50% 
            background: url("../assets/a3.png") repeat        
          75% 
            background: url("../assets/a4.png") repeat    
          100% 
            background: url("../assets/a5.png") repeat
   .title  
      position: absolute
      width: 900px
      height: 100px
      left: 50px
      top: -135px
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
      left: 102px
      top: -55px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367 
      opacity: 0.8
      letter-spacing: 4px
   .w1 //art
      position: absolute
      width: 150px
      height: 100px
      left: -200px
      top: 690px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 45px
      line-height: 39px
      color: #847367  
   .w2  //2020   
      position: absolute
      width: 100px
      height: 100px
      left: -185px
      top: 758px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 40px
      line-height: 39px
      color: #847367  
   .image1
      background-image: url("../assets/b1.png") 
      position: absolute
      width: 300px
      height: 300px
      left: -190px
      top: 805px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image2
      background-image: url("../assets/b2.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 160px
      top: 805px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image3
      background-image: url("../assets/b3.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 515px
      top: 805px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image4
      background-image: url("../assets/b4.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 870px
      top: 805px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image5
      background-image: url("../assets/b5.png") 
      position: absolute
      width: 300px
      height: 300px
      left: -190px
      top: 1155px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image6
      background-image: url("../assets/b6.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 160px
      top: 1155px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image7
      background-image: url("../assets/b7.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 515px
      top: 1155px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image8
      background-image: url("../assets/b8.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 870px
      top: 1155px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7 
   .w3 //2019
      position: absolute
      width: 100px
      height: 100px
      left: -180px
      top: 1550px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 40px
      line-height: 39px
      color: #847367 
   .p1
      background-image: url("../assets/c1.png") 
      position: absolute
      width: 300px
      height: 300px
      left: -190px
      top: 1605px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p2
      background-image: url("../assets/c2.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 160px
      top: 1605px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p3
      background-image: url("../assets/c3.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 515px
      top: 1605px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p4
      background-image: url("../assets/c4.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 870px
      top: 1605px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p5
      background-image: url("../assets/c5.png") 
      position: absolute
      width: 300px
      height: 300px
      left: -190px
      top: 1958px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p6
      background-image: url("../assets/c6.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 160px
      top: 1958px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p7
      background-image: url("../assets/c7.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 515px
      top: 1958px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .p8
      background-image: url("../assets/c8.png") 
      position: absolute
      width: 300px
      height: 300px
      left: 870px
      top: 1958px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .lds-circle //會轉的圓形
      position: absolute
      top: 2330px
      left: 450px
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
      left: 355px
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
      left: 520px
      top: 2349px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 35px
      line-height: 39px
      color: #847367  
   .bottomr //藍色方塊
      width: 350px
      height: 100px
      top: 2320px
      left: 316px
      position: absolute
      background: #A3C8FF
      opacity :0.2
      transition: 0.3s
      &:hover 
        opacity: 0.7
</style>