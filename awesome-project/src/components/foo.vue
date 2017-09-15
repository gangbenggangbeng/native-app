<template>
    <div class="wrapper">
        <text class="h1">{{ msg }}</text>
        <text class="weex">hello weex!!</text>
        <text class="vue">我是庞格格</text>

        


    </div>
</template>
<style scoped>
html{ 
    scrollbar-face-color:#f6f6f6; 
    scrollbar-highlight-color:#fff;
    scrollbar-shadow-color:#eeeeee; 
    scrollbar-3dlight-color:#eeeeee;
    scrollbar-arrow-color:#000; 
    scrollbar-track-color:#fff;
    scrollbar-darkshadow-color:#fff;
  }  
.wrapper{
    flex-direction: column;
    justify-content: center;
}
.weex{
  font-size: 60px;
  text-align: center;
  color: red;
}
.vue{
  font-size: 60px;
  text-align: center;
  margin-top:30px;
  color: #ccc;
}
</style>
<script>
export default {
  name: 'foo',
  data () {
    return {
      msg: 'foo'
    }
  }
}
</script>
</script>