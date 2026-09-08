# okaniwa623.github.io

自作ツールの説明ページとプライバシーポリシーの置き場。
<https://okaniwa623.github.io/> で公開している。

**このリポジトリを public にしている理由**: GitHub Pages（無料プラン）が public リポジトリを
必要とするため。Google の OAuth 同意画面を「本番環境」に公開するには、ホームページ URL と
プライバシーポリシー URL が実在するドメイン上に必要で、その置き場としてここを使っている。

**機密情報は一切置かないこと。** 認証情報の管理方針は `okaniwa623/dev-docs` を参照。

## 構成

```
/                       トップ（ツール一覧）
/gas-mcp/               gas-mcp のホームページ  ← OAuth のホームページ URL
/gas-mcp/privacy.html   プライバシーポリシー    ← OAuth のプライバシーポリシー URL
/gas-mcp/terms.html     利用規約
/style.css              共通スタイル（ライト / ダーク対応）
```

## 新しいツールを足すとき

`<ツール名>/index.html` `privacy.html` `terms.html` を作り、
トップの一覧に 1 行足す。`style.css` を読み込めば体裁は揃う。
