<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from "./components/layout/Header";
export default {
  name:"app",
  components:{
    Header
  }
}
</script>


<style>
* {
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}

.btn {
  display: inline-block;
  border: none;
  background: #555555;
  color: #ffffff;
  padding: 7px 20px;
  cursor: pointer;
}
.btn:hover {
  background: #666666;
}
</style>
