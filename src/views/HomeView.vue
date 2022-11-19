<template>
  <div class="home" >
    <img alt="Vue logo" src="../assets/logo.png">
    
  </div>
  <HelloWorld title="嘿嘿" msg="1dsadadd" class111="texttype"/>
    <HelloWorld title="ffsfdsd" msg="2"/>
    <HelloWorld title="eqwdwadad" msg="3"/>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.texttype{
  background-color: rgb(225, 26, 26);
}
</style>