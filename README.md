# OPTUS AI・DX LP

伴走型AI教育サービスのランディングページ。

## 公開URL

https://y-kayukawa-byte.github.io/optus-ai-lp/

## デプロイ

GitHub Pages（`main` ブランチのルート）で公開しています。
`index.html` を編集して `main` に push すると、自動で反映されます。

- **`index.html`** … 公開するLP本体。画像・アイコンはすべて base64 で埋め込んだ自己完結型で、これ1ファイルだけで表示できます。
- **`.nojekyll`** … GitHub Pages の Jekyll 処理を無効化（`{{ }}` の誤変換やビルド失敗を防止）。

## リポジトリ構成

| パス | 役割 | デプロイ |
|------|------|:---:|
| `index.html` | 公開するLP本体（自己完結） | ✅ |
| `.nojekyll` | GitHub Pages 設定 | ✅ |
| `input/` | 制作用の元画像・スクショなどの作業素材 | ❌（gitignore） |
| `*.pdf` | 参考資料 | ❌（gitignore） |

作業素材（`input/`・PDF）はローカルには残していますが、公開サイトには含まれません。
