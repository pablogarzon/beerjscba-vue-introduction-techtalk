<template>
  <div id="slide7">
    <div data-index="3" class="slide-wrapper" style="">
      <div class="slide slide-photo-title vertical">
        <div class="body">
          <h1 class="title">Ciclo de vida de la instancia de vue</h1>
        </div>
        <img id="prueba" src="src/assets/lifecycle.png">
      </div>
    </div>
  </div>
</template>
<script>
export default {
  mounted() {
    var img = document.getElementById('prueba');
    img.style.width = "290px";
  }
}
</script>
<style lang="css" scoped>
</style>
