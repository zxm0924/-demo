<template>
  <div>
    <mt-tabbar v-model="selected" fixed="true">
      <mt-tab-item id="花园">
        <img slot="icon" src="../assets/100.png" width="100px" height="100px">
        花园
      </mt-tab-item>
      <mt-tab-item id="盆栽">
        <img slot="icon" src="../assets/103.png" width="100px" height="100px">
        盆栽
      </mt-tab-item>
      <mt-tab-item id="别墅">
        <img slot="icon" src="../assets/104.png" width="100px" height="100px">
        别墅
      </mt-tab-item>
      <mt-tab-item id="农活">
        <img slot="icon" src="../assets/101.png" width="100px" height="100px">
        农活
      </mt-tab-item>
    </mt-tabbar>
  </div>
</template>

<script>
  export default {
    name: 'Footer',
    data () {
      return {selected: '底部'}
    },
    watch: {
      selected: function (val, oldVal) {
        // console.log(val)
        // click后打印出当前mt-tab-item的id
      }
    }
  }



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .el-carousel__item h3 {
    color: #1caa92;
    font-size: 18px;
    opacity: 0.75;
    line-height: 300px;
    margin: 0;
  }

  .el-carousel__item:nth-child(2n) {
    background-color: #ec7dab;
  }

  .el-carousel__item:nth-child(2n+1) {
    background-color: #58f3bf;
  }

</style>
