# グ㌰ | 低短橋養魚場（GitHub Pages版）

Wixサイト https://ponnjiu.wixsite.com/gupico の再現版です。
Wixにはサイトの書き出し機能がないため、文章・画像・リンク・配置をもとに
静的サイトとして作り直しました。

## ページ構成

| ファイル | 元サイトのページ |
|---|---|
| `index.html` | HOME |
| `commission.html` | 依頼詳細 |
| `terms.html` | 利用規約,連絡先 |
| `utau.html` | UTAU配布所 |
| `utau/sunadorikunn.html` | 鱼鱸 |
| `utau/yoshidapureco.html` | 吉田ぷれこ |
| `utau/umiushi.html` | 笹倉梓 |
| `utau/sabahi.html` | サバヒー |

- `style.css` … パソコン版のデザイン
- `mobile.css` … スマホ版のデザイン（画面幅820px以下で自動で切り替わります）
- `images/` … 画像一式（`gallery/` はトップのInstagramギャラリー、
  `gallery-utau/` は配布所のギャラリー、`thumbs/` はYouTubeサムネイル、
  `chars/` はキャラクター画像・立ち絵）
- `audio/` … 試聴音源の置き場所（下記参照）

## GitHub Pagesへの公開方法

1. GitHubで新しいリポジトリ `GU-pico.github.io` を作る（Public）
2. このフォルダの中身をすべてアップロードする
   （`gupico-site` フォルダ自体ではなく、中身一式をリポジトリのトップに）
3. 数分待つと https://gu-pico.github.io/ で公開されます
4. 以後の更新は、ファイルを差し替えてアップロードするだけです

※ 画像が多いので、パソコンから GitHub Desktop や git で上げるのが楽です。

## 音声ファイルについて

元サイトの試聴プレイヤーはWix専用の配信形式で、音源ファイルそのものは
取り出せませんでした。各キャラクターページにはプレイヤーの位置だけ
再現してあるので、`audio/README.txt` の通り、元のmp3をファイル名を
合わせて `audio/` に入れるとそのまま再生できるようになります。

## 元サイトと変えたところ

- Instagramのフィード埋め込み → 画像ギャラリー＋Instagramへのリンクに置き換え
  （画像ファイル自体はすべて取り込んであるので、Wix/Instagram側が消えても残ります）
- YouTube動画 → サムネイル画像＋YouTubeへのリンク（クリックで動画が開きます）
- 各音源ページのダウンロードボタン → ページ下部の「配布リンク一覧」に集約
  （BowlRoll / MediaFire / Google Drive のリンク先は元サイトのまま）
- お問い合わせフォーム（Wix専用機能）→ XのDMへの案内に置き換え
