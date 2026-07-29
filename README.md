# Portfolio — Sakurauchi Rinko

UI/UX・Webデザイン・グラフィックのポートフォリオサイト。

ビルドツールを使わない静的サイト（HTML / CSS）です。

## 構成

| ファイル | 内容 |
| --- | --- |
| `index.html` | トップ（About / Skills / Works） |
| `case01.html` | 樹木点検・管理システム（UI/UX） |
| `case02.html` | Projection Mapping Award（Webデザイン） |
| `case03.html` | セキュリティ審査管理（UIデザイン + フロント） |
| `case04.html` | 展示会グラフィック（グラフィック） |
| `style.css` | 全ページ共通スタイル |
| `images/` | 各ケースのビジュアル |

## ローカルで見る

```bash
python3 -m http.server 8080
```

http://localhost:8080 を開きます。

## デザイン

- Navy `#082569` / Gold `#C9A84C` / Warm beige `#EDEBE6`
- Noto Serif JP（見出し）/ Noto Sans JP（本文）
- 文字色は WCAG 2.1 AA のコントラスト比（通常文字 4.5:1）を全ページで満たしています
- `prefers-reduced-motion` に対応
