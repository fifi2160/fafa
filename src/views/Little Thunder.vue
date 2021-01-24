<template lang=pug>
  .Container2
   .title2 {{title2}}
    .lt1
    .titlebackground
    .word1 {{word1}}
    .heart
    .round1
    .round2
    .round3
    .round4
    .w1 {{w1}}
    .w2 {{w2}}
    .w3 {{w3}}
    .w4 {{w4}}
    .w5 {{w5}}
    .w6 {{w6}}
    .lt2
    .lt3
    .lt4
    .lt5
    .lt6
    .lt7
    .lt8
    .bottomm
    .w7 {{w7}}
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
      title2: 'Little Thunder',
      word1: 'Little    Thunder',
      w1: 'News',
      w2: 'Shop',
      w3: 'About',
      w4: 'Contact',
      w5: '◆ Menu ◆',
      w6: '◆ Art Work ◆',
      w7: ' Read  More ',
      }
  }
}
    </script>

<style lang="sass">
  .Container2
     width: 1518px
     height: 2450px
     top: 80px
     left: 0px
     position: absolute
     background: #FFF8D2
  .title2
     position: absolute
     width: 900px
     height: 100px
     left: 300px
     top: 70px
     font-style: normal
     font-weight: normal
     font-size: 80px
     line-height: 39px
     color: #4A3F34  
  .round1 //藍
     background: #B0F6FF
     position: absolute
     border-radius: 50%
     width: 200px
     height: 200px
     left: -150px
     top: 860px
     transition: all ls
     &:hover
       width: 200px
       height: 200px
       background: #FF8070
  .round2 //綠
     background: #95FDB2
     position: absolute
     border-radius: 50%
     width: 200px
     height: 200px
     left: 200px
     top: 860px
     transition: all ls
     &:hover
       width: 200px
       height: 200px
       background: #FF8070
  .round3 //黃
     background: #FFEA7A
     position: absolute
     border-radius: 50%
     width: 200px
     height: 200px
     left: 550px
     top: 860px
     transition: all ls
     &:hover
       width: 200px
       height: 200px
       background: #FF8070
  .round4 //橘
     background: #FFC977
     position: absolute
     border-radius: 50%
     width: 200px
     height: 200px
     left: 900px
     top: 860px
     transition: all ls
     &:hover
       width: 200px
       height: 200px
       background: #FF8070
  .word1
     position: absolute
     width: 900px
     height: 100px
     left: -10px
     top: -11px
     font-style: normal
     font-weight: bold
     font-size: 45px
     line-height: 39px
     color: #705D4F
     letter-spacing: 10px
  .lt1
     background-image: url("../assets/lt1.jpg") 
     position: absolute
     width: 1518px
     height: 800px
     left: -300px
     top: -70px
     background-size: cover
  .lt2
     background-image: url("../assets/lt2.jpg") 
     position: absolute
     width: 500px
     height: 500px
     left: -250px
     top: 1230px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .lt3
     background-image: url("../assets/lt3.jpg") 
     position: absolute
     width: 250px
     height: 250px
     left: 262px
     top: 1230px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .lt4
     background-image: url("../assets/lt4.jpg") 
     position: absolute
     width: 380px
     height: 580px
     left: 790px
     top: 1230px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .lt5
     background-image: url("../assets/lt7.jpg") 
     position: absolute
     width: 250px
     height: 250px
     left: 525px
     top: 1230px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .lt6
     background-image: url("../assets/lt5.jpg") 
     position: absolute
     width: 510px
     height: 580px
     left: 264px
     top: 1495px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .lt7
     background-image: url("../assets/lt10.jpg") 
     position: absolute
     width: 380px
     height: 250px
     left: 790px
     top: 1825px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .lt8
     background-image: url("../assets/lt8.jpg") 
     position: absolute
     width: 500px
     height: 330px
     left: -250px
     top: 1745px
     background-size: cover
     transition: 0.3s
     &:hover 
        opacity: 0.7
  .titlebackground
     width: 600px
     height: 100px
     top: -45px
     left: 170px
     position: absolute
     background: #F9DDD1
     opacity: 0.85
     border-radius:30px
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
  .w1
     position: absolute
     width: 900px
     height: 100px
     left: -495px
     top: 942px
     font-style: normal
     font-weight: bold
     font-size: 45px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px
  .w2
     position: absolute
     width: 900px
     height: 100px
     left: -150px
     top: 942px
     font-style: normal
     font-weight: bold
     font-size: 45px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px 
  .w3
     position: absolute
     width: 900px
     height: 100px
     left: 202px
     top: 942px
     font-style: normal
     font-weight: bold
     font-size: 45px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px 
  .w4
     position: absolute
     width: 900px
     height: 100px
     left: 550px
     top: 942px
     font-style: normal
     font-weight: bold
     font-size: 37px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px 
  .w5 //menu
     position: absolute
     width: 900px
     height: 100px
     left: 7px
     top: 791px
     font-style: normal
     font-weight: bold
     font-size: 37px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px 
  .w6 //art
     position: absolute
     width: 900px
     height: 100px
     left: 10px
     top: 1142px
     font-style: normal
     font-weight: bold
     font-size: 37px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px 
  .w7
     position: absolute
     width: 900px
     height: 100px
     left: 13px
     top: 2182px
     font-style: normal
     font-weight: bold
     font-size: 37px
     line-height: 39px
     color: #705D4F
     letter-spacing: 3px 
  .heart
     display: inline-block
     position: relative
     width: 80px
     height: 80px
     transform: rotate(45deg)
     transform-origin: 40px 40px
     top: -3px
     left: 700px
     position: absolute
     width: 32px
     height: 32px
     background: #FFF1A8
     animation: lds-heart 1.2s infinite cubic-bezier(0.215, 0.61, 0.355, 1)
     &:after 
        content: " "
        position: absolute
        display: block
        width: 32px
        height: 32px
        background: #FFF1A8
     &:before 
        content: " "
        position: absolute
        display: block
        width: 32px
        height: 32px
        background: #FFF1A8
        left: -24px
        border-radius: 50% 0 0 50%
     &:after 
        top: -24px
        border-radius: 50% 50% 0 0
     @keyframes lds-heart 
        0% 
          transform: scale(0.95)
        5% 
          transform: scale(1.1)
        39% 
          transform: scale(0.85)
        45% 
          transform: scale(1)
        60% 
          transform: scale(0.95)
        100% 
          transform: scale(0.9)
  .bottomm //底部方塊
    width: 350px
    height: 100px
    top: 2150px
    left: 288px
    position: absolute
    background: #FF8070
    opacity :0.89
    border-radius:20px
    transition: 0.3s
    &:hover 
      opacity: 0.7  
</style>