# パスの調べ方を学ぼう（Rails編に入ってた）
- `rails routes`：パスを確認できる。
- 表示される内容
    - Prefix：パスの名前
    - Verb：HTTPメソッド
    - URI Pattern：パス
    - Controller#Action：コントローラー名#アクション名
- パスを調べるタイミング
    - 新しくルーティングを作ったとき
    - 設定したルーティングが上手く動作しないとき
    