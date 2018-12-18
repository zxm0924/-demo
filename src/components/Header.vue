
<template>
   <mt-header fixed title="梅子庄园"></mt-header>  
</template>
<script>

// Vue.component(Header.name, Header);
  export default {
    data() {
      return {
        activeIndex: '1',
        activeIndex2: '1'
      };
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>
