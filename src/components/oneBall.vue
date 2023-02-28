<template>
  <div class="ball">
  </div>
</template>

<script>
export default {
  name: 'oneBall',
  props: {
    msg: String
  }, 
  methods: {

  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.ball
{
  width: 250px;
  height: 250px;
  border-style: solid;
  border-radius: 50%;
  
}
</style>
