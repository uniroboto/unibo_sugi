# unibo端末側に配置するファイル群

このリポジトリは、uniboアプリを起動する際に必要なファイル群です。
配置場所はunibo端末の
```bash
/mnt/shell/emulated/0/
```
以下となります。

## フォルダ構成

```bash
- Download
|- almex（アルメックス展示会用データ格納）
 |- image
 |- sound
|- autodemo（プレゼン用データ格納）
 |- image
 |- sound
|- db（uniboの会話定義ファイル格納）
 |- talkdb.csv
|- motion（モーションファイル定義）
 |- ※.txtのモーションファイル群
|- personalData（パーソナルデータファイル格納予定）
 |-
|- recipe（料理レシピのレコメンドデータ格納）
 |- image
 |- recipe_list.json
 |- screening.csv
|- robotexpo（国際ロボット展用データ格納）
 |- image
 |- sound
|- Voice（音声合成用ファイル群格納）
 |- AITalk
|- weather(お天気情報データ格納)
 |- image
 |- sound

- DCIM
|- PersonalData（個人認証用データ格納）※Downloadフォルダに移動予定
```

## 運用方法

### SkillPackに必要なフォルダ構成
新たにSkillPackを追加してそれに必要な画像や音声ファイルの格納方法は、
[SkillPack名]のフォルダを用意してその配下に[image]と[sound]フォルダを設置する
```bash
- [SkillPack]
|- image
 |- xxx.png
|- sound
 |- xxx.wav
```
