<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
     wuge(){
       console.log("武哥来过了222！【最新的！】！！")
       console.log("武哥的新方法！")
       console.log("哎呀来的新的")
     },
     zhangyue(){
       console.log("张悦新来了！！！哎呀和！")
       console.log("张悦【武哥走了一次！】来了！！")
     },
     zhangyue2(){
       console.log("张悦222")
     },
     wuge2(){
       console.log("武哥222")
     } 
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
