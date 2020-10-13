<template>
  <div class="hello">
    <h3>{{ msg }}</h3>

    <!-- <button class="btn btn-primary">测试按钮</button> -->
    
  </div>
  <!-- <input type="text"> -->
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
  div{
  background: linear-gradient(0deg,#C4E6DA 10%,#C8EBDF);
  /* color: #84A5A3; */
  }
  
</style>
