# グループホーム withハピネス立川 — 公式サイト

鳥取市立川町のグループホーム「withハピネス立川」（運営：株式会社 WITHHOLDINGS）のトップページ。

**このリポジトリは Claude Code でメンテナンスする前提で構成されています。** 編集ルールは `CLAUDE.md` を参照（Claude Code が自動で読み込みます）。

## 構成

| パス | 内容 |
|---|---|
| `index.html` | トップページ本体（CSS/JS同梱の単一ファイル） |
| `assets/` | 画像（水彩イラスト・実写真・ロゴ） |
| `CLAUDE.md` | Claude Code 用のメンテナンス規約・デザイントークン |

## 公開方法（GitHub Pages）

1. このフォルダをリポジトリのルートに置いて push
2. GitHub → Settings → Pages → Source を「Deploy from a branch」/ `main` / `/ (root)` に設定
3. 数分で `https://<ユーザー名>.github.io/<リポジトリ名>/` に公開されます

以後は Claude Code に修正を指示 →「コミットしてプッシュして」で公開サイトが自動更新されます。

## ページ構成（上から）

1. ナビ（スティッキー、ロゴ＋アンカーリンク＋見学申込CTA）
2. ヒーロー（水彩背景 `hero-watercolor.png` ＋ロゴ＋コピー＋CTA）
3. ファクトバー（365日／5名／0円／車で10分）
4. 想い `#mission`（`letter.png`）
5. 4つの特徴 `#features`（`features.png`）
6. 1日の過ごし方 `#day`（`day-flow.png`）
7. 声 `#voices`（HTMLカード×3）
8. 料金 `#fee`（`fee.png`）
9. Q&A `#qa`（HTMLカード×4）
10. 見学から入居まで `#visit`（`visit-flow.png`）
11. 支援者の方へ `#careplan`（`img-d.png`）＋連携フロー（HTML）
12. アクセス `#access`（地図イラスト＋連絡先カード）
13. 信頼バッジ帯 → 最終CTA → フッター

## 既知のTODO

- 郵便番号（フッター `〒xxx-xxxx`）が未確定
- CTAボタンのリンク先（問い合わせフォーム／Instagram実URL／`tel:`）が未接続
- プライバシーポリシー・利用規約ページが未作成
- 「支援者の方へ」の空室カードは変動情報（更新運用を決めるか固定文言化）
- Tweaksパネル・花カーソル・クリック開花は試作演出（本番で外す場合は CLAUDE.md 参照）
