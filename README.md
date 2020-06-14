# MyDSP (My Digital Signal Processing) and Rust programming practice

### motivation
Rust学習、Vモデルの実践、Rustの演習がてら、信号処理アプリを作りたい

### やりたいこと・方針

|項目|説明|
|:--:|:--|
|背景|並列処理やテストがサポートされる言語でマイコン展開できる、信号処理アプリケーションを作りたい|
|課題・目的|マイコンで展開でき、処理速度の速いRustで信号処理を行えるアプリケーションの作成を行えるようにする|
|概要|信号処理の基本的な機能(信号の生成・デジタルフィルタリング・周波集解析・データセット読み取り・作成等)ができるアプリケーションを作成する|
|日程・体制|プロトタイプ初号機＝＝＞2カ月くらいで作れれば...(願望)|
|成果物|信号の生成・デジタルフィルタリング・周波集解析・データセット読み取り・作成、ができるアプリケーション|

### 外から見たときの振る舞いとか

|項目|説明|
|:--:|:--|
|概要|信号(セータセット等)・処理内容を渡して呼び出すと、処理結果を戻り値や、データセット保存で出力を行えるアプリ|
|機能|信号を引数や、ファイルから渡せる・処理内容(フィルタ・周波数変換処理・データのトリム・保存指示)を引数として渡せる・処理結果を戻り値で返せる・処理結果をデータとして保存できる(オフライン処理)→いずれはリアルタイム処理もしたい|
|開発する環境|Windows10 Eclipse RustDT|
|UI|CUI→いずれはGUI|
|データ|input : 与える信号の情報(生データorデータファイル), output : 処理結果(生データorデータファイル)|
|ハード/ソフトウェア構成|実行環境 : Windows application → いずれArduino or ARM-Cortex(マイコン)|


### 内部で見るの振る舞いとか

|項目|説明|
|:--:|:--|
|UI|CUI|
|データ構造|未定|
|プログラム構造|未定|
|ソフト/ハードウェア構成|未定|

### コーディング

|項目|説明|
|:--:|:--|
|未定|未定|
