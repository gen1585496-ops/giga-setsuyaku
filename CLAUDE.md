# ギガ節約ラボ（giga-site）

素の HTML / CSS の静的サイト。ビルドもフレームワークも無い。
公開先 → https://gen1585496-ops.github.io/giga-setsuyaku/

**共通の約束は `C:\dev\CLAUDE.md` にある。**

## このサイトの役割

1. 「ギガ節約ブラウザ」の紹介ページ
2. **アフィリエイト ASP の審査で提出する媒体を兼ねる**

2つ目が効いてくる。**審査に通る体裁を壊さないこと。**
`disclosure.html`（広告の表示）、`about.html`（運営者情報）、プライバシーポリシーは
ASP が見る。消したりリンクを外したりしない。

## 構造

```
index.html       トップ
app.html         アプリ紹介
about.html       運営者情報      ← ASP 審査で見られる
disclosure.html  広告の表示       ← ASP 審査で見られる
articles/        記事
style.css        全ページ共通
```

## 触るときの注意

- **ビルドは無い。** HTML を直接編集して push すれば GitHub Pages に出る
- 記事を足したら index からリンクする。孤立ページは審査で不利
- スタイルは `style.css` 1本。ページごとにインラインで書き足さない
