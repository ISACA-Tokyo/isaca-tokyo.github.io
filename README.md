# ISACA東京支部 アーカイブサイト

ISACA東京支部が過去に掲載したトピックス（お知らせ）の記録を保存する静的サイトです。

公開URL: https://isaca-tokyo.github.io/

## これは何か

2027年初頭に旧サイト `www.isaca.gr.jp` の運用を終了する予定です。
現行サイト（Higher Logic / Engage）へ移さないお知らせや、その配布資料を
失わないよう、このリポジトリに保存しています。

最新の情報は [ISACA東京支部 公式サイト](https://engage.isaca.org/tokyochapter/home) にあります。

## 構成

```
/
├── index.html          アーカイブトップ（年度一覧）
├── 2026/
│   ├── index.html      2026年度トピックス一覧
│   ├── *.html          個別ページ
│   └── files/          配布資料（PDF等）
└── .nojekyll           GitHub PagesのJekyll処理を無効化
```

年度ごとにフォルダを分け、その年度の資料は `<年度>/files/` に置きます。

## ⚠️ このリポジトリは全世界に公開されています

**会員限定のコンテンツを置いてはいけません。**

gitは履歴を保持するため、一度コミットしたファイルは削除しても取得できてしまいます。
「間違えたら消せばよい」が通用しません。

- 会員限定の資料は Higher Logic のドキュメントライブラリに置く
- 旧サイトの `members_only/` 配下のものは、このリポジトリに一切入れない

## 運用

- リポジトリの内容がそのまま公開されます（Higher Logicへのコピペは不要）
- `main` に push すると数分で反映されます
- 見た目は支部共通CSS（S3配信）を参照しているため、公式サイトと揃います

本体のリポジトリは [ISACA-Tokyo/isaca-tokyo-hp](https://github.com/ISACA-Tokyo/isaca-tokyo-hp)（非公開）です。
