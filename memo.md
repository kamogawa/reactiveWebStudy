### Figma使い方
#### スタイルガイド作成
 - font : https://fonts.google.com/noto/specimen/Noto+Sans+JP
 - style追加：text or 色　スタイル設定 > 点4アイコンクリック ＞ + クリック　＞　名前設定 > 完了
 - style適用：対象を選択 > 点4アイコンクリック ＞ 登録したstyleを選択

### scss sass
 - 親要素からNestingが可能
 - Mixinsを除く書き方はほぼ同じ
 - scssの方が　{}, ; を使って可読性が良い為、主流

 - ＆：親要素の参照　
 - prefixを使って短くすることも可能
 　- ex: font: { size: 10, weight: 10 } 
 - セレクター
   - :is（）: ieでは動かない, 複数のセレクターを選択できる為、重複を減らす
 - 変数が使える: $変数名:値 変数のscopeあり
 - ファイルインポート：@import "test(.css)" 拡張子なくてもOK

### css
 - [inline block の違い](https://zero-plus.io/media/css-display-format-difference/)

