# Dr.WASH LP

静的HTMLのみのランディングページです。ビルド不要で、そのままVercelにデプロイできます。

## ファイル構成

- `index.html` … ページ本体
- `style.css` … スタイル
- `vercel.json` … Vercel設定

## GitHub → Vercel デプロイ手順

1. GitHubで新規リポジトリを作成し、この4ファイルをアップロード（またはpush）
2. https://vercel.com にGitHubアカウントでログイン
3. **Add New → Project** で上記リポジトリを選択
4. Framework Preset は **Other**、Build Command / Output Directory は空のまま **Deploy**
5. 以後は `main` にpushするたびに自動で再デプロイされます

## 編集ポイント

- 画像は現在 drwashkuma.com の画像URLを直接参照しています。独自に管理する場合は `images/` フォルダを作って差し替えてください。
- 料金・電話番号・営業時間は公式サイトで確認できなかったため未掲載です。`index.html` の MENU / ACCESS セクションに追記してください。
- 「ご利用の流れ」は一般的な流れで作成した仮の文面です。実際の運用に合わせて修正してください。
