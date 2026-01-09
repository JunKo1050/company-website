# 合同会社Corn - 公式Webサイト

物理教育YouTubeチャンネル「たのしいぶつり」を運営する合同会社Cornの公式Webサイトです。
Apple Developer登録用として作成しています。

## 🌐 サイトURL

- **カスタムドメイン**: https://cornph.jp
- **GitHub Pages**: https://junko1050.github.io/company-website/

## 📋 サイト概要

高校生向けの物理教育YouTubeチャンネル「たのしいぶつり」の紹介と、合同会社Cornの企業情報を掲載しています。

### 主なセクション
- **ヒーローセクション**: サービス紹介とYouTubeリンク
- **YouTubeチャンネル**: チャンネルの特徴（わかりやすい解説、高校生向けコンテンツ、楽しく学べる）
- **私の想い**: 物理教育への想いを記載
- **会社概要**: 日英バイリンガルでの企業情報（Apple Developer審査対応）

## 🛠️ 技術スタック

- **HTML5 / CSS3**: シンプルな静的サイト
- **GitHub Pages**: ホスティング
- **お名前.com**: カスタムドメイン管理

## 📁 ファイル構成

```
cornwebsite/
├── index.html          # メインHTMLファイル
├── styles.css          # スタイルシート
├── kv-image.jpeg       # キービジュアル画像
├── logo.png            # ファビコン
├── CNAME               # カスタムドメイン設定
└── README.md           # このファイル
```

## 🚀 デプロイ方法

### 変更をプッシュ
```bash
git add .
git commit -m "Update content"
git push
```

GitHub Pagesが自動的にデプロイします（数分かかる場合があります）。

## 🔧 DNS設定（お名前.com）

### Aレコード設定
ホスト名: `@`
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

### CNAME設定（オプション）
ホスト名: `www`  
値: `junko1050.github.io`

## 📝 カスタマイズ方法

### 会社情報の編集
[index.html](index.html) の「会社概要」セクションを編集してください。

### YouTubeリンクの変更
`https://www.youtube.com/@tanoshi-butsuri` の部分を検索して置換してください。

### デザインの変更
[styles.css](styles.css) でカラーやレイアウトを調整できます。

## 📞 お問い合わせ

- **Email**: info@cornph.jp
- **営業時間**: 平日 9:00-18:00 (JST)

## 📄 ライセンス

© 2026 合同会社Corn (Corn LLC). All rights reserved.
[CNAME](CNAME) ファイルを編集して、取得したドメイン名に変更：
```
example.com
```

### デザインの変更
[styles.css](styles.css) を編集してカラーやレイアウトを調整できます。

## 🌐 デプロイ後の確認
- GitHub Pages URL: `https://yourusername.github.io/repo-name/`
- カスタムドメイン: `https://yourdomain.com/`（DNS反映後）

## ⏱️ DNS反映時間
お名前.comでDNS設定後、反映までに **数時間〜48時間** かかる場合があります。

## 📱 Apple Developer登録での利用
このWebサイトのURLを、Apple Developer Program登録時の「会社Webサイト」として使用できます。

## 📄 ファイル構成
```
.
├── index.html          # メインHTML
├── styles.css          # スタイルシート
├── CNAME              # カスタムドメイン設定
├── README.md          # このファイル
└── .github/
    └── copilot-instructions.md
```

## ⚠️ 注意事項
- Apple Developer登録には、会社の実在性を証明できる情報が必要です
- 連絡先情報は正確に記載してください
- サイトは公開されるため、機密情報は記載しないでください