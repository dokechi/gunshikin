# 軍資金を作る

転売・物販で欲しい商品を見つけたものの、購入資金が足りない人に向けた、スマホファーストの情報サイトです。

通信費、保険料、電力会社、証券口座、クレジットカードの5つを入口に、確認すべき条件を短く整理し、節約額やポイントを「次の商品何個分か」に翻訳します。

## 現在の状態

ぞろ屋式ホームページ作成工程のうち、ライセンス認証を必要としない設計・本文・ファーストビュー選定まで完成しています。採用FVは`fv-23` Stagger Reveal／A「一行ずつ出る」です。現在はGitHub Pagesの入口`index.html`と、通信費、保険料、電力会社、証券口座、クレジットカードの全5入口を、画像を使わない暫定公開プレビューとして配置しています。30点以上の画像を使う正式版は、正規ライセンス認証後に進めます。

- [`site-design.md`](site-design.md)：戦略、ペルソナ、コピー、スマホ設計
- [`SPEC.md`](SPEC.md)：9ページ分の本文・SEO・注意事項・画像計画
- [`FV-CANDIDATES.md`](FV-CANDIDATES.md)：スマホ用ファーストビュー5案
- [`IMPLEMENTATION-READINESS.md`](IMPLEMENTATION-READINESS.md)：完了範囲と残作業
- [`hp-builder-input.md`](hp-builder-input.md)：制作インテーク
- [`index.html`](index.html)：GitHub Pages用の暫定公開プレビュー
- [`mobile.html`](mobile.html)：通信費の料金差計算と公式確認導線
- [`insurance.html`](insurance.html)：保険料の同条件比較、確認チェック、公式情報導線
- [`power.html`](power.html)：電気料金の年額目安、契約条件チェック、公式情報導線
- [`securities.html`](securities.html)：口座開設条件の判定、特典の商品換算、投資リスクと公式情報導線
- [`card.html`](card.html)：年会費区分、獲得条件、特典の商品換算、作りすぎ防止と公式情報導線

## 公開予定

- リポジトリ：`dokechi/gunshikin`（Public）
- ホスティング：GitHub Pages
- 対象端末：スマートフォンを最優先、タブレット・PCにも対応

## 表示上の方針

- トップは原則1画面で、5つの入口を迷わず選べる
- 金額・ポイントは例示とし、案件・時期・条件による変動を明記する
- アフィリエイトリンク付近にPR表記を置く
- 実画面を装った生成画像は使用しない
- 主要機能をホバーやアニメーションだけに依存させない
