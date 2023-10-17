# ゲーム作成
## 概要
### スライム育成ゲーム
- 体力（HP）,攻撃（ATK）,防御（DEF）,素早さ（SPD）の4つのステータス
- ステータスの初期値は個体ごとにランダム(ガチャで入手予定)
- レベルが上がるとステータスポイント(SP)を取得し、割り振ることでステータスを伸ばす
- SPの取得は基本は1レベルごとにゲージ1本分、個体によって1.@倍などの補正がかかることがあり、ゲージがたまると追加でSPを獲得
- 会敵時の行動候補は、　  [攻撃][防御][スキル][逃走]
- 素早さは行動順に影響(ポケモンレジェンズアルセウスみたいな)
- スライムは乗り換え？

## 使用ライブラリ
- 候補
  - phaser
    - https://phaser.io/
- typescript使ったほうが便利

## 勉強用
- [node.jsでTypeScript+Phaserなブラウザゲーム開発環境を作る](https://tech.e3factory.com/programming/2551)
- [Phaser-サンプルゲーム作成まで-](https://note.com/_kikiyo_/n/n350a43dcbf37)
- [Web屋がJavaScriptでゲームを作ってSteamで配信するまでの道のり](https://qiita.com/laineus/items/0bb62f58910ccdfa1d34)
