# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください

## 選択した事業側の課題
サービス登録者数の内、男性60%に対して、女性は40%。一方で、
サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。
もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

##　提案内容
1.Xや女性ユーザーの割合が多いinstagramなどとのソーシャルメディア連携
2.女性エンジニアに少しでも関連するコンテンツを設ける

##　実装方針
1.に関して
・instaアカウントやXアカウントでサインアップできるようにする
・SNSキャンペーンの実施
2.に関して
・topページに女性エンジニアの成功ストーリーをトピックとしたビデオコンテンツや
インタビューシリーズなどを設ける

・各成功ストーリーの下には、該当する女性エンジニア主催のもくもく会やイベントへのリンクを設置する。
成功ストーリーに共感した利用者が、実際にそのエンジニアと交流できる機会を提供する。

・女性エンジニアからのメンタリングやキャリアアドバイスを掲載する。
これにより、女性利用者が自身のキャリアに関する質問や悩みを解決できる場を提供できる。
