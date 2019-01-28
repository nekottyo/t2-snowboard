<template>
  <div class='nes-container'>
    <div class="nes-container with-title is-rounded">
      <p class="title">とき</p>
      2018/02/10 (日)
    </div>
    <div class="nes-container with-title is-rounded">
      <p class="title">ところ</p>
      <a href="https://gala.co.jp/winter/" target="_blank" rel="noopener">ガーラ湯沢スキー場</a>
    </div>
    <div class="nes-container with-title is-rounded">
      <p class="title">おかね</p>
      <div class="nes-container is-rounded">
        基本</br>
        往復新幹線(自由席) + リフト券 13,000円
      </div>
      <div class="lists">
        <div class="nes-container is-rounded">
          <a href="https://gala.co.jp/winter/" target="_blank" rel="noopener">レンタル</a><br/>
          事前予約で 20% offだから2日前までに申し込む
          <ul class="nes-list is-disc">
            <li>ウエア上下 2,400円</li>
            <li>ボードセット 4,000円</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="nes-container with-title is-rounded">
      <p class="title">予定</p>
      <div class="lists">
        <ul class="nes-list is-disc">
          <li>06:30  東京駅集合</li>
          <li>07:08  新幹線</li>
          <li>09:00  到着</li>
          <li>- あそぶ -</li>
          <li>??:??  帰る</li>
        </ul>
      </div>
    </div>
    <div class="nes-container with-title is-rounded">
      <p class="title">その他</p>
      <ul class="nes-list is-disc">
        <li>温泉(1,200円?)ある</li>
        <li>長い靴下あったほうがいい</li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Schedule extends Vue {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
.nes-list {
  margin: 0 1rem;
  li {
    text-align: left;
    margin: 0 10px;
  }
}
a {
  color: #42b983;
}
.nes-container {
  margin: 3rem 0;
}
</style>
