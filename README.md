# 会社Webサイト（GitHub Pages）

Apple Developer登録用の会社公式Webサイトです。

## 🚀 セットアップ手順

### 1. GitHubリポジトリの作成
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo-name.git
git push -u origin main
```

### 2. GitHub Pagesの有効化
1. GitHubリポジトリの **Settings** タブを開く
2. 左メニューから **Pages** を選択
3. **Source** を `main` ブランチに設定
4. **Save** をクリック

### 3. カスタムドメインの設定（お名前.com）

#### GitHub側の設定
1. GitHub Pages設定画面で **Custom domain** に独自ドメインを入力
2. `CNAME` ファイルにドメイン名が記載されていることを確認

#### お名前.com側のDNS設定
お名前.comの管理画面で以下のDNSレコードを追加：

**Aレコード（@）:**
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**または CNAMEレコード（www）:**
```
yourusername.github.io
```

### 4. SSL/HTTPS の有効化
GitHub Pagesの設定で「Enforce HTTPS」にチェックを入れる（DNS設定が反映されてから）

## 📝 カスタマイズ方法

### 会社情報の編集
[index.html](index.html) を開いて以下の項目を更新：
- 会社名
- 設立年月
- 代表者名
- 所在地
- 資本金
- 事業内容
- お問い合わせ先（メール・電話）

### ドメイン名の設定
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