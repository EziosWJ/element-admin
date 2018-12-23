<template>
  <div class="hello">
    <el-container direction="vertical">
      <el-header>
        <header-nav/>
      </el-header>
      <el-container>
        <el-aside width="300px">
          <slider-nav/>
        </el-aside>
        <el-main>main</el-main>
      </el-container>
      <el-footer>
        footer @copyright 2018
      </el-footer>
    </el-container>
  </div>
</template>

<script>
import HeaderNav from "./commons/HeaderNav";
import SliderNav from "./commons/SliderNav";
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  components: {
    HeaderNav,
    SliderNav
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* h1, h2 {
  font-weight: normal;
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
} */
</style>
