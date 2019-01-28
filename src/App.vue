<template>
  <div id="app">
    <div class="center">
      <h1>スノボヤガーナ</h1>
      <img alt="Snow Board" src="./assets/snowboard.png" />
      <p>みんなでスノーボードに行こうという企画です</p>
    </div>
    <Schedule />
    <Footer />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Schedule from './components/Schedule.vue';
import Footer from './components/Footer.vue';

@Component({
  components: {
    Schedule,
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

  color: #2c3e50;
  margin-top: 60px;
}

.center {
  text-align: center;
}

img {
  max-width: 180px;
  width: 100%;
  height: auto;
}
</style>
