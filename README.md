# testing-app-practice

## 概要
COACHTECH 教材 Tutorial 10-5「テスト ハンズオン演習」で作成した成果物です。<br>
Laravel 10のテスト機能を使用して、ユーザー作成処理の正常系・異常系テストを実装しました。

## 使用技術
- PHP 8.5.12
- Laravel 10.50.3
- PHPUnit（テスト）
- Eloquent / Factory

## 学んだこと
- User::factory()->create() によるテストデータの作成
- assertDatabaseHas() によるデータベースへの保存確認
- expectException() によるメールアドレス重複時の例外検証

## 動作確認
GitHubから本プロジェクトを取得し、Laravel Sailを使用して起動することで動作確認できます。<br>
./vendor/bin/sail artisan test を実行し、ユーザー作成の正常系テストとメールアドレス重複の異常系テストが成功することを確認してください。<br>
※ 実行にはDocker環境およびテスト用データベースの初期設定が必要です。