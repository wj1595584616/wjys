<template>
    <div id="app">
        <Tou></Tou>
        <Dao></Dao>
        <div class="box">缴费分析系统</div>
        <div class="box1">
            <div class="box2">
                <p><img src="../assets/t1.png"><span>1000<br>水费</span></p>
                <p><img src="../assets/t2.png"><span>1000<br>电费</span></p>
                <p><img src="../assets/t3.png"><span>1000<br>煤气费</span></p>
                <p><img src="../assets/t4.png"><span>1000<br>宽带费</span></p>
                <p><img src="../assets/t5.png"><span>1000<br>停车费</span></p>
                <p><img src="../assets/t6.png"><span>1000<br>物业费</span></p>
            </div>
            <div class="box3">
                <img src="../assets/t7.png">
                <img src="../assets/t8.png">
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
    height: 1320px;
    border: 1px solid #e8e8ff;
    float: left;
    margin-left: 20px;
    margin-top: 40px;
}
.box2 p{
    float: left;
    width: 220px;
    height: 100px;
    border: 1px solid;
    border-radius: 10px;
    margin-left: 25px;
}
.box2 p>img{
    float: left;
    margin-top: 6px;
    margin-left: 10px;
}
.box2 p>span{
    font-size: 25px;
    margin-left: 20px;
    margin-top: 10px;
    float: left;
}
.box3 img{
    margin-left: 17px;
    margin-top: 50px;
}
</style>