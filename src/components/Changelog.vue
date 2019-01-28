<template>
  <div class="nes-container with-title">
    <p class="title">更新履歴</p>
    <ul class="nes-list is-disc">
      <li>02/28</li>
      集合時間を修正しました</br>
      その他を整理しました
    </ul>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Changelog extends Vue {
}
</script>

<style scoped lang="scss">
</style>
