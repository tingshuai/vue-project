<template>
  <div id="app">
    <section class="part">
      <aside class="self">
        <div class="name">乔飞</div> 
        <div class="goal">求职意向:Web前端攻城狮</div>
      </aside>
      <aside class="self">
        <ul>
          <li><span class="icon">生辰八字：</span><span class="text">1993.10.08</span></li>
          <li><span class="icon">联系方式：</span><a class="text" href="tel:18058641352">18058641352</a></li>
          <li><span class="icon">邮箱：</span><span class="text">1085370797@qq.com</span></li>
        </ul>
      </aside>
      <aside class="self"><img src="https://avatars2.githubusercontent.com/u/23158246?s=40&v=4" alt="头像"></aside>
    </section>
    <section class="part">
      <h3 class="title">技术背景</h3>
      <svg @drag="drag" class="circle" xmlns="http://www.w3.org/2000/svg" version="1.1">
        <circle cx="100" cy="50" r="40" stroke="black"
        stroke-width="2" fill="red" />
      </svg>
      <svg class="circle" xmlns="http://www.w3.org/2000/svg" version="1.1">
        <circle cx="100" cy="50" r="40" stroke="black"
        stroke-width="2" fill="red" />
      </svg>
      <svg class="circle" xmlns="http://www.w3.org/2000/svg" version="1.1">
        <circle cx="100" cy="50" r="40" stroke="black"
        stroke-width="2" fill="red" />
      </svg>
    </section>
    <section class="part">
      <h3 class="title">工作经历</h3>
      <div class="exprience exprience1">
        <aside class="left"></aside>
        <aside class="right"></aside>
      </div>
      <div class="exprience exprience2">
        <aside class="left"></aside>
        <aside class="right"></aside>
      </div>
      <div class="exprience exprience3">
        <aside class="left"></aside>
        <aside class="right"></aside>
      </div>
    </section>
    <section class="part">
      <h3 class="title">自我评价</h3>

    </section>
  </div>
</template>

<script>

export default {
  name: 'app',
  data(){
    return {
      
      }
  },
  mounted(){

  },
  methods:{
  
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
  border:1px solid red;
}
*{
  margin: 0;
  padding: 0;
}
li{
  list-style: none;
}
</style>
