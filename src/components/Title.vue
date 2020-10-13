<template>
  <div class="hello">
    <h2>{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: 'Title',
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
    /* box-sizing: border-box; */
}
 div{
  background: #BBE6D6;
  color: #000;
  }
/* h1{
display: flex; 
  justify-content: center;
   text-align: center;
} */
h2{
    margin: 0 40px 0;
    padding: 4px 0;
}

</style>
