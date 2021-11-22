<template>
  <div class="container">
      <h1>Titolo Jumbotron</h1>
      <img src="../assets/returnal-listing-thumb-01-ps5.jpg" alt="img">
      <p>Questo è il testo nell'immagine del Jumbotron posizionato con abolute</p>
  </div>
</template>

<script>
export default {
    name: 'Jumbotron',
}
</script>

<style lang="scss" scoped>
    .container{
        width: 80%;
        margin: 50px auto;
        position: relative;
    }
    img{
        width: 90%;
    }
    p{
        position: absolute;
        left: 150px;
        bottom: 50px;
        font-size: 30px;
        color: #F5E028;
    }
</style>

