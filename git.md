# gitの使い方メモ


## 作業ファイルの設定
-----------------------
$ git init
-----------------------
カレントディレクトリがgitの作業フォルダになる。


## 新しいファイルを登録する
---------------------
$ git add "file name"
---------------------

## gitの反映状況の確認
---------------------
$ git 
---------------------

## フォルダ内の変更点の確認
---------------------
$ git status
---------------------

## ファイルの変更内容の確認
---------------------
$ git diff
---------------------

## ローカルに変更を反映(コミット)
---------------------
$ git commit -m "メッセージ"
---------------------

## ローカルをアップロード(push)
---------------------
$ git push origin master
---------------------
origin:gitの名前的なの
master:ローカルの名前的なの

## gitのパスの作り方
---------------------
$ git remote add origin url
---------------------

## 変更内容の確認
---------------------
$ git log [-p]
---------------------
[-p] コメント以上を出す


---------------------
---------------------
---------------------
---------------------
---------------------


# gitの設定

## ユーザー名
---------------------
$ git config --global user.name "user name"
---------------------

## メールアドレス
---------------------
$ git config --global user.email "e-mail addores"
---------------------

