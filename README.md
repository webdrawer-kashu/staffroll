# staffRoll

## jQuery Plugins

## 使い方

```html
<link rel="stylesheet" href="staffroll.css">
<script type="text/javascript" src="staffroll.js"></script>
```

```javascript
$(function(){
  $('#staffRoll').staffRoll();
});
```

## options
```javascript
$('#staffRoll').staffRoll({
  type : '1', //タイプの選択
  allTime : 3000,//スクロールのかかる時間（スクロールタイプのみ）
  delay : 1000,//次のスクロールまでのディレイ時間
  fadeTime : 4000//フェードにかかる時間（フェードタイプのみ）
});
```

## type and demo
- type 1
<a href="http://webdrawer.net/sample/js/staffroll/index.html" target="_blank">縦レイアウト＋縦スクロール</a>

- type 2
<a href="http://webdrawer.net/sample/js/staffroll/index2.html" target="_blank">縦レイアウト＋フェード</a>

- type 3
<a href="http://webdrawer.net/sample/js/staffroll/index3.html" target="_blank">縦レイアウト＋横スクロール</a>

- type 4
<a href="http://webdrawer.net/sample/js/staffroll/index4.html" target="_blank">横レイアウト＋縦スクロール</a>

- type 5
<a href="http://webdrawer.net/sample/js/staffroll/index5.html" target="_blank">横レイアウト＋フェード</a>

type 6
<a href="http://webdrawer.net/sample/js/staffroll/index6.html" target="_blank">横レイアウト＋横スクロール</a>

type 7（おまけ）
<a href="http://webdrawer.net/sample/js/staffroll/index7.html" target="_blank">名前が縦に並んでいるバージョンを奥に流れていくスターウォーズっぽいバージョン</a>


##ブログ
<a href="http://webdrawer.net/javascript/staffroll.html" target="_blank">[ブログ]</a>
