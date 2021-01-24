<template lang=pug>
  .Container
    .slide
     .title {{title}}
     .title2 {{title2}}
     .f1
     .f2
     .f3
     .f4
     .f5
     .cheaper1 {{cheaper1}}
     .cheaper2 {{cheaper2}}
     .cheaper3 {{cheaper3}}
     .cheaper4 {{cheaper4}}
     .bottomr
     .w1 {{w1}}
     .lds-circle
     .midheader
     .image1
     .image2
     .image3
     .image4
     .image5
     .image6
     .w4 {{w4}}
     .w5 {{w5}}
     .image7
    
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
      title: 'Yogisya',
      w1: '- Art  Work -',
      w4: 'Read',
      w5: 'More',
      title2: 'Home      |      News      |      Shop     |       About    |        Contact ',
      cheaper1: ' { Cheaper1 } ',
      cheaper2: ' { Cheaper2 } ',
      cheaper3: ' { Cheaper3 } ',
      cheaper4: ' { Cheaper4 } ',
      }
  }
}
    </script>

<style lang="sass">
   .Container
     width: 1518px
     height: 3250px
     top: 80px
     left: 0px
     position: absolute
     background: #E9D3D3
   .f1
      background-image: url("../assets/f1.png") 
      position: absolute
      width: 550px
      height: 550px
      left: 300px
      top: 930px
      background-size: cover
   .f2
      background-image: url("../assets/f3.png") 
      position: absolute
      width: 550px
      height: 550px
      left: 790px
      top: 1000px
      background-size: cover
   .f3
      background-image: url("../assets/f5.png") 
      position: absolute
      width: 360px
      height: 360px
      left: 420px
      top: 1430px
      background-size: cover
   .f4
      background-image: url("../assets/f4.png") 
      position: absolute
      width: 400px
      height: 410px
      left: 770px
      top: 1430px
      background-size: cover
   .f5
      background-image: url("../assets/f6.png") 
      position: absolute
      width: 200px
      height: 260px
      left: 1000px
      top: 900px
      background-size: cover
   .image7
      background-image: url("../assets/dd1.png") 
      position: absolute
      width: 650px
      height: 380px
      left: 423px
      top: 1215px
      background-size: cover
   .midheader
      background-image: url("../assets/yo8.png") 
      position: absolute
      width: 1518px
      height: 100px
      left: -8px
      top: 1835px
      background-size: cover
   .slide
      position: absolute
      top: 150px
      left: 8px
      width: 1500px
      height: 810px
      margin: 20px auto
      background-size: over
      background-position: center
      -webkit-animation-name: 'loop'
      -webkit-animation-duration: 20s
      -webkit-animation-iteration-count: infinite
      @-webkit-keyframes "loop" 
          0% 
            background: url("../assets/yo1.png") repeat
          25% 
            background: url("../assets/yo2.png") repeat      
          50% 
            background: url("../assets/yo3.png") repeat        
          75% 
            background: url("../assets/yo4.png") repeat    
          100% 
            background: url("../assets/yo5.png") repeat
   .title  
      position: absolute
      width: 900px
      height: 100px
      left: 290px
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
      left: 362px
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
      width: 350px
      height: 100px
      left: -45px
      top: 900px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 40px
      line-height: 39px
      color: #847367  
      opacity: 0.95
   .image1
      background-image: url("../assets/e2.png") 
      position: absolute
      width: 400px
      height: 850px
      left: 8px
      top: 955px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .image2
      background-image: url("../assets/e1.png") 
      position: absolute
      width: 400px
      height: 850px
      left: 1090px
      top: 955px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7 
   .image3 //底下圖片
      background-image: url("../assets/e3.png") 
      position: absolute
      width: 565px
      height: 400px
      left: 160px
      top: 2005px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7 
   .image4
      background-image: url("../assets/e4.png") 
      position: absolute
      width: 565px
      height: 400px
      left: 800px
      top: 2005px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7 
   .image5
      background-image: url("../assets/e5.png") 
      position: absolute
      width: 565px
      height: 400px
      left: 160px
      top: 2485px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7 
   .image6
      background-image: url("../assets/e7.png") 
      position: absolute
      width: 565px
      height: 400px
      left: 800px
      top: 2485px
      background-size: cover
      transition: 0.3s
      &:hover 
        opacity: 0.7 
   .lds-circle //會轉的圓形
      position: absolute
      top: 2930px
      left: 726px
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
      left: 639px
      top: 2950px
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
      left: 796px
      top: 2950px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 35px
      line-height: 39px
      color: #847367  
   .bottomr //藍色方塊
      width: 350px
      height: 100px
      top: 2920px
      left: 598px
      position: absolute
      background: #DD8C8C
      opacity :0.2
      transition: 0.3s
      &:hover 
        opacity: 0.7
   .cheaper1
      position: absolute
      width: 300px
      height: 100px
      left: 294px
      top: 1960px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 26px
      line-height: 39px
      color: #AF9A87
   .cheaper2
      position: absolute
      width: 300px
      height: 100px
      left: 934px
      top: 1960px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 26px
      line-height: 39px
      color: #AF9A87
   .cheaper3
      position: absolute
      width: 300px
      height: 100px
      left: 294px
      top: 2438px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 26px
      line-height: 39px
      color: #AF9A87
   .cheaper4
      position: absolute
      width: 300px
      height: 100px
      left: 934px
      top: 2438px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 26px
      line-height: 39px
      color: #AF9A87
</style>