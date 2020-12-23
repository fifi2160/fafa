<template lang="pug">
  .newscontainer
   .Header
   .searchPage
    .search {{search}}
    .white {{white}}
    .image
    .image1
    .image2
    .image3
    .image4
    .websiteB
     .webTitle {{webTitle}}
     .webLine
     .webText1 {{webText1}}
     .webText2 {{webText2}}
     .webText3 {{webText3}}
     .webText4 {{webText4}}
     .webText5 {{webText5}}
     .webText6 {{webText6}}
     .webText7 {{webText7}}
     .webText8 {{webText8}}
     .webText9 {{webText9}}
     .webText10 {{webText10}}
     .webText11 {{webText11}}
     .webText12 {{webText12}}
     .webText13 {{webText13}}
     .webText14 {{webText14}}
     .webText15 {{webText15}}
     .webText16 {{webText16}}
     .webText17 {{webText17}}
     .webText18 {{webText18}}
     .webText19 {{webText19}}
     .webText20 {{webText20}}
     .webBottom {{webBottom}}
     .image5
     .webRight1
     .webRight2
     .webRight3
     .rightText {{rightText}}
     .rightText1 {{rightText1}}
     .image6
    .wText1 {{wText1}}
    .wText2 {{wText2}}
    .wText3 {{wText3}}
    .wText4 {{wText4}}
    .wText5 {{wText5}}
    .wText6 {{wText6}}
    .Group1
    .Group2
    .Group3
    .topText {{topText}}
    
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
       search:'search',
       white: 'Posts RSS  |  Facebook  |  Twitter  |  Mail me',
       wText1: '院學士班招生 - 科技藝術！',
       wText2: '歡迎你一起來開創清華科技藝術跨域DNA！',
       wText3: '藝設系招生 - 〝藝〞鳴驚人！',
       wText4: '歡迎你一起來把美感、創意帶入清華生活！',
       wText5: '音樂系招生 - 全方位音樂人！',
       wText6: '歡迎你一起在清華創造音樂心靈饗宴！',
       topText: 'HOME    |    關於學院    |    學院師資    |    學院規章    |    招生訊息    |    榮譽榜    |    活動花絮    |    藝院影音    |    藝術學報    |    聯絡資訊',
       webTitle: '-  近  期  活  動  -',
       webText1: '◆ 藝設系學生獲獎－109年林務局「國產材設計商品比賽」決選',
       webText2: '◆ 2021 年藝術學院教育發展基金',
       webText3: '◆【開放報名】2020國立清華大學藝術與設計學系研究生論文研討會',
       webText4: '◆ 清華大學藝設系研究生論文研討會 – 徵稿',
       webText5: '◆ 科技藝術策展人講座系列 – Metabolism at Contemporary (2020.04.07)',
       webText6: '◆ 清華藝術學報',
       webText7: '◆ 藝設系設計組-異質對話-（360展區1）',
       webText8: '◆ 華山烏梅劇場「Face to face」實驗性跨領域展演 × 四組劇場表演與一組互動裝置',
       webText9: '◆ 藝術學院-畢業典禮',
       webText10: '◆ 藝設系學生獲獎－第14屆福爾摩沙珠寶設計教育推廣競賽',
       webText11: '◆ 清明連假後防疫措施',
       webText12:'◆ 1月8日清華大學藝術大樓「春之廳」命名典禮',
       webText13: '◆ 勾勒《新竹•城市美術館》論壇',
       webText14: '◆ 奧斯卡獎得主Dr. Jos Stam – 我的學思歷程-電腦圖像30年-從開天闢地到奧斯卡獎的旅程',
       webText15: '◆ 國際跨領域學術論壇 – 意識、情感認知與體現互動藝術',
       webText16: '◆ 歡迎報名「跨國實驗室工作坊」：互動藝術中的沉浸式即興創作',
       webText17: '◆ 學士班陶亞倫主任與四位學生受邀參加「2019雅典數位藝術節」',
       webText18: '◆ 清華花園',
       webText19: '◆「三便士歌劇」清華登場 跨院學生共演擦火花',
       webText20: '◆ 跨系的藝術結晶---2019音樂系三便士歌劇',
       webBottom: '國立清華大學藝術學院   Email   Tel:+886-3-5715131  #78801    2020  Copyright ©',
       rightText: '學 院 相 關 網 站',
       rightText1: '訊息類別',
    }
  }
}
</script>

<style lang="sass">
   .newscontainer
     position: relative
     width: 1535px
     height: 2274px
     border: 1px solid #aaa
   .Header
     width: 1535px
     height: 90px
     top: 0px
     left: 0px
     position: absolute
     background: #DDE2E5
   .searchPage
    position: absolute
    width: 520px
    height: 44px
    left: 450px
    top: 24px
    background: #FFFFFF
   .search
    position: absolute
    width: 128px
    height: 72px
    left: 400px
    top: 8.5px
    font-family: Passion One
    font-style: normal
    font-weight: normal
    font-size: 24px
    line-height: 26px
    color: rgba(179, 111, 65, 0.8)
   .white
    position: absolute
    width: 500px
    height: 20px
    left: 580px
    top: 10px
    font-family: sans-serif
    font-style: normal
    font-weight: normal
    font-size: 20px
    line-height: 26px
    letter-spacing: 0.15em
    color: #FFFFFF
   .image
    background-image: url("../assets/aa.png")
    position: absolute
    width: 80px
    height: 80px
    left: -450px
    top: -19px
    background-size: cover
   .image1
    background-image: url("../assets/bb.png")
    position: absolute
    width: 350px
    height: 60px
    left: -373px
    top: -10px
    background-size: cover
   .image2
    background-image: url("../assets/cc.png")
    position: absolute
    width: 1350px
    height: 544px
    left: -356px
    top: 174px
    background-size: cover
   .image3
    background-image: url("../assets/dd.png")
    position: absolute
    width: 80px
    height: 130px
    left: 995px
    top: 380px
    background-size: cover
   .image4
    background-image: url("../assets/ee.png")
    position: absolute
    width: 350px
    height: 70px
    left: 143px
    top: 720px
    background-size: cover
   .websiteB
    position: absolute
    width: 1535px
    height: 1100px
    left: -450px
    top: 1150px
    background: #F1EAE2
   .Group1 //中
    position: absolute
    width: 450px
    height: 250px
    left: 95px
    top: 819px
    background: rgba(189, 107, 69, 0.3)
    border-radius: 15px
   .Group2 //左
    position: absolute
    width: 440px
    height: 250px
    left: -380px
    top: 819px
    background: rgba(189, 107, 69, 0.3)
    border-radius: 15px
   .Group3 //右
    position: absolute
    width: 440px
    height: 250px
    left: 580px
    top: 819px
    background: rgba(189, 107, 69, 0.3)
    border-radius: 15px
   .wText1
    position: absolute
    width: 380px
    height: 39px
    left: -345px
    top: 900px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 32px
    line-height: 39px
    color: #5B4130
   .wText2
    position: absolute
    width: 800px
    height: 60px
    left: -560px
    top: 950px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 19px
    line-height: 34px
    color: #5B4130
   .wText3
    position: absolute
    width: 411px
    height: 39px
    left: 120px
    top: 900px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 32px
    line-height: 39px
    color: #5B4130
   .wText4
    position: absolute
    width: 422px
    height: 67px
    left: 110px
    top: 950px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 19px
    line-height: 34px
    color: #5B4130
   .wText5
    position: absolute
    width: 411px
    height: 39px
    left: 600px
    top: 901px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 32px
    line-height: 39px
    color: #5B4130
   .wText6
    position: absolute
    width: 357px
    height: 58px
    left: 626px
    top: 950px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 19px
    line-height: 34px
    color: #5B4130
   .topText
    position: absolute
    width: 1500px
    height: 29px
    left: -425px
    top: 110px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 24px
    line-height: 29px
    color: #AD6F45
    letter-spacing: 0.2em
   .webTitle
    position: absolute
    width: 186px
    height: 34px
    left: 69px
    top: 50px
    font-family: Yrsa
    font-style: normal
    font-weight: bold
    font-size: 28px
    line-height: 34px
    color: #B26E41
   .webLine
     position: absolute
     width: 1174px
     height: 810px
     left: 66px
     top: 90px
     border: 1px solid #B26E41
   .webText1 //近期活動
    position: absolute
    width: 951px
    height: 1166px
    left: -132px
    top: 120px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
   .webText2
    position: absolute
    width: 951px
    height: 1166px
    left: -251px
    top: 182px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
   .webText3
    position: absolute
    width: 951px
    height: 1166px
    left: -111px
    top: 214px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
   .webText4
    position: absolute
    width: 951px
    height: 1166px
    left: -208px
    top: 247px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
   .webText5
    position: absolute
    width: 951px
    height: 1166px
    left: -107px
    top: 278px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
   .webText6
    position: absolute
    width: 951px
    height: 1166px
    left: -316px
    top: 153px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText7
    position: absolute
    width: 951px
    height: 1166px
    left: -220px
    top: 308px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText8
    position: absolute
    width: 951px
    height: 1166px
    left: -56px
    top: 340px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText9
    position: absolute
    width: 951px
    height: 1166px
    left: -296px
    top: 371px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText10
    position: absolute
    width: 951px
    height: 1166px
    left: -146px
    top: 402px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText11
    position: absolute
    width: 951px
    height: 1166px
    left: -289px
    top: 433px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText12
    position: absolute
    width: 951px
    height: 1166px
    left: -190px
    top: 463px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText13
    position: absolute
    width: 951px
    height: 1166px
    left: -250px
    top: 495px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText14
    position: absolute
    width: 951px
    height: 1166px
    left: -30px
    top: 526px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText15
    position: absolute
    width: 951px
    height: 1166px
    left: -154px
    top: 559px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText16
    position: absolute
    width: 951px
    height: 1166px
    left: -118px
    top: 593px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText17
    position: absolute
    width: 951px
    height: 1166px
    left: -118px
    top: 627px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText18
    position: absolute
    width: 951px
    height: 1166px
    left: -333px
    top: 662px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText19
    position: absolute
    width: 951px
    height: 1166px
    left: -189px
    top: 695px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webText20
    position: absolute
    width: 951px
    height: 1166px
    left: -207px
    top: 731px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 18px
    line-height: 22px
    color: #5B4130
  .webBottom
    position: absolute
    width: 771px
    height: 24px
    left: 388px
    top: 1060px
    font-family: Yeseva One
    font-style: normal
    font-weight: normal
    font-size: 17px
    line-height: 24px
    color: rgba(91, 65, 48, 0.8)
  .image5
    background-image: url("../assets/ff.png")
    position: absolute
    width: 180px
    height: 550px
    left: 1300px
    top: 80px
    background-size: cover
  .webRight1
    position: absolute
    width: 210px
    height: 36px
    left: 1285px
    top: 35px
    background: rgba(189, 107, 69, 0.59)
    border-radius: 21px
    transform: matrix(1, 0, 0, -1, 0, 0)
  .webRight2
    position: absolute
    width: 210px
    height: 36px
    left: 1285px
    top: 638px
    background: rgba(189, 107, 69, 0.59)
    border-radius: 21px
    transform: matrix(1, 0, 0, -1, 0, 0)
  .webRight3
    position: absolute
    width: 226px
    height: 310px
    left: 1277px
    top: 687px
    background: #FFFFFF
    border-radius: 20px
  .rightText
    position: absolute
    width: 200px
    height: 29px
    left: 1290px
    top: 40px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 24px
    line-height: 29px
    color: #FFF6F0
  .rightText1
    position: absolute
    width: 96px
    height: 29px
    left: 1344px
    top: 643px
    font-family: Yrsa
    font-style: normal
    font-weight: normal
    font-size: 24px
    line-height: 29px
    color: #FFF6F0
  .image6
    background-image: url("../assets/hh.png")
    position: absolute
    width: 155px
    height: 300px
    left: 1321px
    top: 688
    px
    background-size: cover
    
</style>
