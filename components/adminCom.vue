<template>
    <div class="adminCom">
        <h3>ADMIN DASHBOARD</h3>
        <button type="submit">Add a new property </button>
        <div class="input_body">
                <label id="a">NAME OF PROPERTY</label>
                <input type="text" value="">
                <label id="b">PRICE</label>
                <input id="price" type="text" value="">
                <label id="c">LOCATION</label>
                <input id="location" type="text" value="">
                <label id="d">DESCRIPTION</label>
                <input id="description" type="text" value="">
                <button id="add" type="submit">Add</button>
        </div>
        <div>
        <span>
            <div id="image1"></div>
            <h3 id="e">The Runway room in NY</h3>
            <p id="f">#100,000 per year</P>
            <button id="k" type="submit">Update </button>
             <button id="l" type="submit">Delete </button>
        </span>
        <span>
            <div id="image2"></div>
            <h3 id="g">The Runway room in NY</h3>
            <p id="h">#100,000 per year</P>
            <button id="m" type="submit">Update </button>
             <button id="n" type="submit">Delete</button>
        </span>
        <span>
            <div id="image3"></div>
             <h3 id="i">The Runway room in NY</h3>
            <p id="j">#100,000 per year</P>
            <button id="o" type="submit">Update</button>
             <button id="p" type="submit">Delete</button>
        </span>
     </div>
    </div>
</template>

<script>
 export default {
   name: 'adminCom',
}
</script>

<style scoped>
 h3{
    position: absolute;
    width: 218px;
    height: 24px;
    left: 611px;
    top: 126px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 19px;
    line-height: 28px;
    color: #000000;
}
button{
    position: absolute;
    width: 203px;
    height: 50px;
    left: 618px;
    top: 192px;
    color:#fff;
    background: #66DBB7;
    border-radius: 5px;
}
.input_body{
    position: absolute;
    width: 800px;
    height: 540px;
    left: 319px;
    top: 296px;
    background: #FFFFFF;
    border: 1px solid #888686;
    box-sizing: border-box;
    box-shadow: 6px 6px 5px rgba(0, 0, 0, 0.25);
    border-radius: 20px;
}
#a{
    position: absolute;
    width: 186px;
    height: 18px;
    left: 61px;
    top: 54px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#b{
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
#c{
    position: absolute;
    width: 186px;
    height: 18px;
    left: 370px;
    top: 160px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
    input{
    position: absolute;
    width: 625px;
    height: 45px;
    left: 61px;
    top: 86px;
    background: #FFFFFF;
    border: 1px solid #888686;
    box-sizing: border-box;
    border-radius: 10px;
}
#price{
    position: absolute;
    width: 270px;
    height: 45px;
    left: 60px;
    top: 199px;
    background: #FFFFFF;
    border: 1px solid #888686;
    box-sizing: border-box;
    border-radius: 10px;
}
#location{
    position: absolute;
    width: 270px;
    height: 45px;
    left: 420px;
    top: 199px;
    background: #FFFFFF;
    border: 1px solid #888686;
    box-sizing: border-box;
    border-radius: 10px;
}
#d{
    position: absolute;
    width: 186px;
    height: 18px;
    left: 31px;
    top: 284px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#description{
    position: absolute;
    width: 508px;
    height: 100px;
    left: 70px;
    top: 330px;
    background: #FFFFFF;
    border: 1px solid #888686;
    box-sizing: border-box;
}
#add{
    width: 210px;
    height: 52px;
    left: 315px;
    top: 445px;
    color:#fff;
    background: #66DBB7;
    border-radius: 5px;
}
#image1{
    position: absolute;
    width: 339px;
    height: 190px;
    margin-left: 80px;
    top: 1000px;
    bottom: 55.45%;
    background: url("../assets/RunwayRoom.jpg");
}
#image2{
    position: absolute;
    width: 339px;
    height: 190px;
    margin-left: 500px;
    top: 1000px;
    bottom: 55.45%;
    background: url("../assets/RunwayRoom.jpg");
}
#image3{
    position: absolute;
    width: 339px;
    height: 190px;
    margin-left: 909px;
    top: 1000px;
    bottom: 55.45%;
    background: url("../assets/RunwayRoom.jpg");
}
#e{
    position: absolute;
    width: 276px;
    height: 846px;
    left: 96px;
    top: 1212px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#f{
    position: absolute;
    width: 190px;
    height: 20px;
    left: 96px;
    top: 1239px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #888686;
}
#g{
    position: absolute;
    width: 276px;
    height: 28px;
    left: 530px;
    top: 1212px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#h{
    position: absolute;
    width: 190px;
    height: 20px;
    left: 550px;
    top: 1240px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #888686;
}
#i{
    position: absolute;
    width: 276px;
    height: 846px;
    left: 996px;
    top: 1210px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 21px;
    color: #000000;
}
#j{
    position: absolute;
    width: 190px;
    height: 20px;
    left: 996px;
    top: 1239px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    color: #888686;
}
#k{
    position: absolute;
    left: 80px;
    top: 1319px;
    width: 150px;
    height: 42px;
    color:#fff;
    background: #66DBB7;
    border-radius: 4px;
}
#l{
    position: absolute;
    left: 280px;
    top: 1319px;
    width: 150px;
    height: 42px;
    color:#fff;
    background: #66DBB7;
    border-radius: 4px;
}
#m{
    position: absolute;
    left: 500px;
    top: 1319px;
    width: 150px;
    height: 42px;
    color:#fff;
    background: #66DBB7;
    border-radius: 4px;
}
#n{
    position: absolute;
    left: 700px;
    top: 1319px;
    width: 150px;
    height: 42px;
    color:#fff;
    background: #66DBB7;
    border-radius: 4px;
}
#o{
    position: absolute;
    left: 920px;
    top: 1319px;
    width: 150px;
    height: 42px;
    color:#fff;
    background: #66DBB7;
    border-radius: 4px;
}
#p{
    position: absolute;
    left: 1110px;
    top: 1319px;
    width: 150px;
    height: 42px;
    color:#fff;
    background: #66DBB7;
    border-radius: 4px;
}
</style>
 