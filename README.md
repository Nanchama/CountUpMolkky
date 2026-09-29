# CountUpMolkky

カウントアップモルックの得点記録アプリ。

## 構成

- `main`: 基準となるアプリ本体
- `test-branch`: Netlifyで動作確認するためのブランチ
- 静的PWAのため、ビルドコマンドは不要
- NetlifyのPublish directoryはリポジトリ直下（`.`）

## 主なファイル

- `index.html`: アプリ本体
- `sw.js`: オフラインキャッシュ・更新処理
- `manifest.webmanifest`: PWA設定
- `icon-180.png`, `icon-192.png`, `icon-512.png`: アプリアイコン
- `netlify.toml`: Netlify配信設定
