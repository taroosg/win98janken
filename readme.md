# win98janken

## DEMO

## 紹介と使い方

- Windows98 風のじゃんけん．

- JavaScript はブラクラのイメージだったのでそれっぽい雰囲気でつくった．

- スタートすると相手の手が表示されるので，勝てる手を選択する．制限時間内に 3 回以上勝てばクリア．

## 工夫した点

- できるだけランダムの要素を入れた．ウインドウの表示位置，ボタンの順番，ボタンの英語，など．

- ウインドウが画面からはみ出ないように，画面サイズを取得してウインドウの出る位置を調整した．

- 順を追って機能を追加した．まずじゃんけんのみ → その場でウインドウが表示されて複数回行う → 勝敗のカウントで最終的な結果を決める → 毎回ウインドウを動かす → ボタンの順番と言語を変える，など．

## 苦戦した点

- CSS がつらい．

- 画面のサイズを変更するとレイアウトが崩れたので，都度画面サイズを調整する処理を追加する必要があった．

## 参考にした web サイトなど

- とくになし．
