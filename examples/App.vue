<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <mao-demo />
    <mao-card
      imgSrc="/img/1.jpg"
      summary="3月2日 “捷达之美”员工家属情感体验活动"
    />
    <br>
    <mao-card
      imgSrc="/img/2.jpg"
      summary="3月8日 华北区客户情感体验活动"
    >
      <template v-slot:footer>
        <div class="footer">
          <div class="level">中级 528人报名</div>
          <div class="price">￥299.00</div>
        </div>
      </template>
    </mao-card>
    <br>
    <mao-card 
      imgSrc="/img/3.jpg"
      :width="370"
      :imgHeight="90"
    >
      3月10日 华北区客户情感体验活动
      <template v-slot:footer>
        <div class="footer-spring">
          <div class="level">4步骤 • 6门课</div>
          <div class="level">10965收藏</div>
        </div>
      </template>
    </mao-card>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.footer {
  padding: 0 8px;
  font-size: 1vw;
  text-align: left;
}
.level {
  color: #9199a1;
  margin-bottom: 8px;
}
.price {
  color: #F01414;
}
.footer-spring {
  display: flex;
  justify-content: space-between;
  padding: 0 8px;
  font-size: 1vw;
}
</style>
