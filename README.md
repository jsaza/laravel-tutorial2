# laravel-tutorial2

Laravelでできるいくつかの機能を試していく Part 2

## 履歴

### 認証を試す

- [認証クイックスタート](https://readouble.com/laravel/5.8/ja/authentication.html)

```
$ php artisan make:auth
$ php artisan migrate
```

### 日本語化できるところは自動で行った

- [comja5](https://github.com/laravel-ja/comja5)

```
$ composer require laravel-ja/comja5
$ vendor/bin/comja5 -f #-f --file：日本語言語ファイル生成
$ vendor/bin/comja5 -c #-c --comment：コメント部分の翻訳
```

### Debugbar インストール

```
$ composer require barryvdh/laravel-debugbar
```
### 登録時のメール認証

 - [Email Verification](https://laravel.com/docs/5.8/verification)



---



- **SNSログインを試す**
  - [Socialite](https://readouble.com/laravel/5.7/ja/socialite.html)
- **課金(Stripe)を試す**
  - [Stripe](https://readouble.com/laravel/5.7/ja/billing.html)