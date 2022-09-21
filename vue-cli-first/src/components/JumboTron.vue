<template>
<div class="container">
<div class="jumbo-container">
    <img alt="Jumbotron logo" src="../assets/jumbo.png">
</div>
</div>

</template>

<script>
export default {
  name: 'JumboTron'
  
}
</script>

<style scoped >

.container{
  display:flex;
  justify-content:center;
}

.jumbo-container{
  max-width:1200px;
}

img{
width:100%;
}

</style>