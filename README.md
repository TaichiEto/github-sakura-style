# GitHub Sakura Theme

GitHub を桜っぽい淡い配色にする Stylus 用ユーザースタイルです。  
白地の読みやすさを残しつつ、ボタン・カード・グラフ・プロフィール周りに控えめなピンクを入れています。

## 使い方

1. ブラウザに Stylus を入れる
   - Chrome / Edge: Chrome Web Store から `Stylus` をインストール
   - Firefox: Firefox Add-ons から `Stylus` をインストール
2. Stylus の管理画面を開く
3. `新スタイルを書く` を選ぶ
4. `github-sakura-theme.css` の中身をすべてコピーして貼り付ける
5. 保存する
6. GitHub を開いて反映を確認する

## 対象サイト

このテーマは CSS 内で GitHub に限定しています。

```css
@-moz-document domain("github.com")
```

そのため、他のサイトには影響しません。

## 調整した主な場所

- GitHub 全体の背景・文字色・境界線
- ボタン、フォーム、ドロップダウン
- README / Markdown 表示
- プロフィール README と pinned repository
- Contribution graph / activity overview
- Dashboard / Feed / Copilot input
- ライトモードとダークモード

## カスタマイズ

色を変えたい場合は、`github-sakura-theme.css` の先頭付近にある CSS 変数を編集してください。

```css
--sakura-accent: #c94f70;
--sakura-petal: #f7a8bc;
--sakura-bg: #fffafb;
```

`--sakura-accent` がメインの桜色、`--sakura-bg` が全体背景です。

## 注意

GitHub 側の HTML や class 名が変わると、一部の見た目が崩れる可能性があります。  
見づらい場所が出たら、その画面の HTML かスクリーンショットを見ながら CSS を追加調整してください。
