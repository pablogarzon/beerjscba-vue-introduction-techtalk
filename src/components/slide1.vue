<template lang="html">
  <div class="slide">
      <div class="slide slide-title">
        <h1 class="title">VueJs</h1>
      </div>
      <div class="slide slide-author">
        <h4>By</h4>
        <img src="src/assets/evan_you.jpeg" alt="" class="photo">
        <h4 class="name">Evan You</h4>
        <p class="bio">
          <ul>
            <li>AngularJs(Angular1)</li>
            <li>Meteor</li>
          </ul>
        </p>
      </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="css" scoped>

  .slide.slide-title{
    margin-top: 0;
    padding: 0;
  }

  .slide.slide-author{
    margin-top: 0 !important;
    padding-top: 0;
  }

  ul{
    text-align: left;
  }

  .imagenes{
    display: inline;
  }

  .imagenes img{
    width: 50%;
  }
</style>
