<template>
  <div class="nes-container with-title">
    <p class="title">更新履歴</p>
    <ul class="nes-list is-disc">
      <li>01/28</li>
      集合時間を修正しました</br>
      その他を整理しました
      <li>01/29</li>
      未来に生きていた問題を修正しました
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
