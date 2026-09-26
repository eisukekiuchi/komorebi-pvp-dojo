# こもれび PvP 道場

Railway に配置できるブラウザゲームです。`npm start` で起動し、Railway の `PORT` を使用します。外部パッケージと環境変数の設定は不要です。

## Railway

1. このフォルダを GitHub リポジトリに置き、Railway の **New Project → Deploy from GitHub repo** で選択します。または Railway CLI でこのフォルダから `railway init`、`railway up` を実行します。
2. サービスの **Settings → Networking → Generate Domain** で公開 URL を発行します。
3. `/health` は稼働確認用です。

ローカル確認: `npm start` → `http://localhost:3000`
