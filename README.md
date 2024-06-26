### ■サービス概要

レシピをコピペし、変更したい材料を入力すると、その材料をAIが置換して、レシピを作り直してくれるアプリ

### ■ このサービスへの思い・作りたい理由

飲食業に従事する中で、アレルギーや宗教上の理由で、特定の物を食べられない人用に、レシピを変更して、対応することが多々あった。
その対応を自宅で、自分で対応できるなら、そういった理由がある人でも、作ったり食べたりできる範囲が広がるのではないかと考えた。
（例：クッキーを作りたいが、卵アレルギーの場合　→ 卵の代わりにバナナを使って作る）

### ■ ユーザー層について

### ・ユーザー層

アレルギー、宗教上の理由、体質等の理由で、作ることを断念しているレシピがある人
また、そういったお子さんがいる家庭

### ・対象にした理由

自分自身、体質的にメロンや牛乳が合わず、レシピで出てきた際も別のものに置き換えて作ることが多い。（シチューを作る際、牛乳の代わりに豆乳に変更するなど）
その際、同じ分量を置き換えただけだと、成分的な違いから、出来上がりが変わってしまうことがあり、苦労した経験があるため。

### ■サービスの利用イメージ

### ・利用イメージ

普段の料理時

### ・得られる価値

作れるレシピの幅が広がる

### ■ ユーザーの獲得について

SNS等での発信

### ■ サービスの差別化ポイント・推しポイント

### ・似たようなサービス

[食物アレルギー対応レシピ　検索サイト](https://www.miraizaidan.or.jp/recipe/?pg=1　)
　　現存のレシピの材料を置換できる点で、差別化できていると思う。

### ■ 機能候補

### ・作りたい機能

AIによる置換機能、投稿機能、お気に入り機能、ユーザー登録機能、投稿検索機能、一覧表示

### ・MVPリリース時

AIによる置換機能、投稿機能、一覧表示、投稿検索機能

### ・本リリース時

ユーザー登録機能、お気に入り機能

### ■ 機能の実装方針予定

### 『AIによる置換機能』

イメージ…入力バーが二つあり、一つはレシピを入れ、もう一つは置換する材料を入力できるようなイメージ。

### ■ 使用予定技術スタック
### フロントエンド
	HTML
	CSS（Bootstrap、Font Awesome）
	JavaScript
### バックエンド
	Ruby on Rails
	Ruby
### DB管理
	MySQL
### 使用API
	openAI GPT-3.5Turbo
	(料金等、もう少し良い条件のものがあったら変更します)
### 使用予定Gem
	Sorcery　ユーザー登録・認証機能
	ransack　投稿検索機能
### ■ 画面転移図
[画面転移図](https://www.figma.com/design/tAsIiiIrib5HS2DPfxNrNQ/%E7%94%BB%E9%9D%A2%E8%BB%A2%E7%A7%BB%E5%9B%B3%E3%80%81%E3%83%88%E3%83%83%E3%83%97%E3%83%9A%E3%83%BC%E3%82%B8?t=EjX3W4h7PghsIEpG-1)

### READMEに記載した機能
- [x]AIによる置換機能(未ログインでも利用可能)
- [x]投稿機能
- [x]お気に入り機能
- [x]ユーザー登録機能
- [x]投稿検索機能
- [x]一覧表示(未ログインでも観覧可能)

### 未ログインでも利用可能な機能
- [x]AIによる置換機能(未ログインでも利用可能)
- [x]一覧表示(未ログインでも観覧可能)
### メールアドレス・パスワード変更確認項目
直接変更できるものではなく、一旦メールなどを介して専用のページで変更する画面遷移になっているか？
- [x] メールアドレス
- [x] パスワード

### ■ ER図
[ER図](https://drive.google.com/file/d/15Nqh3bwLtAvl5bLYU8wpBFQVx5ru1LKO/view?usp=sharing)
