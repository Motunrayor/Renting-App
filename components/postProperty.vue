<template>
  <div class="post">
      <p>Have a property for sale? Reach a larger audience and make fast business transactions<br> Lorem Ipsum because I am out of words</p>
      <button>Post a property</button>
  </div>
</template>

<script>
export default {
  name: 'post',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.post{
  position: absolute;
  width: 1350px;
  height: 210px;
  left: 0px;
  top: 2290px;
  background: url("../assets/post.jpg");
}
button{
  width: 130px;
  height: 41px;
  margin-left: 0px;
  top: 3115px;
  background: #66DBB7;
  border-radius: 5px;
  color: #fff;
}
p{
  width: 876px;
  height: 56px;
  margin-left: 250px;
  top: 1036px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  text-align: center;
  color: #FFFFFF;
}
</style>
