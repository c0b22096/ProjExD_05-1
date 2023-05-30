# ハコツミツミ

## 実行環境の必要条件

- python >= 3.10
- pygame >= 2.1

## ゲームの概要

ハコを積み上げてブロックや穴を越え, 敵を爆破, 時には自分も爆破し, 進み続けるアクションゲーム  

### 操作方法

- キーボード
  - A or Light: 左移動
  - D or Right: 右移動
  - Space or Up: ジャンプ
  - Right Shift: 無敵
  - Right Ctrl: 予測線表示
- マウス
  - Left Click: ハコ発射
  - Right Click: ボム発射

### クリア条件

クリアは存在せず, どこまで進めるか自分の限界に挑戦する  
穴に落ちるか敵に当たるとゲームオーバー

## ゲームの実装

### 共通基本機能

- プレイヤーに関するクラス
- ブロックに関するクラス

### 担当追加機能

#### C0A22094

- プレイヤーの加速度運動
- プレイヤーとブロックの衝突
- レベルの生成と保持
- スクロール

#### C0B22096

- プレイヤーの無敵状態

