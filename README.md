# 長野俊和プロフィールLP

`index.html` 1枚で完結。外部依存は Google Fonts（Shippori Mincho）のみ。

## 公開手順（GitHub Pages・レンタル社長と同じ）

1. リポジトリを作り、`index.html` をルートに置く
2. Settings → Pages → Branch を `main` / root に設定
3. 独自ドメインを使う場合は、ルートに `CNAME` ファイル（中身はドメイン名のみ）を置き、DNSのCNAMEレコードを `<user>.github.io` に向ける

## ドメイン候補（未決定）

- `nagano.comfortable-noise.com`（既存ドメインのサブドメイン。追加コストなし・会社と紐づく）
- `comfortable-noise.com/nagano/`（既存サイトの配下）
- 新規ドメイン

迷ったら、まずは既存ドメインのサブドメインで公開して、SNSのプロフィール欄に貼る。

## 後から足せるもの

- 問い合わせフォーム（レンタル社長で使った Google Apps Script 方式をそのまま流用可）
- GA4（`<head>` にタグを1つ足すだけ）
- OGP画像（SNSに貼ったとき表示される画像。1200×630px のPNGを `og-image.png` として置き、`<meta property="og:image">` を追加）

## 中身を直すとき

テキストはすべて `index.html` の中に平文で書いてあるので、エディタで直接書き換えればよい。
紹介者向けスライド（`nagano_profile_for_referrers.pptx`）と内容を揃えておくこと。
