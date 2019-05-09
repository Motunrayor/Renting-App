<template>
  <header class="page__header">
    <div class="header__form">
      <h2>Find the perfect home for you.</h2>
      <form action="POST">
        <div class="form__row">
          <label id="text">Location:</label><br>
          <input type="text" name="location" id="location">
        </div><br>
        <div class="form__row">
            <input type="text" name="location" class="form__input"> <input type="text" name="location"  class="form__input">
        </div><br>
            <button type="submit" class="form__button ">SEARCH</button>
      </form>
    </div>
  </header>
</template>

 <script>
 export default {
   name: 'header',
 }
 </script>

<style scoped>
.page__header {
    height: 600px;
    background: url("../assets/Background.jpg");
    text-align: center;
    display: flex;
    margin: auto;
}
#location{
    width: 554px;
    height: 40px;
    background: #FFFFFF;
    border: 1px solid #C4C4C4;
    box-sizing: border-box;
    border-radius: 5px;
}
.form__input{
    width: 250px;
    height: 40px;
    background: #FFFFFF;
    border: 1px solid #C4C4C4;
    box-sizing: border-box;
    border-radius: 5px;
}
.header__form {
    background: #ffffff;
    border-radius: 10px;
    padding: 1em;
    margin: auto;
}
h2{
    color: #000000;
}
.form__button{
    width: 130px;
    height: 41px;
    left: 655px;
    top: 517px;
    background: #66DBB7;
    border-radius: 4px;
}
</style>

