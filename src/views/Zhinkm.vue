<template>
    <div id="app">
    <Tou></Tou>
    <Dao></Dao>    
        <div class="box">开门</div>
        <div class="box1">
             <el-tabs v-model="activeName" type="card" @tab-click="handleClick" style="height:800px">
                <el-tab-pane label="开门统计" name="first">
                    <img src="../assets/t9.png" width="95%">
                </el-tab-pane>
                <el-tab-pane label="开门记录" name="second">
                    <div class="center-box1">
                         <span class="demonstration" style="margin-right:20px;margin-left:50px">开始日期:</span>
                            <el-date-picker v-model="value1" type="date" placeholder="年/月/日" style="width:300px">
                            </el-date-picker>
                            <span class="demonstration" style="margin-right:20px;margin-left:50px">结束日期:</span>
                            <el-date-picker v-model="value2" type="date" placeholder="年/月/日" style="width:300px">
                            </el-date-picker>
                            <el-date-picker v-model="value3" type="date" placeholder="年/月/日" style="margin-left:50px;width:300px">
                            </el-date-picker>
                            <span class="center-box2">查询</span>
                    </div>
                    <div class="center-box3">
                        <span>抓拍图片</span>
                        <span>卡号</span>
                        <span>刷卡事件</span>
                        <span>设备名称</span>
                        <span>设备号</span>
                        <span>进出动作</span>
                        <span>验证方式</span>
                        <span>持卡人</span>
                        <span>房屋号</span>
                        <span>所在楼栋</span>
                    </div>
                    <div class="center-box4">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <div class="center-box5 block">
                             <el-pagination style="margin-top:20px"
            @size-change="handleSizeChange"
            @current-change="handleCurrentChange"
            :current-page="currentPage4"
            :page-sizes="[100, 200, 300, 400]"
            :page-size="100"
            layout="total, sizes, prev, pager, next, jumper"
            :total="400"
          >
          </el-pagination>
                    </div>
                </el-tab-pane>
            </el-tabs>
            
        </div>
    </div>    
</template>
<script>
import Dao from "../components/Dao"
import Tou from "../components/Tou"
export default {
    name:"Zhinkm",
    components:{
        Tou,
        Dao
    },
    data() {
      return {
        activeName: 'first',
         value1: '',
        value2: '',value3: '',
      };
    },
    methods: {
      handleClick(tab, event) {
        console.log(tab, event);
      }
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
    float: left;
    margin-left: 20px;
    margin-top: 60px;
    border: 1px solid #d4d4ff;
    width: 80%;
    height: 840px;
}
.center-box2{
    padding: 9px 40px;
    background-color: #b6a4fe;
    border-radius: 8px;
    color: #fff;
    margin-left: 100px;
}
.center-box3{
    margin-top: 50px;
}
.center-box3 span{
    width: 149.6px;
    height: 60px;
    font-weight: 900;
    text-align: center;
    line-height: 60px;
    color: #fff;
    background-color: #c0c0ff;
    border-right: 1px solid #fff;
    float: left;
    font-size: 18px;
}
.center-box3>span:nth-of-type(10){
    border-right: 1px solid #c0c0ff;
}
.center-box4 span{
    width: 148.6px;
    height: 60px;
    font-weight: 900;
    text-align: center;
    line-height: 60px;
    color: #fff;
    border: 1px solid #c0c0ff;
    float: left;
    font-size: 18px;
}
.center-box5{
    text-align: center;
    clear: both;
    height: 70px;
    width: 100%;
    border: 1px solid #c0c0ff;
    float: left;
    margin-top: 320px;
}
#app{
    height: 1000px;
}
</style>