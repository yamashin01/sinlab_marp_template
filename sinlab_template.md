---
marp: true
theme: sinlabTheme
paginate: true
---

<!--
_class: title
_paginate: skip
 -->
# スライドタイトル

スライドの内容

---
<!--
class: page
-->

# 基本フォーマット
テストテストテスト
箇条書き
* aaa
* bbb
* ccc

---
<style>
/* 画像コンテナのスタイル */
.image-container {
  display: flex;          /* flexboxを使用して横に並べる */
  justify-content: space-between; /* 画像の間にスペースを確保 */
  gap: 100px;             /* 画像間のギャップを100pxに設定 */
  margin-top: 150px;
}

/* 画像のスタイル */
.image-container img {
  width: 300px;
}
</style>

# 画像あり
画像が入る場合の記述。複数の画像を配置する場合はHTML形式の方が有効らしい。

<div class="image-container">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQu2PE_WAO3wrVzpZJJlDgN0Zz8kD7eWCrnRA&s" alt="画像1">
  <img src="https://via.placeholder.com/200" alt="画像2">
</div>

---
# HTML形式
<div class="normal-textbox">
  HTML形式の記述
  <ul>
    <li>aaa</li>
    <li>bbb</li>
  </ul>
</div>


---
<!--
class: last
_paginate: skip
-->
