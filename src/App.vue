<template>
<div id="app">
  <Keynote>
    <!-- Your slides here! -->
    <Slide>
      <Hello/>
    </Slide>
    <Photo-Title-Slide title="In a nutshell" photo="src/assets/laquemegusta.png" vertical animation="slide-right">
      Un resumen breve de mi Historia
    </Photo-Title-Slide>
    <Title-Slide title="¡Es Hora de actualizarse!"
               subtitle="¿Qué tal JS?"></Title-Slide>
    <Photo-Title-Slide title="un bazillon de frameworks"
                     photo="src/assets/js-frameworks.png"
                     vertical>
      <img src="src/assets/meme_pc_wtf.gif" alt="">
    </Photo-Title-Slide>
    <Photo-Title-Slide title="Angular"
                     photo="src/assets/Sel_050.png"
                     vertical>
      <img src="src/assets/Sel_052.png" alt="">
    </Photo-Title-Slide>
    <Photo-Title-Slide title="React"
                     photo="src/assets/Sel_053.png"
                     vertical>
      ¿PHP sos vos?
    </Photo-Title-Slide>
    <Title-Slide title="¿Entonces?"></Title-Slide>
    <Slide>
      <slide1/>
    </Slide>
    <Photo-Title-Slide title="Sintaxis de Vue" photo="src/assets/sintaxis.png" vertical animation="slide-right">
    </Photo-Title-Slide>
    <Slide>
      <slide2/>
    </Slide>
    <Slide>
      <slide7/>
    </Slide>
    <Photo-Slide photo="src/assets/The_Progressive_Framework.jpg"></Photo-Slide>
    <Title-Slide title="Comparativa con otros frameworks/librerias"></Title-Slide>
    <Photo-Slide photo="src/assets/speed.jpg"></Photo-Slide>
    <Title-Slide title="Angular"></Title-Slide>
    <Slide>
      <slide3/>
    </Slide>
    <Slide>
      <slide4/>
    </Slide>
    <Title-Slide title="React"></Title-Slide>
    <Slide>
      <slide6/>
    </Slide>
    <Slide>
      <slide5/>
    </Slide>
    <Photo-Title-Slide title="Hola mundo en React"
                     photo="src/assets/Sel_060.png"
                     vertical>
    </Photo-Title-Slide>
    <Photo-Title-Slide title="Hola mundo en Vue"
                     photo="src/assets/Sel_061.png"
                     vertical>
    </Photo-Title-Slide>
    <Photo-Title-Slide title="Computed Properties"
                     photo="src/assets/Sel_047.png"
                     vertical>
    </Photo-Title-Slide>
    <Photo-Title-Slide title="Compañias usando Vue" photo="src/assets/companies.jpg" vertical animation="slide-right">
    </Photo-Title-Slide>
    <Slide>
      <Bye/>
    </Slide>
    <Slide>
      <Bye/>
    </Slide>
  </Keynote>
</div>
</template>

<script>
import Hello from './components/Hello';
import Bye from './components/Bye';
import slide1 from './components/slide1';
import slide2 from './components/slide2';
import slide3 from './components/slide3';
import slide4 from './components/slide4';
import slide5 from './components/slide5';
import slide6 from './components/slide6';
import slide7 from './components/slide7';
export default {
  name: 'app',
  components: {
    Hello,
    Bye,
    slide1,
    slide2,
    slide3,
    slide4,
    slide5,
    slide6,
    slide7
  }
}
</script>
<style>
@import "assets/css/key-note.css";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
