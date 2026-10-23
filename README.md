# denpa-free-save

電波人間のRPG FREE!（3DS）のセーブエディタと解析報告書。

**▶ エディタを開く: https://mamimu1107.github.io/denpa-free-save/**

## 特徴
- **MOD / CFW不要**。savedata.bin を差し替えるだけ
- **ブラウザで完結**。インストール不要、スマホでも開ける。読み込んだファイルはどこにも送信されません
- Azahar（3DSエミュレータ）で動作確認済み
- 所持金・ジュエル・アイテム・電波人間・イベント・ステージ・全フラグ・激レア・転身・未使用データを編集
- 対応: 日本版。更新データ v17 あり／なし（v0）のどちらのセーブも同じ形式で読めます

## 使い方
1. **savedata.bin** を**必ずバックアップ**
2. エディタを開いて **savedata.bin** を読み込む
3. 好きな項目を編集して保存
4. ダウンロードされた **savedata.bin** で元のファイルを置き換える

## 解析報告書
セーブ構造の解析結果を [report.pdf](report.pdf) にまとめています。ROM まわりの記述は [naauao（sweshelo 氏）の lanai 資料](https://github.com/sweshelo/naauao/blob/main/lanai/README.md) と照合しています。

## 注意
- 無保証・自己責任。**必ずバックアップを取ってから**使ってください
- 実機（3DS本体）では未確認です。報告歓迎
- 不具合・要望は [Issues](https://github.com/mamimu1107/denpa-free-save/issues) へ。壊れたセーブを添付してもらえると助かります
- 本ツールは非公式のファン製です。任天堂・ジニアス・ソノリティとは関係ありません

## ライセンス
コード部分は MIT License です。ツールに含まれる ROM 由来のデータ（画像・名称・テキストなど）には MIT は適用されず、権利は各権利者に帰属します。
