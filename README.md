# 公開手順（GitHub Pages・無料）
1. https://github.com で無料アカウントを作成（メール認証まで）。
2. 右上「＋」→「New repository」→ 名前を英数字で入力（例 konshinkai）→ Public →「Create repository」。
   ※無料プランのGitHub Pagesは公開リポジトリが前提です（非公開での利用可否はプラン次第なのでご確認ください）。
3. 「uploading an existing file」をタップし、このフォルダの index.html / config.js / manifest.json / sw.js をドラッグ。「Commit changes」。
4. 「Settings」→ 左の「Pages」→ Source「Deploy from a branch」→ Branch「main」/「(root)」→「Save」。
5. 1〜2分後、Pages画面上部に https://アカウント名.github.io/konshinkai/ と表示されます。これが公開URLです。
6. スマホで開く：URLをメモ/メッセージで自分に送り、タップ。
7. iPhoneのホーム画面に追加：Safariで開く →下の共有ボタン→「ホーム画面に追加」→「追加」。
8. 修正：リポジトリで config.js を開く→鉛筆アイコン→編集→「Commit changes」。1〜2分で反映（反映されないときはSafariを再読み込み）。

# 個人情報について
- 公開URLを知る人は誰でも見られます。config.js の DEFAULT_NAME / DEFAULT_PHONE は空欄のまま公開し、利用時にSTEP 1で入力してください。
- 氏名・電話番号は、STEP 1で保存にチェックしない限り、保存も外部送信もされません。
- QR元画像を使う場合は、画像を同じ場所に置き、config.js の MAIL_QR_IMAGE_PATH にファイル名を書いてください。
