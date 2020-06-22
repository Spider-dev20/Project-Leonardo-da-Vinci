<template>
<body>
  <div>
    <nuxt-link to="/about" >Food-Menu </nuxt-link>
    <h1>LEONARDO DA VINCI</h1>
    <h1>FOOD IS ART</h1>
    <img src="./Leonardo.jpg" alt="">
  </div>
</body>
</template>

<script>
export default {
  name:"index" 
}
</script>
<style>
  body {
    background-color: burlywood;
    text-align: center;
  }
  h1 {
    font-family: initial;
    border: aqua 25px;
    padding-block: aqua 25px;
    margin-block: aqua 24px;
  }
  
</style>