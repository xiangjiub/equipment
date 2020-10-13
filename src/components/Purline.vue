<template>
<!-- <div class="site">
    <p>烟点：阿七烟点</p>
</div> -->
 
<div class="row">

   <div class="purLine">
        <p>{{purname}}</p>

  </div>

    <div class="card">
      <div class="card-body">
        <h5 class="card-title">刷卡设备</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
         <p class="card-text">运行状态：{{status}}</p>
      </div>
    </div>

    <div class="card">
      <div class="card-body">
         <h5 class="card-title">定级设备</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
      </div>
    </div>

    <div class="card">
      <div class="card-body">
         <h5 class="card-title">磅码设备</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
      </div>
    </div>
  
    <div class="card">
      <div class="card-body">
         <h5 class="card-title">打包设备</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
      </div>
    </div>
</div>

<div class="line"></div>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String,
    status:Boolean,
    purname:String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

*{
    margin: 0;
    padding: 0;
}

.row{
    margin: 0px 0px 0px;
    padding: 20px 0;
    display: flex;
    justify-content:space-around;
}

.row .purLine
{
    display:flex;
    flex-flow: column;
    /* align-items:center; */
    justify-content:space-around;
}

.card{
    margin: 5px;
    padding: 15px;
    border-radius: 10px
}
.line{
    height: 1px;
    border-top: solid #ACC0D8 1px;
    margin: 0 20px;
}
</style>
