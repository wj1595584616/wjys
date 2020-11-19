<template>
  <div id="app">
    <Tou></Tou>
    <Dao></Dao>
    <div class="box">物业缴费</div>
    <div class="box-center">
      <el-tabs type="card">
        <el-tab-pane label="水费">
          <div class="center">
            <span class="center1">查看历史账单</span>
            <div class="center2">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>水费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="block center4">
              <el-pagination
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
          </div>
        </el-tab-pane>
        <el-tab-pane label="电费">
          <div class="center">
            <span class="center1">查看历史账单</span>
            <div class="center2">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="center2" style="margin-left: 30px">
              <p style="font-weight: 900">2019/08<span>电费</span></p>
              <p>小星社区1栋2单元5楼0501室<span>小张</span></p>
              <p style="margin-top: 50px">
                <span>￥</span><span>100.00</span><span>立即缴费</span>
              </p>
            </div>
            <div class="block center4">
              <el-pagination
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
          </div>
        </el-tab-pane>
        <el-tab-pane label="停车费">
          <div class="box1">
            <span class="center1">查看历史账单</span>
            <div class="box1-1">
                <div>
                    <span>湘A23J89</span><br>
                    <span>长沙XXX社区停车场</span>
                </div>
                <div>
                    入场时间: 2019-08-13 12:30
                </div>
                <div>
                    停车时长: 1天2小时30分<span>05</span>秒
                </div>
                <div>
                    缴费金额: <span>20</span>元
                </div>
                <div>立即缴费</div>
            </div>
            <div class="box1-1">
                <div>
                    <span>湘A23J89</span><br>
                    <span>长沙XXX社区停车场</span>
                </div>
                <div>
                    入场时间: 2019-08-13 12:30
                </div>
                <div>
                    停车时长: 1天2小时30分<span>05</span>秒
                </div>
                <div>
                    缴费金额: <span>20</span>元
                </div>
                <div>立即缴费</div>
            </div>
            <div class="box1-1">
                <div>
                    <span>湘A23J89</span><br>
                    <span>长沙XXX社区停车场</span>
                </div>
                <div>
                    入场时间: 2019-08-13 12:30
                </div>
                <div>
                    停车时长: 1天2小时30分<span>05</span>秒
                </div>
                <div>
                    缴费金额: <span>20</span>元
                </div>
                <div>立即缴费</div>
            </div>
            <div class="box1-1">
                <div>
                    <span>湘A23J89</span><br>
                    <span>长沙XXX社区停车场</span>
                </div>
                <div>
                    入场时间: 2019-08-13 12:30
                </div>
                <div>
                    停车时长: 1天2小时30分<span>05</span>秒
                </div>
                <div>
                    缴费金额: <span>20</span>元
                </div>
                <div>立即缴费</div>
            </div>
            <div class="box1-1">
                <div>
                    <span>湘A23J89</span><br>
                    <span>长沙XXX社区停车场</span>
                </div>
                <div>
                    入场时间: 2019-08-13 12:30
                </div>
                <div>
                    停车时长: 1天2小时30分<span>05</span>秒
                </div>
                <div>
                    缴费金额: <span>20</span>元
                </div>
                <div>立即缴费</div>
            </div>
            <div class="box1-1">
                <div>
                    <span>湘A23J89</span><br>
                    <span>长沙XXX社区停车场</span>
                </div>
                <div>
                    入场时间: 2019-08-13 12:30
                </div>
                <div>
                    停车时长: 1天2小时30分<span>05</span>秒
                </div>
                <div>
                    缴费金额: <span>20</span>元
                </div>
                <div>立即缴费</div>
            </div>
            <div class="block center4" style="margin-top:45px">
              <el-pagination
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
          </div>
        </el-tab-pane>
        <el-tab-pane label="燃气费">
            <div class="center">
                <p class="center1-1">
                    <span style="margin-left:40px;margin-right:10px">缴费单位:</span>
                    <el-select v-model="select" slot="prepend" placeholder="111燃气有限公司" style="width:400px">
                    <el-option label="餐厅名" value="1"></el-option>
                    <el-option label="订单号" value="2"></el-option>
                    <el-option el-option label="用户电话" value="3"></el-option>
                    </el-select>
                    <span  style="margin-left:70px;margin-right:10px">用户编号:</span>
                    <el-input placeholder="请输入内容" v-model="input"  clearable style="width:400px"></el-input>
                    <span class="center1-2">查询</span>
                    <span class="center1-3">查看历史账单</span>
                </p><hr style="border:1px solid #ededff;margin-top:50px">
                <p>
                    <el-autocomplete v-model="state" :fetch-suggestions="querySearchAsync"  placeholder="请输入内容" @select="handleSelect"></el-autocomplete>
                </p>
            </div>
        </el-tab-pane>
        <el-tab-pane label="固定宽带"
          ><div class="center">水费</div></el-tab-pane
        >
        <el-tab-pane label="有线电视"
          ><div class="center">水费</div></el-tab-pane
        >
        <el-tab-pane label="物业费"><div class="center">水费</div></el-tab-pane>
      </el-tabs>
    </div>
  </div>
</template>
<script>
import Tou from "../components/Tou";
import Dao from "../components/Dao";
export default {
  name: "Wuyjf",
  components: {
    Tou,
    Dao,
  },
  data() {
      return {
      select: ''
      }
  },
};
</script>
<style scoped>
.center1-1{
    margin-top: 40px;
}
.center1-2{
    padding: 10px 60px;
    margin-left: 40px;
    background-color: #b6a4fe;
    border-radius: 5px;
    color: #fff;
}
.center1-3{
    padding: 10px 30px;
    margin-left: 10px;
    background-color: #b6a4fe;
    border-radius: 5px;
    color: #fff;
}
#app {
  height: 1160px;
}
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
.box-center {
  height: 800px;
  margin-top: 40px;
  width: 80%;
  float: left;
  margin-left: 20px;
}
.center {
  width: 99.8%;
  border: 1px solid #dad1ff;
  height: 900px;
}
.center1 {
  float: right;
  padding: 10px 20px;
  background-color: #b9b9ff;
  color: #fff;
}
.center2 {
  width: 400px;
  height: 180px;
  border: 2px solid #ededff;
  border-radius: 14px;
  background-color: #f9f9ff;
  float: left;
  margin-top: 80px;
  margin-left: 90px;
}
.center2 p {
  margin-top: 20px;
  margin-left: 20px;
  font-size: 18px;
}
.center2 p:nth-of-type(1) span {
  margin-left: 50px;
}
.center2 p:nth-of-type(2) span {
  margin-left: 50px;
}
.center2 p:nth-of-type(3) span:nth-of-type(1) {
  color: #fcaa3e;
  font-weight: 900;
}
.center2 p:nth-of-type(3) span:nth-of-type(2) {
  color: #55a0ff;
  font-weight: 900;
}
.center2 p:nth-of-type(3) span:nth-of-type(3) {
  margin-left: 200px;
  padding: 3px 10px;
  color: #fff;
  border-radius: 8px;
  background-color: #b6a4fe;
  font-size: 16px;
}
.center:nth-of-type(1) div:nth-of-type(4) {
  margin-top: 30px;
}
.center div:nth-of-type(5) {
  margin-top: 30px;
}
.center div:nth-of-type(6) {
  margin-top: 30px;
}
.center div:nth-of-type(7) {
  margin-top: 30px;
}
.center div:nth-of-type(8) {
  margin-top: 30px;
}
.center div:nth-of-type(9) {
  margin-top: 30px;
}
.center4 {
  text-align: center;
  clear: both;
  border-top: 1px solid #b9b9ff;
  border-bottom: 1px solid #b9b9ff;
  height: 30px;
  padding: 20px;
  margin-top: 137px;
  float: left;
  width: 100%;
}
.box1{
  width: 99.8%;
  border: 1px solid #dad1ff;
  height: 900px;
  font-size: 18px;
}
.box1-1{
    width: 300px;
    height: 350px;
    border: 1px solid #ceceff;
    border-radius: 48% 48% 0 0;
    float: left;
    margin-top: 40px;
    margin-left: 100px;
    overflow: hidden;
}
.box1-1 div:nth-of-type(1){
    width: 100%;
    height:140px;
    background-color: #b6a4fe;
    color: #fff;
    text-align: center;
    line-height: 40px;
}
.box1-1 div:nth-of-type(1) span:nth-of-type(1){
    font-size: 30px;
    margin-top: 40px;
    margin-left: 80px;
    float: left;
}
.box1-1 div:nth-of-type(1) span:nth-of-type(2){
    font-size: 18px;
    margin-top: 10px;
    float: left;
    clear: both;
    margin-left: 70px;
}
.box1-1 div:nth-of-type(2){
    text-align: center;
    padding: 20px 0;
}
.box1-1 div:nth-of-type(3){
    text-align: center;
    padding:0 0 20px 0;
}
.box1-1 div:nth-of-type(3) span{
    font-weight: 900;
    color: #fcaa3e;
    font-size: 23px;
}
.box1-1 div:nth-of-type(4){
    float: left;
    margin-left: 28px;
    padding: 0 0 20px 0;
}
.box1-1 div:nth-of-type(4) span{
    color: #fcaa3e;
    font-size: 20px;
}
.box1-1 div:nth-of-type(5){
    clear: both;
    float: left;
    padding: 10px 87px;
    background-color: #b6a4fe;
    color: #fff;
    border-radius: 9px;
    margin-left: 30px;
}
</style>