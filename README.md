# 研究・開発 GitHub 総合インデックス

確認日：2026-10-10（JST）。**新しいチャット・新しい作業は、このページから始める。**

## 最初に読む

- **[新しいチャット用の貼り付け文・作業開始／終了手順](https://github.com/Maverick-oba/Compass/blob/main/docs/git_inventory/START_HERE.md)**
- **[13プロジェクトの詳細索引：正本・確認commit・注意点・再開地点](https://github.com/Maverick-oba/Compass/blob/main/docs/git_inventory/PROJECT_INDEX.md)**
- [引き継ぎテンプレート](https://github.com/Maverick-oba/Compass/blob/main/docs/git_inventory/HANDOFF_TEMPLATE.md)
- [2026-10-10のGit確認記録](https://github.com/Maverick-oba/Compass/blob/main/docs/git_inventory/inventory_20261010.json)

詳細索引はアクセス権のあるprivateリポジトリ内に保存している。新しいチャットには、このページのURLと「対象プロジェクト」「今回の作業」を渡す。手順書が自動で読まれる保証はないので、開始時に読むよう明示する。

## 目的別に探す

| 対象 | GitHub |
|---|---|
| 中央運用・CENTRAL64・Ability Graph・公開Web | [keiba-central-web-compass](https://github.com/Maverick-oba/keiba-central-web-compass) |
| 中央高配当・通常配当研究・地方RTD | [Compass](https://github.com/Maverick-oba/Compass) |
| 地方Ability・地方高配当研究 | [keiba-local-compass-web](https://github.com/Maverick-oba/keiba-local-compass-web) |
| RaceNaviモバイルアプリ | [compass-app](https://github.com/Maverick-oba/compass-app) |
| 競艇データ・AI・公開Compass | [boatrace-ai-compass](https://github.com/Maverick-oba/boatrace-ai-compass) |
| 競輪データ・研究 | [keirin_data_lab](https://github.com/Maverick-oba/keirin_data_lab) |
| オート取得・公式PDF調査 | [auto_race_lab](https://github.com/Maverick-oba/auto_race_lab) |
| Gold EA・Gold Compass研究 | [gold-ea-research](https://github.com/Maverick-oba/gold-ea-research) |
| 日経225 EA | [jp225-ea-research](https://github.com/Maverick-oba/jp225-ea-research) |
| USDJPY／EURUSD EA（repo名末尾のハイフンに注意） | [fx-ea-research-](https://github.com/Maverick-oba/fx-ea-research-) |
| Gold類似チャート探索 | [gold-analog-lab](https://github.com/Maverick-oba/gold-analog-lab) |
| 全体の入口 | [ai-memory-engine](https://github.com/Maverick-oba/ai-memory-engine) |
| 個別作業記録・SBI PDF整理 | [Codex-test](https://github.com/Maverick-oba/Codex-test) |

## 引き継ぎ事故を防ぐルール

1. 詳細索引から対象の仕様・採用判断・監査文書を読む。確認時のリンクはcommit固定で、その後の変更も確認する。
2. 作業PCのrepo／branch／HEAD／未commit差分を確認する。mainだけが作業先とは限らない。
3. 実装正本・研究版・実稼働版を区別する。古い会話、古いREADME、最高成績だけで現行正本を判断しない。
4. データの所在・期間・SHA・時計・対象定義を照合する。件数合わせの後付け調整をしない。
5. 終了時に結果・採否・未確認・次の1作業を対象repoへ記録し、commitとpushを別々に確認して索引を更新する。

## 今回確認した範囲

接続から見えるMaverick-obaの13リポジトリ、全リモートbranch一覧、mainの全ファイル一覧、アプリ作業branchのファイル一覧、選択した仕様・監査文書の本文を照合した。全コード監査・再計算・テスト・公開URL再検証は実施していない。

ローカル未commit／未push、DB、取得原本、稼働EA設定、最新バックフィルcheckpointはこの棚卸しだけでは確認できない。詳細索引に、Gitで確認した事実とローカルで必要な確認を区別して記録した。

既存コード・モデル・取得データの移動、削除、再生成は行っていない。索引は作成時点の記録なので、正本変更やチャット切替時に更新する。

[全リポジトリ一覧](https://github.com/Maverick-oba?tab=repositories)
