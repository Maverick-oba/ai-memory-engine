# 研究・開発 GitHub 総合インデックス

> 棚卸し日: 2026-10-10（JST）
>
> **全プロジェクトの入口。** リポジトリの場所を探すときは最初にここを見る。
> この索引は GitHub で確認できた13リポジトリと、そのうち取得できた README の記載に基づく。各リポジトリ内の全ファイル・全コミット・ローカル未push成果物を照合済みという意味ではない。

## まずどこを見る？

| 分類 | 目的・研究 | GitHub | 現状／参照先 |
|---|---|---|---|
| 中央競馬 | Ability Graph・中央Web・公開Viewer | [keiba-central-web-compass](https://github.com/Maverick-oba/keiba-central-web-compass) | 2026-10-10更新（[commit 5cd1337](https://github.com/Maverick-oba/keiba-central-web-compass/commit/5cd133716585c6f69be9c0e7f84d3f325f3c1706)）。個別正本・自動公開フローは要再確認 |
| 中央・地方競馬 | Compass・競馬研究基盤 | [Compass](https://github.com/Maverick-oba/Compass) | README未取得。高配当A/B・通常配当・Cut/Ability等の格納位置は未特定 |
| 地方競馬 | 地方Compass Web | [keiba-local-compass-web](https://github.com/Maverick-oba/keiba-local-compass-web) | README未取得。正本・公開手順は要確認 |
| モバイル | Compass Flutterアプリ（Android/iOS） | [compass-app](https://github.com/Maverick-oba/compass-app) | 既存READMEはFlutter雛形。公開版との対応・release手順は未記載 |
| 競艇 | BOAT RACE データ・AI・Compass | [boatrace-ai-compass](https://github.com/Maverick-oba/boatrace-ai-compass) | [README](https://github.com/Maverick-oba/boatrace-ai-compass/blob/main/README.md)に取得・解析・DB・公開手順。実データはローカル |
| 競輪 | 出走表・過去データ取得・監査 | [keirin_data_lab](https://github.com/Maverick-oba/keirin_data_lab) | [README](https://github.com/Maverick-oba/keirin_data_lab/blob/main/README.md)。rawデータはローカル。バックフィルの最新完了範囲は要確認 |
| オート | オートレース取得可能性・分析 | [auto_race_lab](https://github.com/Maverick-oba/auto_race_lab) | [README](https://github.com/Maverick-oba/auto_race_lab/blob/main/README.md)。取得元ごとの規約・許諾・検証状態に注意 |
| Gold EA | XAUUSD TrendMagic / MACD EA | [gold-ea-research](https://github.com/Maverick-oba/gold-ea-research) | [README](https://github.com/Maverick-oba/gold-ea-research/blob/main/README.md)。研究版の正本記載あり。ただしv1.7系・v2.2研究系の区別を要確認 |
| JP225 EA | 日経225 Rebreak EA | [jp225-ea-research](https://github.com/Maverick-oba/jp225-ea-research) | [README](https://github.com/Maverick-oba/jp225-ea-research/blob/main/README.md)。v0.7.6基準との記載 |
| FX EA | 通貨別EA研究 | [fx-ea-research-](https://github.com/Maverick-oba/fx-ea-research-) | README未取得。通貨・ロジック・凍結版は要確認 |
| Gold類似検索 | XAUUSD過去類似チャート | [gold-analog-lab](https://github.com/Maverick-oba/gold-analog-lab) | [README](https://github.com/Maverick-oba/gold-analog-lab/blob/main/README.md)。v0.1/v0.2/v0.2.1研究 |
| 研究記憶・索引 | 全体案内・引き継ぎ事故防止 | [ai-memory-engine](https://github.com/Maverick-oba/ai-memory-engine) | **このREADMEが全体の入口**。既存ファイルは変更せず追加 |
| 作業記録 | Codexテスト・PDF整理記録など | [Codex-test](https://github.com/Maverick-oba/Codex-test) | README未取得。記録の実体と配置は要調査 |

## 正本の探し方

1. この表で対象リポジトリへ移動。
2. 各リポジトリのREADME、docs、検証結果、コミットを確認する。
3. **実装正本・検証正本・運用正本を区別する。** 研究途中の最大値・仮説・過去の会話をそのまま運用正本にしない。
4. Gitで確定できないものは「未確認」と記す。件数を合わせるための後付け調整は禁止。
5. ローカルデータ・未pushファイルが必要なら、その所在とGit未保存の事実を明記する。

## 今回の棚卸しで見つかった要注意点

- **READMEが取得できなかった6件**：`ai-memory-engine`（本ファイル作成前）、`Codex-test`、`Compass`、`keiba-central-web-compass`、`keiba-local-compass-web`、`fx-ea-research-`。READMEがない可能性は高いが、アクセス／パスの問題もあるため「不存在確定」とはしない。
- **compass-app**：READMEがFlutterテンプレートのまま。アプリの公開・復旧入口になっていない。
- **Gold EA**：READMEでは別系統の研究をひとつの「現行基準」にまとめて読む危険がある。v1.7フォワード、v2.2研究、実稼働設定を分離して記録する必要がある。
- **高配当A/B、通常配当、地方高配当**：研究は存在するが、この棚卸しでは保存先の実ファイル・正本コミットを未特定。**再現性確認まで完成扱いにしない**。
- **競輪・オート**：README中に初期時点の記録とその後の進捗が併記されている。最新の監査・コミットを優先して再確認する。
- **重要な非Git資産**：競馬・競艇DB、オッズ、Dukascopy M1、MT4実ログ、rawバックフィル等は別管理の可能性。Git索引だけでデータ復旧できると誤解しない。

## 今後の標準インデックス（各リポジトリに追加する際の型）

各リポジトリのREADMEか `docs/PROJECT_INDEX.md` に、次を揃える。

| 項目 | 必ず記録する内容 |
|---|---|
| 目的 | 何を研究・運用する場所か |
| 状態 | 運用中／研究中／凍結／調査中 |
| 正本 | コードパス、設定、モデルID、commit、確定日 |
| 再現 | 元データ期間、コマンド、照合件数、監査 |
| 運用 | 起動スクリプト、公開先、ローカルルート |
| 注意 | 誤版、失敗条件、上書き禁止対象 |
| 次の作業 | 未解決事項と再開地点 |

**運用ルール：** 重要な検証結果・判断・基準変更は、コードだけでなく根拠メモと一緒にGitへ。全体索引には場所と状態のみ記録し、詳細や巨大データは各リポジトリに置く。既存コードやフォルダを整理目的で勝手に移動・削除しない。

## リンク

- [全リポジトリ一覧（GitHub）](https://github.com/Maverick-oba?tab=repositories)
- [全体索引（このREADME）](https://github.com/Maverick-oba/ai-memory-engine/blob/main/README.md)
