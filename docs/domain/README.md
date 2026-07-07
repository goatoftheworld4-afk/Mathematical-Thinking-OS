# Domain OS

## 目的

- 分野固有の着眼点を、分野ごとのファイルに分割して管理する
- 1つの巨大なファイルへの集中を避ける
- 必要な分野だけを参照しやすくする
- 着眼点の追加・修正・検証を分野単位で行えるようにする

## 現在の状態

- 現在の分野別着眼点は `docs/02_DomainOS.md` にまとめて保存されている
- 分割が完了するまでは、`docs/02_DomainOS.md` を正式な参照元とする
- 分割後も、内容が一致していることを確認するまでは元ファイルを削除しない

## 分割方針

- 1分野につき1ファイルを基本とする
- 着眼点IDは変更しない
- 定義、発動条件、候補操作、非発動条件、誤用、検証項目を保持する
- 単なるコピーではなく、重複や矛盾も確認する
- 移動完了後に各ファイルへのリンクを設定する

## ファイル構成予定

- `algebra.md`
  - 代数
  - ID: `ALG`

- `functions.md`
  - 関数
  - ID: `FUN`

- `sequences.md`
  - 数列
  - ID: `SEQ`

- `probability.md`
  - 確率
  - ID: `PRB`

- `combinatorics.md`
  - 場合の数
  - ID: `CMB`

- `integers.md`
  - 整数
  - ID: `INT`

- `calculus.md`
  - 微分・積分
  - ID: `CAL`

- `limits.md`
  - 極限
  - ID: `LIM`

- `induction.md`
  - 数学的帰納法
  - ID: `IND`

- `vectors.md`
  - ベクトル
  - ID: `VEC`

- `analytic-geometry.md`
  - 図形と方程式
  - ID: `GEO`

- `plane-geometry.md`
  - 平面図形
  - ID: `PLN`

- `spatial-geometry.md`
  - 空間図形
  - ID: `SPG`

- `trigonometry.md`
  - 三角関数
  - ID: `TRG`

- `complex-plane.md`
  - 複素数平面
  - ID: `CPLX`

- `exponential-logarithmic.md`
  - 指数・対数
  - ID: `EXP`

- `logic.md`
  - 集合・命題・論理
  - ID: `LOG`

- `statistics.md`
  - データ分析・統計
  - ID: `STAT`

## 移行手順

- 元ファイルから1分野ずつ新しいファイルへ移す
- 見出しと着眼点IDを確認する
- 数式とMarkdownの表示を確認する
- 元ファイルとの内容一致を確認する
- READMEからリンクする
- 全分野の移行完了後に元ファイルの役割を再検討する

## 完了条件

- 全分野が個別ファイルに分割されている
- 着眼点IDの重複や欠番が確認されている
- 各ファイルがREADMEから参照できる
- `02_DomainOS.md` と分割後ファイルの内容に欠落がない
- GPTが必要な分野だけを参照できる
