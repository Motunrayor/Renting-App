<template>
  <div class="about">
    <div id="head">
      <nav class="nav-about">
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
    <div id="show3">
        <p id="show">THE BETTER STORY<br>Who we are, What we do and where we come from</p>
    </div>
</div>

    <span>
        <div id="second">
           <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
           <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
     </span>

    <span>
        <div id="color">
            <div id= "show1"></div>
            <div id= "show2"></div>
            </div>
    </span>
    
</div>
</template>

<script>
export default {
  name: 'about',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-about{
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
   color: #000;
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
#head{
    position: absolute;
    width: 12340px;
    height: 637px;
    left: 0px;
    top: 0px;
    background:#354A5F;
}
#second{
    position: absolute;
    width: 836px;
    height: 607px;
    left: 0px;
    top: 637px;
    background:#ffffff;
}
#color{
    position: absolute;
    width: 500px;
    height: 607px;
    left: 848px;
    top: 637px;
    background:#E5E5E5;
}
#show{
  position: absolute;
  width: 551px;
  height: 65px;
  margin-left: 247px;
  margin-top: 86px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 42px;
  text-align: center;
  color: #FFFFFF;
}
#show1{
  width: 416px;
  height: 217px;
  margin-left: 64px;
  margin-top: 59px;
  background: url("../assets/about.jpg");
}
#show2{ 
  width: 416px;
  height: 217px;
  margin-left: 64px;
  margin-top: 59px;
  background: url("../assets/about1.jpg");
}
#show3{
  position: absolute;
  width: 999px;
  height: 365px;
  left: 220px;
  top: 147px;
  background: linear-gradient(0deg, rgba(25, 9, 59, 0.29), rgba(25, 59, 9, 0.29)), url("../assets/better.jpg");
}
p{
  text-align:justify;
  margin-top: 59px;
}
</style>
