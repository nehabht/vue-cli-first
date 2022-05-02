<template>
  <div class="jumbotron">
      <Title/>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Totam, vitae.</p>
  </div>
</template>

<script>
import Title from './Title.vue'

export default {
  name: 'Hero',
  props: {
    msg: String
  },
  components: {
      Title
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotron{
    background-color: thistle;
    color: black;
    width: 800px;
    margin: 0 auto;
}

</style>