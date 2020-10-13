<template>
<!-- <div class="site">
    <p>烟点：阿七烟点</p>
</div> -->
 
<div class="row">

   <div class="purLine">
        <p>扫码设备</p>
  </div>

      <div class="card">
      <div class="card-body">
        <h5 class="card-title">扫码设备A</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
        </div>
    </div>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">扫码设备B</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
        </div>
    </div>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">扫码设备C</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
        </div>
    </div>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">扫码设备D</h5>
        <p class="card-text">ip地址：192.168.1.168</p>
        <p class="card-text">当前版本：{{msg}}</p>
        <p class="card-text">运行状态：{{status}}</p>
        </div>
    </div>
</div>

</template>

<script>
export default {
  name: 'Numeral',
  props: {
    msg: String,
    status:Boolean
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

.card{
    margin: 5px;
    padding: 15px;
    border-radius: 10px
}
.row .purLine
{
    display:flex;
    flex-flow: column;
    justify-content:space-around;
}

</style>
