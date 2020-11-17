<template>
    <div id="app">
        <Tou></Tou>
        <Dao></Dao>
        <div class="box">房屋分类统计</div>
        <div class="box1">
            <div class="box2">
                <p></p>
            </div>
        </div>
    </div>
</template>
<script>
import Dao from '../components/Dao'
import Tou from '../components/Tou'
export default {
    name:'Jiaoffx.vue',
    components:{
        Tou,
        Dao
    }
}
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
.box1{
    width: 80%;
    height: 500px;
    border: 1px solid #e8e8ff;
    float: left;
    margin-left: 20px;
    margin-top: 40px;
}
</style>