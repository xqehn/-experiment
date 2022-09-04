# 対戦テトリス

このプログラムはテトリスを元に作られています。
ただし、細かいルールなどは若干異なっています。

## 目的

自動で対戦するテトリスのプレーヤーを作成する。

## 動作確認方法

tetris.pyを実行して、ゲームをやってみましょう。
ターミナルで本実験で使用するテトリスの動きが確認できます。

|キー|動作|
|:---:|:---|
|↑|回転|
|→ | 右に1マス|
|←|左に1マス|
|↓|下に1マス|
|スペース|一気に下|

## AIモード

自分で作ったAIの動きを確認する方法です。
今回はランダムに手を選ぶBotを動かしてみます。

最初にサーバを起動します。

```shell
python ai_mode.py
```

その次に、別のターミナルでAIを動かします。

```shell
python client.py
```

ゲームオーバーになるとAIの方は終わります。
サーバを修了したい場合は、**Ctrl-C**です。
**Ctrl-C**はコントロールキーを押しながら、キーのCを押します。

## 実験の方法
各自、Botのディレクトリを自分達のチーム名でコピーし、そのディレクトリのPlayer.pyを書き直して、強いAIを作成してみてください。
