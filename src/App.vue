<template>
  <div id="app">
    <img alt="Snow Board" src="./assets/snowboard.png" />
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
  font-family: "Nu Kinako Mochi";
  src: url("assets/fonts/NuKinakoMochi-Reg.otf") format("opentype");
}

#app {
  width: 80%;
  margin: 0 auto;

  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img {
  width: 40%;
}
</style>
