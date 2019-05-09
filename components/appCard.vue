<template>
  <div class="appCard">
        <h2>Lastest Properties</h2>
        <h6>view the latest property on the market. You are sure to see something good</h6>
     
    <span>
         <div>
        <div id= "show1"></div>
            <div  id="body">
                <h3>Outdoor Pato in Orlando</h3><br>
                <h4>Lorem Ipsum et loer ter the reyy</h4>
                <p>#100,000</P>
                <h5>Location: Orlando</h5>
            </div>
        </div>
    </span>
  
    <span>
     <div>
        <div id= "show2"></div>
            <div  id="body">
                <h3 id="a">Outdoor Pato in Orlando</h3><br>
                <h4 id="b">Lorem Ipsum et loer ter the reyy</h4>
                <p id="c">#100,000</P>
                <h5 id="d">Location: Orlando</h5>
            </div>
        </div>
    </span>

    <span>
     <div>
        <div id= "show3"></div>
          <div  id="body">
              <h3 id="e">Outdoor Pato in Orlando</h3><br>
              <h4 id="f">Lorem Ipsum et loer ter the reyy</h4>
              <p id="g">#100,000</P>
              <h5 id="h">Location: Orlando</h5>
          </div>
        </div>
    </span>
                <a>view all houses</a>
  </div>
</template>

<script>
export default {
  name: 'appCard'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.appCard{
    width: 1350px;
    height: 704px;
    left: -1px;
    top: 1574px;
    background: #F2F6FF;
}
#show1{
    position: absolute;
    width: 288px;
    height: 182px;
    left: 234px;
    top: 834px;
    background: url("../assets/appCard.jpg");
}
#show2{
    position: absolute;
    width: 288px;
    height: 182px;
    left: 586px;
    top: 834px;
    background: url("../assets/appCard.jpg");
}
#show3{
    position: absolute;
    width: 288px;
    height: 182px;
    left: 938px;
    top: 834px;
    background: url("../assets/appCard.jpg");
}
h3{
    position: absolute;
    width: 164px;
    height: 18px;
    left: 245px;
    top: 1028px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 16px;
    color: #000000;

}
h4{
    position: absolute;
    width: 210px;
    height: 16px;
    left: 246px;
    top: 1050px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #888686;
}
h5{
    position: absolute;
    width: 123px;
    height: 14px;
    left: 247px;
    top: 1144px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
#a{
  position: absolute;
    width: 164px;
    height: 18px;
    left: 597px;
    top: 1028px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
#b{
    position: absolute;
    width: 210px;
    height: 16px;
    left: 598px;
    top: 1050px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #888686;
}
#c{
    position: absolute;
    width: 193px;
    height: 32px;
    left: 557px;
    top: 1078px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 33px;
    color: #66DBB7;
}
#d{
    position: absolute;
    width: 123px;
    height: 14px;
    left: 599px;
    top: 1144px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
#e{
    position: absolute;
    width: 164px;
    height: 18px;
    left: 949px;
    top: 1028px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
#f{
    position: absolute;
    width: 210px;
    height: 16px;
    left: 950px;
    top: 1050px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #888686;
}
#g{
    position: absolute;
    width: 193px;
    height: 32px;
    left: 900px;
    top: 1078px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 33px;
    color: #66DBB7;
}
#h{
    position: absolute;
    width: 123px;
    height: 14px;
    left: 951px;
    top: 1144px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
p{
    position: absolute;
    width: 193px;
    height: 32px;
    left: 200px;
    top: 1078px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 33px;
    color: #66DBB7;
}
h2{
    position: absolute;
    width: 201px;
    height: 36px;
    left: 620px;
    top: 726px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 28px;
    color: #000000;
}
h6{
    position: absolute;
    width: 486px;
    height: 24px;
    left: 477px;
    top: 762px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
a{
    position: absolute;
    width: 102px;
    height: 20px;
    left: 661px;
    top: 1257px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #000000;
}
</style>
