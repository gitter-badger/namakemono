ナマケモノ育成ゲーム
==========

突然、ナマケモノを7日間預かることになりました。

ナマケモノが死んだり逃げ出したりしないよう、ちゃんと世話をしないといけません。

(1) 7日間、世話するコマンドを入力し、ナマケモノのパラメータを変化させます

(2) 4回コマンドを入力したら、1日が過ぎます

(3) ナマケモノのパラメータは満腹度と機嫌度の2つあり、初期値は10です

(4) 上記(3)のパラメータがゼロ以下になったら即ゲームオーバーです

　・満腹度がゼロ以下…死亡

　・機嫌度がゼロ以下…逃亡

(5) コマンドは食事/掃除/散歩/睡眠の4つ

　・食事：満腹度＋２のみ

　・掃除：満腹度－１、機嫌度－１

　・散歩：満腹度－１、機嫌度＋１

　・睡眠：満腹度－２、機嫌度＋２

(6) まる1日世話をしないだけでパラメータが減少します

　※効果は累積します（連続するほど激しく減少）

　・食事を与えない：満腹度－３

　・睡眠を与えない：機嫌度－３

　・掃除や散歩をしない：機嫌度－１

　例)1日エサをやらない場合は３、2日だと６、3日目だと９減少

------------------------------
【発展型の提案】

１．ナマケモノのパラメータの種類を増やしてみる

２．世話コマンドの種類を増やしてみる（パラメータの増減も工夫する）

３．同じコマンドを連続入力させないとか、回数制限をしてみる

　(食事なら1日3回まで、掃除や散歩は連続入力させない、とか)

４．ナマケモノの機嫌次第で、1日のコマンド入力回数が変わる

　(２～５の範囲でランダムでコマンド回数を変更する)

５．クラスを使って書いてみる

