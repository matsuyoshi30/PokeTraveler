## PokeMaker(仮)

## 方針
とりあえず複雑な戦闘、イベントは考えずポケモンGSC風の世界を探索できるゲームを目指すことにする
特定のマスに行ったら特定のキャラが話しかけてくるぐらいのイベントはやりたい

## 今後やること
 - ウィンドウをポケモン風の普通のウィンドウにする
 - BGMを付ける
 - SEを付ける
 - オープニングをつくる
 - イントロダクション(オーキド博士がプレゼンするあれ)を作る(ここでユーザーアバターな名前をユーザーに決めてもらう)

## ウィンドウ
まず文字データをすぐ使える状態にする
ウィンドウデータを使える状態にする
ウィンドウデータに文字を描画していく(一気に描画せずフレームごとに文字を増やしていく)
文字を描画したウィンドウデータを描画する
毎ウィンドウに毎フレーム、文字を最初から描画するのはオーバーヘッドが高いので、前フレームのウィンドウをとっておきそれに1文字追加する形式でやる

将来性も考える
 - メッセージ内にイベントの割り込み
 - メッセージの分岐処理
 - メッセージのループ処理