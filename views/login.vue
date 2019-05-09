<template>
<header>
    <nav class="login">
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
        <div id="body">
            <label id="name">Name:</label>
            <input id="a" type="text" value="">
            <label id="password">Password:</label>
            <input id="b" type="text" value="">
            <button id="c" type="submit">Login</button>
        </div>
      
</header>
</template>

<script>
export default {
  name: 'login',

 
};
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header{
  position: absolute;
  width: 1350px;
  height: 708px;
  left: 0px;
  top: 0px;
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.37) 0%, rgba(0, 0, 0, 0.37) 100%), url("../assets/backgroundGotv.jpg");
}
.login {
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
   background: #888686;
   border: none;
   padding: 0.65em 1em;
   border-radius: 5px;
   color: #ffffff;
}
#body{
    position: absolute;
    width: 700px;
    height: 440px;
    left: 319px;
    top: 196px;
    border: 1px solid #888686;
    box-sizing: border-box;
    box-shadow: 6px 6px 5px rgba(0, 0, 0, 0.25);
    border-radius: 20px;
}
#name{
    position: absolute;
    width: 186px;
    height: 18px;
    left: 1px;
    top: 54px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#a{
    position: absolute;
    width: 525px;
    height: 45px;
    left: 60px;
    top: 86px;
    border: 1px solid #888686;
    box-sizing: border-box;
    border-radius: 10px;
}
#password{
    position: absolute;
    width: 186px;
    height: 18px;
    left: 1px;
    top: 161px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#b{
    position: absolute;
    width: 525px;
    height: 45px;
    left: 60px;
    top: 199px;
    border: 1px solid #888686;
    box-sizing: border-box;
    border-radius: 10px;
}
#c{
    width: 210px;
    height: 52px;
    left: 315px;
    margin-top: 345px;
    color:#fff;
    background: #888686;
    border-radius: 5px;
}
</style>
