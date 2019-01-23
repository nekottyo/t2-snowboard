<template>
  <div>
  <h2>とき</h2>
	<p>2018/02/10 (日)</p>
	<h2>ところ</h2>
	<p>
		<a href="https://gala.co.jp/winter/" target="_blank" rel="noopener">ガーラ湯沢スキー場</a>
	</p>
	<h2>おかね</h2>
	<p>
		基本</br>
		往復新幹線(自由席) + リフト券 13,000円
	</p>
	<p>
		<a href="https://gala.co.jp/winter/" target="_blank" rel="noopener">レンタル</a><br/>
		事前予約で 20% offだから2日前までに申し込む
	</p>
	<ul>
		<li>ウエア上下 2,400円</li>
		<li>ボードセット 4,000円</li>
	</ul>
	<h2>予定</h2>
	<ul>
		<li>06:30  東京駅集合</li>
		<li>07:08  新幹線</li>
		<li>09:00  到着</li>
		<li>- あそぶ -</li>
		<li>??:??  疲れたので帰る</li>
	</ul>
  <h2>備考</h2>
  <ul>
    <li>(思いついたら足す)</li>
    <li>温泉(1,200円?)ある</li>
    <li>長い靴下あったほうがいい</li>
  </ul>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
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
li {
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
