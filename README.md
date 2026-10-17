# PLUS R · Pixel Run Clock

モノクロのフリップ時計と、60秒で画面を横切るドット絵キャラクターのウィジェットです。

- 現在時刻・日付の表示
- 左右比率をドラッグで調整
- 右下のスイッチでライト／ダーク切り替え（設定はブラウザに保存）
- キャラクターは毎分、右端から走り抜けて左端から再登場
- ゆっくり流れる雲と、モノクロのRPG風の街並み
- 動きを減らすOS設定に対応

## GitHub Pages

このディレクトリのファイルを新しい公開リポジトリのルートへ配置します。
GitHubの Settings → Pages → Deploy from a branch で `main` / `/ (root)` を選択します。ビルドは不要です。

既存の配布サイト `kayumori/todays-goal-clock` とは独立したリポジトリとして公開してください。

## 埋め込み

公開後のGitHub PagesのURLをNotionなどに埋め込めます。推奨サイズは幅600px以上・高さ160px前後です。`?theme=dark` を付けると、テーマ設定をまだ保存していないブラウザではダークモードで開きます。

## ファイル

- `index.html`: ウィジェット本体
- `assets/hood-run-hands-v5.png`: 完成版の8コマ・モノクロ走行素材
- `.nojekyll`: Jekyll処理を省略
