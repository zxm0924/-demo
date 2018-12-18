<template>
  <div id="app">
    <el-container>
      <el-header>
          <Header></Header>
      </el-header>
      <el-main>
          <router-view></router-view>
      </el-main>
      <el-footer>
          <Footer></Footer>
      </el-footer>
    </el-container>
  </div>
</template>

<script>
  import Header from './components/Header'
  import Footer from './components/Footer'
  export default {
    name: 'App',
    components: {
      Header,
      Footer
    }
  }

</script>

<style >
  body{
      padding:0;
      margin:0px auto;
  }
</style>
