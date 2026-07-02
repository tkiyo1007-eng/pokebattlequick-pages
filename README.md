# ポケバトル早見表 GitHub Pages公開用

このフォルダをGitHub Pagesで公開すると、App Store Connectに入力するPrivacy Policy URLとSupport URLを作れます。

## 入っているページ

- `index.html`
- `privacy.html`
- `support.html`

## 推奨リポジトリ名

`pokebattlequick-pages`

## GitHubでの作業

1. GitHubで新しいPublicリポジトリを作成する。
2. Repository nameを `pokebattlequick-pages` にする。
3. このフォルダの中身をリポジトリへアップロードする。
4. GitHubのリポジトリ画面で `Settings` を開く。
5. 左メニューの `Pages` を開く。
6. `Build and deployment` のSourceを `Deploy from a branch` にする。
7. Branchを `main`、folderを `/root` にして保存する。
8. 数分後、公開URLが表示される。

## App Store Connectに入力するURL

GitHubユーザー名を `<github-user>` とすると、URLは次の形になります。

- Privacy Policy URL: `https://<github-user>.github.io/pokebattlequick-pages/privacy.html`
- Support URL: `https://<github-user>.github.io/pokebattlequick-pages/support.html`

## 公開後の確認

ブラウザで次の2つが開けることを確認します。

- `https://<github-user>.github.io/pokebattlequick-pages/privacy.html`
- `https://<github-user>.github.io/pokebattlequick-pages/support.html`

ページが404の場合、GitHub Pagesの反映待ち、またはPages設定のBranch/folderを確認してください。
