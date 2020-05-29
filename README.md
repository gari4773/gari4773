# BASEBALL

## BASEBALLとは？
草野球チーム向けの管理システムです

## ダウンロード方法
GitHubからダウンロードするかgit cloneしてください
ダウンロード先

git cloneする場合
https://https://github.com/tech-is/baseball
```
git clone https://github.com/tech-is/baseball.git  
```

## 主な機能
```
・選手 チーム登録機能  
・試合マッチング機能(Email)  
・チーム情報機能(選手情報・チーム概要)  
・チームオーダー管理機能  
・チームカレンダー機能  
・グラウンド検索機能  
・試合結果(チーム・選手の成績)  
・チーム内チャット機能  
・選手募集  
・野球豆知識コーナー 
```
## 環境構築
```
・apache  
・PHP 7.3.12  
・MYSQL 10.4.10-MariaDB   
・Codeigniter 3.1.11  
```

## フォルダ構成
・application/  
　　・config/　デフォルトコントローラーの設定やデータベースの設定ファイルを置いています  
　　・controler/　コントローラーのフォルダ  
　　・model/　データベース周りの関数をまとめたクラスを置いているフォルダ  
　　・views/　フロントエンドファイルをまとめたフォルダ  
・system/ ライブラリやヘルパーを置いているフォルダ  
・assets/ 静的ファイルをおいているフォルダ  
　　・CMS/　CMS本体のcssとjsを置いています  
・index.php　最初にこのファイルを読み込んでください  
・database.txt　データベースを構築するSQL文を記述しています  

# DEMO

"hoge"の魅力が直感的に伝えわるデモ動画や図解を載せる

# Features

"hoge"のセールスポイントや差別化などを説明する

# Requirement

"hoge"を動かすのに必要なライブラリなどを列挙する

* huga 3.5.2
* hogehuga 1.0.2

# Installation

Requirementで列挙したライブラリなどのインストール方法を説明する

```bash
pip install huga_package
```

# Usage

DEMOの実行方法など、"hoge"の基本的な使い方を説明する

```bash
git clone https://github.com/hoge/~
cd examples
python demo.py
```

# Note

注意点などがあれば書く

# Author

作成情報を列挙する

* 作成者
櫻井 和泉 河崎
* 所属
TECH I.S
* E-mail

# License
ライセンスを明示する

"hoge" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

社内向けなら社外秘であることを明示してる

"hoge" is Confidential.

