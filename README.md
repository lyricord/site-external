# site-external

株式会社リリコード（Lyricord Inc.）の公式コーポレートサイト。GitHub Pages で公開する静的サイト。

- **正本**: [`docs/index.html`](docs/index.html)（単一ファイル・依存なし）
- **公開ソース**: GitHub Pages の Source を `main` ブランチの **`/docs`** フォルダに設定（`docs/` 配下だけを配信するため、この `README.md` はサイトに公開されない）
- **カスタムドメイン**: [`docs/CNAME`](docs/CNAME)（`lyricord.co.jp`）
- **内容の出典**: `lyricord-executive/context`（事業設計書・サービス仕様・名刺 ほか）
- **参考デザイン**: [asaty94/lyrecord-site](https://github.com/asaty94/lyrecord-site) のトーン＆マナーを踏襲

## 掲載内容

| セクション | 出典 |
| --- | --- |
| ブランドの由来（Lyricord ＝ Lyric 言葉 × Cord 絆／シンボルは琴 lyre） | 事業設計書.md（MVV） |
| MVV（Mission / Vision / Value） | 事業設計書.md |
| 事業領域（遺族へ／終活する人へ） | 事業設計書.md（事業領域） |
| 会社概要・お問い合わせ | 名刺.md ほか |

## 公開手順（GitHub Pages）

1. このリポジトリ（`lyricord/site-external`）に push する。
2. GitHub の **Settings → Pages** で、Source を `Deploy from a branch` にし、Branch を `main` / **`/docs`** に設定する。
3. 数分後、発行された URL で公開される。独自ドメイン（`lyricord.co.jp`）は `docs/CNAME` と Pages の Custom domain で設定済み。

## 編集メモ

- ブランド表記は **Lyricord**（Lyric × Cord）。参考サイトの `Lyrecord`（Lyre × Cord）ではない点に注意。
- 購入者向けの取次資料とは別の「コーポレートサイト」の位置づけのため、社名を明示している。
