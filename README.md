# Roll-A-Ball

Unity チュートリアル Roll-A-Ballをアレンジしたゲームです。

・初めてやったこと
  Sliderを使ったリアルタイムレベル変更（アイテム再配置）
  for Loop文でのアイテム配置と座標調整
  TextMesh Proでのタイトルロゴ作成
  Virtual JoyStick実装
  SetActiveでのUI切り替え
  TimeScale変更によるゲーム停止
  NavMeshによるAI操作
  
・やりたいこと
  サウンド追加
  クリア画面にNext Levelボタンを追加
  エンディング、Total Time追加
  //レベル数を3つに減らす(EASY 4x4,NORMAL 7x7,HARD 10x10)
  
・雑感
  チュートリアルを見てたらアイテムを手動で複製・円形に配置してたので、もっと楽に、正確に円形配置したい！と思いアレンジを始めました。
  スクリプトを探して実装出来たものの、円形だとデッドゾーンが発生するため、これなら四角形でいいやとなり変更。
  （円形ステージも作ってみようかな？壁がムズイか）
  中心を合わせるのが地味に時間かかった。というか植木算方式に並べるのが意外と面倒だった。
  集めるアイテムもCubeからCoin？に変更。爽快感がかなり増えた（あと視認性）。
