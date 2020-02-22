# brainAR

## できたこと
- WebコンテナのURLを格納したQRコードをARマーカーの内部に配置して読み込ませる
- URLを踏むとA-Frameから端末のカメラのブラウザで仕様命令をだす
- カメラでARのマーカーを読むと、そのパターンから配置したglbを読み込んで表示させる

## 現状の問題点
- 最適な大きさがわからない
- アホほど重い(x3dの方がまだ高速に描画できる)
- 画面の中心にオブジェクトが固定されてしまって肝心の回り込みなどができない