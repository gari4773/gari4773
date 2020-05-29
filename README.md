# BASEBALL

## BASEBALLとは？
草野球チーム向けの管理システムです

## ダウンロード方法
GitHubからダウンロードするかgit cloneしてください
ダウンロード先

git cloneする場合  
https://github.com/tech-is/baseball  
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
・index.php　最初にこのファイルを読み込んでください  

# データベース構築

# 導入方法
