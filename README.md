# BASEBALL

## BASEBALLとは？
草野球チーム管理システムです

## ダウンロード方法
GitHubからダウンロードするかgit cloneしてください  
ダウンロード先  
https://github.com/tech-is/baseball  

git cloneする場合  
```
git clone https://github.com/tech-is/baseball.git  
```

## 主な機能
```
・選手 チーム登録機能  
・試合マッチング機能(Email)  
・チーム情報機能(選手情報・チーム概要)  
・チームオーダー管理機能  
・グラウンド検索機能  
・試合結果(チーム・選手の成績)  
・野球豆知識コーナー 
```

## 環境構築
```
・apache  
・PHP 7.3.12  
・MYSQL 10.4.10-MariaDB   
・Codeigniter 3.1.11  
```

## 初期設定
```config.ini.sample```をコピーして```config.ini```に名前変更して中身を編集してください。

* **メールの設定 [mail]**  

| パラメータ名 | 指定値 | 例 |
| :---: | :---: | :---: |
| Host | smtpサーバーを指定 | smtp.gmail.com |
| Password | メールアドレスのパスワード | ******* |
| Username | メールアドレス |  *****@gmail.com |
| Secure | SMTPSecure 暗号化を有効にするかどうか | TLS/STARTTLS推奨 |
| Port | ポート番号 | TLS/STARTTLSポート:587 |

* **有効期限の設定 [expire]**  

 | パラメータ名 |指定値 | 例 |
 | :---: | :---: | :---: |
| day | 本登録リンクのアクセス期限 | 15 (minに対する値を指定) |

* **お問い合わせ先の設定 [contact]**

| パラメータ名 | 指定値 | 例 |
| :---: | :---: | :---: |
| Host | smtpサーバーを指定 | smtp.gmail.com |
| Password | メールアドレスのパスワード | ******* |
| Username | メールアドレス |  *****@gmail.com |
| Secure | SMTPSecure 暗号化を有効にするかどうか | TLS/STARTTLS推奨 |
| Port | ポート番号 | TLS/STARTTLSポート:587 |

* **データベースの設定 [database]**

| パラメータ名 | 指定値 | 例 |
| :---: | :---: | :---: |
| Hostname | データベースサーバのホスト名 | localhostなど |
| Username | データベースに接続するために使用するユーザ名 | rootなど |
| Password | データベースに接続するために使用するパスワード | ****** |
| Database | 接続したいデータベース名 | boardなど |
| Dbdriver | データベースの種類 | mysql postgres odbcなど　※小文字で指定しなければならない |

## フォルダ構成
・application/  
　　・config/　デフォルトコントローラーの設定やデータベースの設定ファイルを置いています  
　　・controler/　コントローラーのフォルダ  
　　・model/　データベース周りの関数をまとめたクラスを置いているフォルダ  
　　・views/　フロントエンドファイルをまとめたフォルダ  
・system/ ライブラリやヘルパーを置いているフォルダ  
・assets/ 静的ファイルをおいているフォルダ  
・index.php　最初にこのファイルを読み込んでください  

## データベース構築
database.sqlに記述してあるSQL分をMysqlを立ち上げて実行してください
ターミナルで行う場合
```
mysql -u root -pパスワード
MariaDB[(none)] ここにSQLを張り付けて実行
```
もしくは
```
①cd sqlファイルの場所まで移動
②mysql -u root(ユーザ名) -pパスワード
③create database db名(新規データベース作成)
④\q(ログアウト)
⑤mysql -u root(ユーザ名) -p db名 < baseball.sql(インポート)
```
