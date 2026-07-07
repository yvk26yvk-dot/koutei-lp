# コウテイちゃん 公式LP

## 構成
- index.html — トップページ(LP)
- privacy.html / terms.html — プライバシーポリシー・利用規約
- 画像(コウテイちゃん各表情・アイコン)

## 公開手順(GitHub Pages + 独自ドメイン)
1. GitHubで新しいリポジトリ「koutei-lp」をPublicで作成
2. このフォルダの中身を全部アップロード(Add file → Upload files)
3. Settings → Pages → Branch: main / (root) → Save
4. ドメイン取得後: 同じPages設定画面の「Custom domain」に取得したドメインを入力
   (Cloudflare側のDNSに、GitHub Pagesを指すCNAMEレコードを追加。
    Pages画面の指示に従えばOK。HTTPSは自動で有効化される)

## 公開前に埋めること
- index.html フッターの contact@example.com → 実際の連絡先
- privacy.html / terms.html の [運営者名]・[連絡先メールアドレス]・制定日◯

## 反映
以後はファイルを上書きアップロードすれば1〜2分で反映
