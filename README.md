# item_modifier-reference
item_modifierの1項目であるreferenceに関するサンプルになります。

詳しくはブログ記事『[【マイクラ】referenceでitem_modifierを呼び出す【item_modifier】](https://natsumake.com/item_modifier-reference/)』を参考にしてください。

<h3>概要</h3>
referenceは作成済みのitem_modifierを呼び出す項目です。

複雑な記述を何度も呼び出す必要がある場合に、referenceで呼び出すことで管理が楽になります。

<h3>使い方</h3>

このデータパックを導入することで、タラのドロップ品が名前と説明文が加えられたラピスラズリをドロップするようになります。

この名前と説明文はreferenceによって別の場所に作成されているitem_modifierを呼び出しています。

また、以下のコマンドを実行することで、手元のアイテムに対してreferenceを用いたitem_modifierを適用させることが出来ます。

```copy
/item modify entity @s weapon.mainhand sample:green_gem
```
