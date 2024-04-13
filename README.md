# item_modifier-reference
item_modifierの1項目であるreferenceに関するサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
referenceは作成済みのitem_modifierを呼び出す項目です。

複雑な記述を何度も繰り返す場合に、元となるファイルを作成したうえで、呼び出すことで管理が楽になります。

<h3>使い方</h3>

このデータパックを導入することで、タラのドロップ品が名前と説明文が加えられたラピスラズリをドロップするようになります。

この名前と説明文はreferenceによって別の場所に作成されているitem_modifierを呼び出しています。

また、以下のコマンドを実行することで、手元のアイテムに対してreferenceを用いたitem_modifierを適用させることが出来ます。

```copy
/item modify entity @s weapon.mainhand sample:green_gem
```
