# item_modifier-set_damage
item_modifierの1項目であるset_damageに関するサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
アイテムの耐久値を削る・回復させることが可能です。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

タラを倒すことで、耐久値が半分になったダイヤモンドの斧がドロップします。

また、

```copy
/item modify entity @s weapon.mainhand sample:set_damage
```

で手元のアイテムの耐久値を最大値の1割に変更します。

```copy
/item modify entity @s weapon.mainhand sample:set_damage_heal
```

を実行した場合は、手元のアイテムの最大耐久値の1/4だけ、耐久値を回復させます。
