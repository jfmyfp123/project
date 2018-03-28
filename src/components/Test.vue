<template>
  <div class="hello">
       <h1>{{msg}}</h1>
       <h2>我是测试页</h2>
  </div>
</template>
<script>
export default{
    name:"HelloWorld",
    data:function(){
        return{
            msg:"欢迎进入vue的世界"
        }
    }
}
</script>
<style scoped>
h1,h2{
    color: #42b983;
    font-weight: normal;
}
</style>
