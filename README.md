## 概要
COACHTECH 教材 Tutorial 10-2「ミドルウェア ハンズオン演習」で作成した成果物です。

## 使用技術
- PHP 8.x
- Laravel 10.x
- カスタムミドルウェア
- Laravel Fortify（認証）


## 学んだこと
- ミドルウェアが Request と Response の間で処理を介在させる仕組み
- sail artisan make:middleware でのミドルウェア作成と Kernel.php での登録
- ルートへのミドルウェア適用方法（->middleware('check_admin')）

## 動作確認
- ローカルホストにアクセスし、Web画面にて表示されることを確認しました。