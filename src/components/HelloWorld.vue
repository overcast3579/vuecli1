<template>
  <div class="hello" :class="class111">
    <div class="img" v-for="item in 6" :key="item">
      <!-- <img :src="require('@/assets/logo.png')" alt="" /> -->
    </div>
    <div>
      <p>{{msg}}</p>
      <p>{{title}}</p>
      <button>巧妙</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title:String,
    msg: String,
    class111:String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
    width: 50%;
    display: inline-flex;
    margin: 1rem;
}
.img {
    height: 150px;
    width: 150px;
    background-color: cadetblue;
}
// h3 {
//   margin: 40px 0 0;
// }
// ul {
//   list-style-type: none;
//   padding: 0;
// }
// li {
//   display: inline-block;
//   margin: 0 10px;
// }
// a {
//   color: #42b983;
// }
// .texttype{
//   background-color: rgb(225, 26, 26);
// }
 </style>
