# laravel-stripe-EC
Laravelを使ったECサイト

カートに商品を入れて購入することができる。

決済代行サービスStripeを導入。
フロントはBlade使用。

urlはこちら
https://github.com/massu-159/laravel-stripe-EC/

### Stripe公式サイト
https://stripe.com/jp

## 環境変数
まずStripeにサインアップ。

.envファイルに変数設定。
```
STRIPE_PUBLIC_KEY=xxxxxxxxx
STRIPE_SECRET_KEY=xxxxxxxxx
```

## アプリケーションの仕様

### 1. 仕様
- カート
  - カートに商品を追加
  - カート内の商品を表示
  - カート内の商品数を変更
  - カート内の商品を削除
- 商品
  - 商品一覧表示

### 2. 構成技術
- php : "^7.3 | ^8.0"

- composer : "2.0"

- laravel : "^8.12"

- stripe/stripe-php : "^7.75"

- @fortawesome/fontawesome-free : "^5.15.2"

## 備考
ルーティングの一覧を表示するコマンド
```
php artisan route:list
```
