<template>
  <div class="signup">
        <p>Sign Up to get the latest offers in your inbox</p>
    <div id="form_row">
        <input type="text" id="form__input" value="  Email"> <button id="enter">Enter</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'signup',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.signup{
  position: absolute;
  width: 1350px;
  height: 208px;
  left: 0px;
  top: 1364px;
  background: #354A5F;
}
p{
  position: absolute;
  width: 350px;
  height: 28px;
  left: 595px;
  top: 1393px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #FFFFFF;
}
#form_row{
  float:center;
  width: 791px;
  height: 92px;
  margin-left: 324px;
  margin-top: 50px;
  background: #FFFFFF;
}
#form__input{
  width: 554px;
  height: 41px;
  left: 368px;
  margin-top: 35px;
  background: #FFFFFF;
  border: 1px solid #C4C4C4;
  box-sizing: border-box;
  border-radius: 5px;
}
button{
  width: 130px;
  height: 41px;
  left: 937px;
  top: 1475px;
  background: #66DBB7;
  border-radius: 4px;
}
</style>
