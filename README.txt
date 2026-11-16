SNS HUB v1 - iPhone向け無料PWA

収録ファイル:
index.html / manifest.webmanifest / sw.js / icon.svg

GitHub Pages公開方法:
1. GitHubで新規Publicリポジトリ sns-hub を作成
2. ZIPを解凍し、4ファイルをリポジトリのルートにアップロード
3. Settings → Pages → Deploy from a branch → main / (root) → Save
4. 公開URLをSafariで開く
5. Safariの共有メニュー → ホーム画面に追加

機能:
- 初期アカウント5件の登録
- アカウントの追加・編集・削除
- タスクの追加・編集・振替・完了・見送り・削除
- 日付別の予定一覧、今後の予定
- 投稿下書きの保存・コピー
- ホーム画面の進捗表示
- JSONバックアップと復元
- オフライン利用（初回オンライン読み込み後）

注意:
- 端末内localStorageに保存。複数端末同期はありません。
- Safariのサイトデータ削除等で消失するため、定期的にバックアップしてください。
- 自動投稿、SNS API連携、収益管理、詳細インサイト分析は未実装です。
- GitHub PagesのPublicリポジトリに個人情報やパスワードをアップロードしないでください。
