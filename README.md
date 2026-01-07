# omo5-neighborhood-guide
# OMO5 Neighborhood Guide

OMO5 Kumamoto neighborhood guide published via GitHub Pages.

This repository uses a CSV file as the single source of truth,
allowing multiple editors to update data safely and consistently.



---

## 🌐 公開ページ
https://（ユーザー名）.github.io/omo5-neighborhood-guide/

※ URLは GitHub Pages 有効化後に自動生成されます

---

## 📁 ファイル構成

omo5-neighborhood-guide/
├─ index.html # 表示用HTML（原則編集しません）
├─ omo5-neighborhood-master.csv # 編集用マスターデータ
└─ README.md # この説明書


---

## ✏️ 編集方法（重要）

### 編集するのは **CSVのみ**
- HTMLは編集しません
- Googleスプレッドシートで編集 → CSVを書き出します

---

### 編集手順

1. Googleスプレッドシートで内容を編集
2. 「ファイル → ダウンロード → CSV」
3. ファイル名を **omo5-neighborhood-master.csv** にする
4. GitHubにアップロードして上書き
5. 数分後にWebページへ反映されます

---

## 📌 CSV編集ルール（必ず守ってください）

### ❌ やってはいけないこと
- 列名を変更しない
- 列の順番を変更しない
- カテゴリ名を勝手に追加しない
- 絵文字・記号をカテゴリに入れない

---

### ✅ カテゴリ一覧（プルダウン固定）

- 飲食
- バー
- ショッピング
- 文化・体験
- 観光・エリア

---

## 📝 備考欄について
備考欄には以下を自由記述できます。

- 住所
- 電話番号
- 特徴（例：お城ビュー／ご近所バー対象 など）

※ 表示や検索に使用されます

## 📐 表記ルールについて

店名・カテゴリ・備考の書き方には  
統一ルールがあります。

編集前に、必ず以下を確認してください。

👉 **[STYLEGUIDE.md（表記ルール）はこちら](./STYLEGUIDE.md)**


---

## 🔄 更新タイミング
CSVを更新してGitHubにアップすると  
**自動的にWebページへ反映**されます。

---

## ⚠️ 困ったとき
- 表示されない
- データがおかしい

場合は、  
**CSVの列ズレ・カテゴリ表記揺れ**をまず確認してください。

---

## 管理者向けメモ
- カテゴリ追加・HTML改修は管理者対応
- 年度更新時はCSVを差し替え
