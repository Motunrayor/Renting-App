<template>
<div class="body">
<header class="ourservices">
  <nav class="services">
    <div class="navigation__menu">
      <span class="link__wrapper">
        <router-link class="link" to="/">Homes</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/properties">Properties</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/admin">Admin</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/login">Login</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/signin">Signin</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/services">Services</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/about">About</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/contact">Contact</router-link>
      </span>
    </div>

    <div>
        <button class="navbar__button">
          Post a property
        </button>
    </div>
</nav>
      <h4>0UR SERVICES</h4>
      <p>Connecting house owners and tenants</P>
      <img src="../assets/home.png">
      <h6>We will connect you faster that other connections</h6>
      <button type="submit">View our properties</button>
</header>
    <div>
      <span>
            <div id= "show1"></div>
      </span>
  
      <span>
          <div id= "show2"></div>
          <img id="a" src="../assets/placeholder.png">
          <h4>Sale of household equipment</h4>
       </span>

        <span>
          <div id= "show3"></div>
        </span>
    </div>
    
</div>
</template>

<script>
export default {
  name: 'services',

 
};
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.body{
  position: absolute;
  height:1430px;
  left: -0.35%;
  right: 0.35%;
  top: 0%;
  bottom: 1.15%;
  background: #F2F6FF;
}
.ourservices{
  position: absolute;
  width: 1350px;
  height: 708px;
  left: 0px;
  top: 0px;
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.37) 0%, rgba(0, 0, 0, 0.37) 100%), url("../assets/ourservices.jpg");
}
.services {
    position: absolute;
    width: 1283px;
    margin: auto;
    left: 0px;
    top: 2px;
    padding: 1.8em;
    display: flex;
    justify-content: space-between;
}
 .navigation__menu {
   display: flex;
   align-content: center;
   justify-content: center;
   flex: 1;
}
 .link {
   color: #FFF;
   padding: 0.5 3em;
   text-decoration: none;
}
 .link__wrapper {
   padding: 0.5em 1em;
}
 .navbar__button {
   background: #66DBB7;
   border: none;
   padding: 0.65em 1em;
   border-radius: 5px;
   color: #ffffff;
}
h4{
  position: absolute;
  width: 161px;
  height: 24px;
  left: 639px;
  top: 80px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 28px;
  color: #000;
}
p{
  position: absolute;
  width: 316px;
  height: 34px;
  left: 562px;
  top: 225px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #FFFFFF;
}
h6{
  position: absolute;
  width: 256px;
  height: 28px;
  left: 587px;
  top: 489px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #FFFFFF;
}
h4{
  position: absolute;
  width: 320px;
  height: 48px;
  left: 523px;
  top: 1075px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  color: #FFFFFF;
}
button{
  position: absolute;
  width: 130px;
  height: 41px;
  left: 664px;
  top: 581px;
  background: #66DBB7;
  border-radius: 4px;
}
#show1{
  position: absolute;
  width: 400px;
  height: 400px;
  left: 53px;
  top: 837px;
  background: url("../assets/household.jpg")
}
#show2{
  position: absolute;
  width: 400px;
  height: 400px;
  left: 490px;
  top: 837px;
  background: #354A5F;
}
#show3{
  position: absolute;
  width: 400px;
  height: 400px;
  left: 920px;
  top: 837px;
  background: url("../assets/household.jpg")
}
img{
  position: absolute;
  left: 655px;
  right: 7.27%;
  top: 330px;
  bottom: 0%;
  background: #FFFFFF;
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.37) 0%, rgba(0, 0, 0, 0.37) 100%), url("../assets/ourservices.jpg");
}
#a{
  position: absolute;
  left: 630px;
  right: 28.33%;
  top: 970px;
  color: #000;
  background: url("../assets/placeholder.png");
}
</style>
