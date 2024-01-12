#　 Nuxt 勉強のためのサンプルプロジェクト

Nuxt(星陵祭のサイトで使われているフロントエンドのフレームワーク)を勉強するためのサンプルプロジェクトです。
開発環境を整えるのが大変だと思うのでこれが役に立てば幸いです。<br />

##　使い方

### 開発環境の構築の仕方

![](/images/create_new_fork.png)
<spacer/>
![](/images/fork_create_fork.png)

上の画像のようにこのプロジェクトのフォークを作ってください <br/>
フォーク：GitHub 上で他ユーザーが所有するリポジトリを、自アカウントのリポジトリへコピーすること <br />

自分の github のアカウントのリポジトリを見ると以下のようになっているはずです。<br />
![](/images/repository.png)

先ほどコピーしたリポジトリをクリックしてください。<br/>
すでに使用しているもの、または新しい codespace を作ってそれに入ってください。<br/>
![](/images/codespace.png)

以下のコマンドをターミナル（写真の赤で囲んだ部分）に打ってください。(1 行ごとにエンターを押してください)
![](/images/explanation1.png)
cd ./nuxt-sample （これは自分がいるディレクトリを移動するコマンドです）<br/>
エンターキーを押す <br/>
yarn dev （これは開発用サーバーを立ち上げるためのコマンドです）<br/>
エンターキーを押す <br/>

次に赤で囲った部分を押してください<br/>
![](/images/explanation2.png)
または以下の画像の赤で線を引いた部分を ctr+クリックしてください<br/>
![](/images/port.png)

もしポートの欄に何も表示されていなかったらポートを追加を押して"3000"と入力してください。<br/>

このように表示されたら成功です!
![](/images/explanation3.png)

### 保存の仕方

git についての話がからみます。git は以下のためのツールです。<br/>
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.(公式ホームページより引用)<br/>

プロジェクト内でファイルの変更があると以下の画像のように変更されたファイルが表示されます。<br/>
![](/images/changed_files.png)
以下の画像で示した+ボタンを押してください（変更内容の全てを github 上に送りたいとき）<br/>
![](/images/stage_changed_files.png)
「ステージされている変更」に変更したファイルが表示されていることを確認した後、「コミット」の上のメッセージの欄に変更の内容をかき（内容はなんでもいい）「コミット」のボタンを押してください。<br/>
最後に「変更の同期」を押してください。<br/>
![](/images/connect.png)
