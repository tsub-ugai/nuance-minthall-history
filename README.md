# ヌュアンスとmint hall（とO-Site）

横浜駅南幸・相鉄ムービル3Fにあるライブハウス（Yokohama O-SITE → Yokohama mint hall）に
ヌュアンスが立った全87公演をまとめた記録ページです。

2026年9月30日の mint hall 閉館にあたって作成しました。

## 内容

- **O-SITE 時代** 17公演（2017.7.16 〜 2019.10.20／ほか中止2）
- **mint hall 時代** 70公演（2021.1.23 〜 2026.9.19）
- 各公演に日付・イベント名・共演者・会場公式ページ・公式Xの該当投稿へのリンク
- 会場・年・シリーズ・状態での絞り込みと、イベント名・共演者名での検索
- 結成・メンバーの増減・大きなワンマン・TIF出演など、ヌュアンス側の節目32件をタイムラインに差し込み

## ファイル

| ファイル | 役割 |
|---|---|
| `index.html` | 本体。CSS・JS・画像すべて内包した1ファイル完結 |
| `og-image.png` | SNS共有時のプレビュー画像 |
| `.nojekyll` | Jekyll の処理を無効化（空ファイル） |

外部から読み込むのは Google Fonts の書体2つのみです。

## 公開方法

GitHub のリポジトリで Settings → Pages → Source を `Deploy from a branch`、
Branch を `main` / `/ (root)` に設定します。

SNS のプレビュー画像が表示されない場合は、`index.html` の `og:image` を絶対URLに変更してください。

```html
<meta property="og:image" content="https://<ユーザー名>.github.io/<リポジトリ名>/og-image.png">
```

## データの出所

- mint hall 時代 … mint hall 公式スケジュールの月別アーカイブ
- O-SITE 時代 … NUANCE 公式X（@nuance_official）の投稿
- 会場情報 … mint hall 公式サイト、LiveFans、ヨコハマ経済新聞
- ヌュアンス側の節目 … Wikipedia、音楽ナタリー、NUANCE 公式X（@nuance_official）の当時の投稿

## ご指摘のお願い

ファンによる非公式のアーカイブです。NUANCE および各会場とは関係ありません。
公開されている情報をもとにまとめていますが、完璧なものではなく、誤りや抜けが含まれている可能性があります。

誤りや問題にお気づきの場合は、[⊃,ζ,"貝](https://x.com/oshushitoon) までリプライ・DMでご連絡ください。
訂正、記載の削除、ページの公開停止まで含めて、すぐに対応します。
