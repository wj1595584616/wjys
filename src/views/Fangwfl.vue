<template>
  <div id="app">
    <Tou></Tou>
    <Dao></Dao>
    <div class="box">房屋分类统计</div>
    <div class="center-box">
      <div class="center">
        <p>
          <img src="../assets/z2.png" /><span style="font-size: 30px">1000</span
          ><br />毛坯数
        </p>
        <p>
          <img src="../assets/z3.png" style="margin-top: 10px" /><span
            style="font-size: 30px"
            >500</span
          ><br />精装数
        </p>
        <p>
          <img src="../assets/z4.png" style="margin-top: 10px" /><span
            style="font-size: 30px"
            >100</span
          ><br />豪华精装数
        </p>
        <p>
          <img src="../assets/z5.png" /><span style="font-size: 30px">100</span
          ><br />入住数
        </p>
      </div>
      <div class="center1">
        <select style="width:200px;float:right;margin-right:70px;height:30px;font-size:20px">
          <option value="volvo">所有年份</option>
          <option value="saab">2001</option>
          <option value="opel">2002</option>
          <option value="audi">2003</option>
        </select>
      </div>
      <div class="center2">
          <img src="../assets/z1.png">
      </div>
    </div>
  </div>
</template>
<script>
import Tou from "../components/Tou";
import Dao from "../components/Dao";
export default {
  name: "Fangwfl",
  components: {
    Tou,
    Dao,
  },
};
</script>
<style scoped>
.box {
  width: 1550px;
  height: 40px;
  background: linear-gradient(90deg, #b6a4fe, #fff);
  float: left;
  margin-left: 20px;
  margin-top: 21px;
  color: #fff;
  line-height: 40px;
  font-weight: 900;
  text-indent: 30px;
}
.center-box {
  float: left;
  width: 84%;
  height: 790px;
  border: 1px solid #e0dfdf;
  margin-left: 20px;
  margin-top: 20px;
}
.center {
  height: 200px;
}
.center p {
  float: left;
  width: 250px;
  border: 1px solid;
  height: 90px;
  border-radius: 10px;
  margin-left: 130px;
  margin-top: 30px;
}
.center p img {
  float: left;
  margin-left: 10px;
  margin-right: 40px;
}
.center2{
    clear: both;
    text-align: center;
    padding: 30px;
}
</style>