<template>
  <div class="balls">
  </div>
</template>

<script>
export default {
  name: 'secondBall',
  props: {
    msg: String
  }, 
  methods: {

  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.balls
{
  width: 200px;
  height: 200px;
  border-style: solid;
  border-radius: 50%;
  
  
}
</style>
