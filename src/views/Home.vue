
<template lang="pug">
   .container
     .Header
      .image
      .Backcontain
      .image1
      .image2
      .image3
      .image4
      .image5
      .image6
      .image7
      .image8
      .image9
      .circle2
      .circle3
      .circle4
      .circle5
      .circle6
      .circle7
      .circle8
      .R1
      .R2
      .R3
      .R4
      .R5
      .R6
      .R7
      .R8
      .webText1 {{webText1}}
      .webText2 {{webText2}}
      .webText3 {{webText3}}
      .webText4 {{webText4}}
      .webText5 {{webText5}}
      .webText6 {{webText6}}
      .webText7 {{webText7}}
      .webText8 {{webText8}}
      .wText1 {{wText1}}
      .wText2 {{wText2}}
      .wText3 {{wText3}}
      .wText4 {{wText4}}
      .wText5 {{wText5}}
      .wText6 {{wText6}}
      .wText7 {{wText7}}
      .wText8 {{wText8}}
      .header
      .circlee
      .bottom
      .head1
      .head2
      .head3
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
       webText1: 'Mayumi Konno',
       webText2: 'Miyoshi',
       webText3: 'Nanaco Yashiro',
       webText4: 'Nutoguran',
       webText5: 'Little Thunder',
       webText6: 'Miho Hirano',
       webText7: 'Yogisya',
       webText8: 'Pegacon',
       wText1: '1987 | Japan | Oil Painting',
       wText2: '1992 | Japan | Illustration',
       wText3: '1990 | Japan | Illustration',
       wText4: '1998 | Japan | Illustration',
       wText5: '1984 | HongKong | Illustration',
       wText6: '1981 | Japan | Oil Painting',
       wText7: '1986 | Japan | Illustration',
       wText8: '1990 | Korea | Illustration',
      }
  }
}
    </script>

<style lang="sass">
   .container //粉紅背景
     width: 1518px
     height: 2990px
     top: 80px
     left: 0px
     position: absolute
     background: #F9DDD1
   .Header //上面長方
     width: 1518px
     height: 80px
     top: 0px
     left: 0px
     position: absolute
     background: #FFFBF1
   .head1
     background-image: url("../assets/home1.png")
     position: absolute
     width: 80px
     height: 80px
     left: 0px
     top: 0px
     background-size: cover
   .head2
     background-image: url("../assets/home2.png")
     position: absolute
     width: 510px
     height: 70px
     left: 900px
     top: 5px
     background-size: cover
   .head3
     background-image: url("../assets/home3.png")
     position: absolute
     width: 80px
     height: 78px
     left: 1430px
     top: 2px
     background-size: cover
   .bottom //最下面米黃長方
     width: 1518px
     height: 100px
     top: 2890px
     left: 0px
     position: absolute
     background: #FFFBF1
   .image //主圖
    background-image: url("../assets/aaa.jpg")
    position: absolute
    width: 830px
    height: 900px
    left: 375px
    top: 150px
    background-size: cover
    overflow: hidden
    transition: all 1s ease-out
    transform: scale(1, 1)
    &:hover
        transform: scale(1.2, 1.2)
   .Backcontain //米黃面積
    width: 1518px
    height: 1500px
    top: 1090px
    left: 0px
    position: absolute
    background: #FFFBF1
   .image1 //鋸齒
    background-image: url("../assets/ccc.png")
    position: absolute
    width: 1518px
    height: 500px
    left: 0px
    top: 2300px
    background-size: cover
   .image2  //绀野
    background-image: url("../assets/vvv.png")
    position: absolute
    width: 300px
    height: 300px
    left: 50px
    top: 1130px
    background-size: cover
   .image3 //門
    background-image: url("../assets/ggg.png")
    position: absolute
    width: 300px
    height: 300px
    left: 790px
    top: 1134px
    background-size: cover
   .image4 //箕芳
    background-image: url("../assets/kkk.png")
    position: absolute
    width: 300px
    height: 300px
    left: 50px
    top: 1480px
    background-size: cover
   .image5 //花
    background-image: url("../assets/kk.png")
    position: absolute
    width: 300px
    height: 300px
    left: 794px
    top: 1487px
    background-size: cover
   .image6 //夜
    background-image: url("../assets/pp.png")
    position: absolute
    width: 300px
    height: 300px
    left: 803px
    top: 1847px
    background-size: cover
   .image7 //美式
    background-image: url("../assets/oo.png") 
    position: absolute
    width: 300px
    height: 300px
    left: 50px
    top: 1845px
    background-size: cover
   .image8 //韓國
    background-image: url("../assets/uuu.png") 
    position: absolute
    width: 300px
    height: 300px
    left: 805px
    top: 2205px
    background-size: cover
   .image9 //圖形
    background-image: url("../assets/vv.png") 
    position: absolute
    width: 300px
    height: 300px
    left: 53px
    top: 2210px
    background-size: cover
   .circle2
    background: #B0F6FF
    position: absolute
    border-radius: 50%
    width: 200px
    height: 200px
    left: 147px
    top: 932px
    opacity :0.5
    transition: all ls
    &:hover
       width: 290px
       height: 290px
       background: #FFFBF1
   .circle3
    background: #E46B50
    position: absolute
    border-radius: 50%
    width: 300px
    height: 300px
    left: 147px
    top: 302px
    opacity :0.5
    transition: all ls
    &:hover
       width: 350px
       height: 350px
       background: #FFFBF1
   .circle4 //黃
    background: #EFBF65
    position: absolute
    border-radius: 50%
    width: 100px
    height: 100px
    left: 347px
    top: 750px
    opacity :0.5
    transition: all ls
    &:hover
       width: 150px
       height: 150px
       background: #FFFBF1
   .circle5 //紫
    background: #ECB4D9
    position: absolute
    border-radius: 50%
    width: 230px
    height: 230px
    left: 1177px
    top: 132px
    opacity :0.5
    transition: all ls
    &:hover
       width: 290px
       height: 290px
       background: #FFFBF1
   .circle6 //螢光綠
    background: #98FFCE
    position: absolute
    border-radius: 50%
    width: 150px
    height: 150px
    left: 1290px
    top: 502px
    opacity :0.5
    transition: all ls linear
    &:hover
       width: 200px
       height: 200px
       background: #FFFBF1
   .circle7 //左半
    background-image: url("../assets/ci.png") 
    position: absolute
    width: 150px
    height: 300px
    left: 0px
    top: 690px
    background-size: cover
    opacity :0.5
   .circle8 //藍
    background: #98DAFF
    position: absolute
    border-radius: 50%
    width: 120px
    height: 120px
    left: 70px
    top: 125px
    opacity :0.5
    transition: all ls linear
    &:hover
       width: 140px
       height: 140px
       background: #FFFBF1
   .R1
     width: 210px
     height: 50px
     top: 1210px
     left: 390px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R2
     width: 210px
     height: 50px
     top: 1555px
     left: 390px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R3
     width: 210px
     height: 50px
     top: 1935px
     left: 390px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R4
     width: 210px
     height: 50px
     top: 2305px
     left: 390px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R5
     width: 210px
     height: 50px
     top: 1210px
     left: 1135px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R6
     width: 210px
     height: 50px
     top: 1555px
     left: 1135px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R7
     width: 210px
     height: 50px
     top: 1935px
     left: 1135px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .R8
     width: 210px
     height: 50px
     top: 2305px
     left: 1135px
     position: absolute
     background: #F9DDD1
     overflow: hidden
     transition: all 1s ease-out
     transform: scale(1, 1)
     &:hover
        transform: scale(1.2, 1.2)
   .webText1
      position: absolute
      width: 198px
      height: 180px
      left: 398px
      top: 1215px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText2
      position: absolute
      width: 100px
      height: 100px
      left: 442px
      top: 1559px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText3
      position: absolute
      width: 197px
      height: 100px
      left: 398px
      top: 1940px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText4
      position: absolute
      width: 100px
      height: 100px
      left: 443px
      top: 2309px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText5
      position: absolute
      width: 197px
      height: 100px
      left: 1143px
      top: 1215px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText6
      position: absolute
      width: 157px
      height: 100px
      left: 1160px
      top: 1560px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText7
      position: absolute
      width: 100px
      height: 100px
      left: 1185px
      top: 1941px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .webText8
      position: absolute
      width: 100px
      height: 100px
      left: 1187px
      top: 2310px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 25px
      line-height: 39px
      color: #847367
   .header
     width: 1518px
     height: 80px
     top: 0px
     left: 0px
     position: absolute
     background: #FFFBF1
   .circlee
      position: absolute
      width: 450px
      height: 450px
      opacity: 0.3
      top: 750px
      left: 1049px
      margin: 20px
      shape-outside: circle(50% at 30%)
      clip-path: circle(45.4% at 82% 48%)
      background: #48D132
      transition: all ls
      &:hover
        width: 450px
        height: 450px
        background: #FFFBF1
   .wText1 
      position: absolute
      width: 250px
      height: 100px
      top: 1275px
      left: 370px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText2 
      position: absolute
      width: 250px
      height: 100px
      top: 1621px
      left: 370px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText3 
      position: absolute
      width: 250px
      height: 100px
      top: 2005px
      left: 370px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText4 
      position: absolute
      width: 250px
      height: 100px
      top: 2370px
      left: 370px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText5 
      position: absolute
      width: 250px
      height: 100px
      top: 1275px
      left: 1136px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText6 
      position: absolute
      width: 250px
      height: 100px
      top: 1625px
      left: 1120px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText7 
      position: absolute
      width: 250px
      height: 100px
      top: 2005px
      left: 1120px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
   .wText8
      position: absolute
      width: 250px
      height: 100px
      top: 2370px
      left: 1120px
      font-style: normal
      font-weight: normal
      font-family: Yrsa
      font-size: 20px
      line-height: 39px
      color: #847367
</style>