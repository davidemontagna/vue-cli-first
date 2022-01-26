<template>
  <div>
    <div class="jumbotron">
      <img src="../assets/hello-world.jpg">
      <h2>Non so se questo possa essere definito Jumbotron</h2>
      <hr>
      <p>Ma ho provato comunque ad inserire un secondo componente.</p>
      
    </div>    
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h2{
  font-size: 30px;
}
p{
  font-size: 20px;
}
.jumbotron{
  padding: 10px;
  background-color: rgb(207, 231, 231);
}
.jumbotron img{
  height: 300px;
}
</style>
