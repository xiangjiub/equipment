<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <Title msg="设备监控"/>
  <HelloWorld msg="Welcome to Monitoring App"/>
  <div class="pursheb">
  <Numeral  msg="3.5" status="true"/>
  <Nav  msg="4.5" status="true" purname="收购线1"/>
  <Nav  msg="3.5" status="true" purname="收购线2"/>
  <Scan  msg="3.5" status="true"/>

  </div>
  
</template>

<script>
import Title from './components/Title'
import HelloWorld from './components/HelloWorld.vue'
import Numeral from './components/Numeral'
import Nav from './components/Purline'
import Scan from './components/Scan'


export default {
  name: 'App',
  components: {
    Title,
    // HelloWorld,
    Nav,
    Numeral,
    Scan
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* display: flex; */
  /* justify-content: center; */
  /* text-align: center; */
  /* color:  rgb(255, 255, 255); */
  margin-top: 0px;                                                                                                                                                                                                                                                                                                                                     
}

HelloWorld{
  color: #cccccc;
  }
.pursheb{
    background: linear-gradient(0deg,#C4E6DA 10%,#C8EBDF);

}
</style>
