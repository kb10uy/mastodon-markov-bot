# mastodon-markov-bot
## 何これ
Mastodon上のアカウントの投稿を、マルコフ連鎖して投稿するBotアプリケーション

**「DM」は学習せず、投稿を「未収載」設定で投稿します。**
利用する際は各サーバーのBotガイドラインに従ってください。
## 必要なもの
Dockerが入ったマシン(入れ方は各自調べてください)

## 動かし方 
0. **NEologd の生成された辞書ディレクトリを `./neologd` に置いておく**
1. Mastodonのアクセストークンを取得(https://example.com/settings/applications/new から取得可能)
2. src/config.ini.sample を src/config.ini にコピー
3. src/config.ini の必要項目を入力(コメントに従って書いてください。)
4. docker-compose up -d でDockerコンテナがビルドされ起動します。

## おすすめ開発方法
VScodeのRemote containerから開発
