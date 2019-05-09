<template>
  <div class="contact">
    <div id="show1">
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
    </nav>
            <p>CONTACT US TODAY!</p>
            <h6>We will connect you faster that other connections</h6>
   </div>
    <div id="show2">
        <div id="form_input">
            <lable>Name:</lable>
            <input id="a" type="text" value="">
            <lable id="b">Email:</lable>
            <input id="c" type="text" value="">
            <lable id="d">Message:</lable>
            <input id="e" type="text" value="">
            <button></button>

        </div>
    
    </div>
  </div>
</template>

<script>
export default {
  name: 'contact',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#show1{
    position: absolute;
    width: 1440px;
    height: 342px;
    left: 0px;
    top: 0px;
    background: linear-gradient(180deg, rgba(0, 0, 0, 0.37) 0%, rgba(0, 0, 0, 0.37) 100%), url("../assets/contact.jpg");
}
#show2{
    position: absolute;
    width: 1440px;
    height: 742px;
    top: 53.62%;
    bottom: 17.68%;
    background: #F2F6FF;
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
   color: #000;
}

#form_input{
  position: absolute;
  width: 930px;
  height: 598px;
  left: 248px;
  top: 90px;
  background: #FFFFFF;
  border: 1px solid #888686;
  box-sizing: border-box;
  border-radius: 20px;
}
lable{
  position: absolute;
  width: 94px;
  height: 20px;
  left: 80px;
  top: 70px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  color: #000000;
}
#a{
  position: absolute;
  width: 825px;
  height: 54px;
  left: 80px;
  top: 109px;
  background: #FFFFFF;
  border: 1px solid #888686;
  box-sizing: border-box;
  border-radius: 10px;
}
#b{
  position: absolute;
  width: 94px;
  height: 20px;
  left: 80px;
  top: 182px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  color: #000000;
}
#c{
  position: absolute;
  width: 825px;
  height: 54px;
  left: 80px;
  top: 215px;
  background: #FFFFFF;
  border: 1px solid #888686;
  box-sizing: border-box;
  border-radius: 10px;
}
#d{
  position: absolute;
  width: 94px;
  height: 20px;
  left: 80px;
  top: 294px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  color: #000000;
}
#e{
  position: absolute;
  width: 825px;
  height: 218px;
  left: 80px;
  top: 324px;
  background: #FFFFFF;
  border: 1px solid #888686;
  box-sizing: border-box;
  border-radius: 10px;
}
button{
  position: absolute;
  width: 130px;
  height: 41px;
  left: 620px;
  top: 968px;
  background:#66DBB7;
  border-radius:4px;
}
p{
  position: absolute;
  width: 239px;
  height: 24px;
  left: 600px;
  top: 129px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  color: #FFFFFF;
}
h6{
  position: absolute;
  width: 256px;
  height: 28px;
  left: 592px;
  top: 222px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #FFFFFF;
}
</style>
