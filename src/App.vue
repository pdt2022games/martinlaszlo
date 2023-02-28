<template>
  <div class="snowman">
  <thirdBall />
  <secondBall />
  <oneBall />
  </div>
</template>

<script>
import oneBall from './components/oneBall.vue'
import secondBall from './components/secondBall.vue'
import thirdBall from './components/thirdBall.vue'

export default {
  name: 'App',
  components: {
    oneBall,
    secondBall,
    thirdBall,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.snowman
{
  align-items: center;
  flex-wrap: wrap;
  flex-direction: column;
  display: flex;
}
</style>
