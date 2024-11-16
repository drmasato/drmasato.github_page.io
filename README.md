# github_page

このリポジトリは、GitHub Pagesにindex.htmlを公開し、アプリを作成してGitHub Actionsを使用してデプロイする方法を実証するページです。

## 手順

1. **GitHubリポジトリの作成**
   - このリポジトリを作成します。

2. **HTMLファイルの作成**
   - リポジトリのルートに`index.html`を追加します。

3. **リポジトリにファイルをプッシュ**
   - `index.html`をリポジトリにプッシュします。

4. **GitHub Pagesの設定**
   - リポジトリの設定ページに移動し、"Pages"セクションでソースを`main`ブランチの`/root`フォルダーに設定します。

5. **GitHub Actionsの設定**
   - `.github/workflows`ディレクトリにワークフローファイル（例：`deploy.yml`）を作成し、アプリのビルドとデプロイを自動化します。

6. **ホームページの公開**
   - GitHub Pagesを有効にした後、公開されたURLにアクセスして`index.html`が表示されることを確認します。

## 参考リンク

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)