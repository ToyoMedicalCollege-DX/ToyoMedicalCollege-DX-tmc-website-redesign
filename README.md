# 東洋医療専門学校 Homepage Redesign Prototype

東洋医療専門学校の公式サイトをベースに、情報設計とビジュアルを現代的に再構成したトップページのリデザイン案です。

## コンセプト

- 情報量は維持しつつ、トップページの導線を「学科 → 学校の強み → キャンパスライフ → オープンキャンパス」に整理
- 白・濃紺を基調に、学科ごとのアクセントカラーを採用
- PC / タブレット / スマートフォンのレスポンシブ対応
- スマートフォンでは資料請求・OC予約・LINE相談を固定表示
- JavaScriptはモバイルメニューとスクロール表示アニメーションのみ
- フレームワーク不要の静的HTML構成

## ファイル

- `index.html` — トップページ
- `styles.css` — 全スタイル・レスポンシブ対応
- `script.js` — ナビゲーション・アニメーション

## ローカル確認

```bash
python3 -m http.server 8080
```

ブラウザで `http://localhost:8080` を開いてください。

## 注意

このリポジトリはデザイン検討用プロトタイプです。リンクの一部は現行公式サイトへ接続しています。画像は現行公式サイトの公開アセットを参照し、読み込めない場合でもグラデーション背景が表示されるようフォールバックを設定しています。

## 現行サイトから整理した主な導線

- オープンキャンパス: `https://www.toyoiryo.ac.jp/oc/`
- 入試案内: `https://www.toyoiryo.ac.jp/boshu`
- 学費: `https://www.toyoiryo.ac.jp/boshu/gakuhi/`
- 就職支援: `https://www.toyoiryo.ac.jp/career_center/`
- LINE相談: `https://www.toyoiryo.ac.jp/boshu/line-meeting`
- 資料請求: `https://www.toyoiryo.ac.jp/form/shiryo`
