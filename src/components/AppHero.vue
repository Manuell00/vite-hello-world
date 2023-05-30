<script>

</script>

<!-- Inserisco il template -->
<template>
    <div class="container">
        <h2>JUMBOTRON!!</h2>
        <h3>Ecco il secondo componente!!!</h3>
        <p>In questa repo mi sto principalment eesercitando nella crazione di componenti e nel loro inserimento all'interno del template dell'App.vue</p>

        <h4>Tentiamo di inserire un'immagine...</h4>
        <div id="logo">
            <img src="../assets/vue.svg" alt="Vue image">
        </div>
        


    </div>
</template>


<!-- Inserisco lo stile  -->
<style scoped>
  .container{
    height: auto;
    background-color: dodgerblue;
    color: white;
    font-size: 16px;
    font-weight: 300;
  }

  h2{
    font-size: 30px;
    background-color: whitesmoke;
    color: dodgerblue;
  }

  #logo {
    height: 100%;
    width: 100%;
    text-align: center;
  }

  #logo img{
    height: 100px;
    width: 100px;
    
  }

</style>
