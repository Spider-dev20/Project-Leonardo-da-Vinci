<template>
<body>
  <div>
    <h1>Kontaktseite</h1>
    <h1><nuxt-link to="./about">Menü</nuxt-link></h1>
    <h1><nuxt-link to="./">Startseite</nuxt-link></h1>
    <h2>Reservierung unter:</h2>
    <h3>0157353057</h3>
    <hr>
    <h2>Adresse:</h2>
    <h3>Casa de Humbre 25</h3>
    <hr>
    <h2>Öffnungszeiten</h2>
    <h3>Täglich von 11:00 bis 23:00 Uhr geöffnet</h3>
    <hr>
    <h2>Email:</h2>
    <h3>veni.vici@gmx.de</h3>
    <hr>
    <br>
    <br>
<img src="./restaurant.jpg" alt="">


    

    
  </div>
</body>
</template>

<script scoped>
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
    border: 15px solid brown;
    background-color: brown;
    margin-block: 15px;
  }
  h2{
    margin-block: 15px;  
  }
  a {
    color: black;
  }
</style>