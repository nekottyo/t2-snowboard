<template>
  <div id="app">
    <h1>スノボヤガーナ</h1>
    <img alt="Snow Board" src="./assets/snowboard.png" />
    みんなでスノーボードに行こうという企画
    <HelloWorld />
    <Footer />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from './components/HelloWorld.vue';
import Footer from './components/Footer.vue';

@Component({
  components: {
    HelloWorld,
    Footer,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
html,
body,
pre,
code,
kbd,
samp {
  font-family: "Misaki";
}

#app {
  margin: 2rem auto;
  max-width: 800px;
  padding: auto 2rem;

  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img {
  max-width: 180px;
  width: 100%;
  height: auto;
}
</style>
