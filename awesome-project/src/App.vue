<template>
  <div class="app">
    <!-- <image class="img" :src="src"></image> -->
    <hello></hello>
    <foo></foo>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'
import Foo from "./components/foo.vue"
export default {
  name: 'app',
  data () {
    return {
      src: "https://img.alicdn.com/tfs/TB1OOl1SVXXXXc_XVXXXXXXXXXX-340-340.png"
    }
  },
  components: {
    Hello,
    Foo
  }
}
</script>

<style scoped>
.app {
  align-items: center;
  padding-top: 200px;
}
.img {
  width: 340px;
  height: 340px;
}
</style>
