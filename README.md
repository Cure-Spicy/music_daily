# Music Diary
ギターが趣味の私が、自分だけの特別なプレイリストを作りました。
**音楽だけじゃない、思い出も一緒に**あなたの音楽ライフを彩ります。

## 目的
自分が演奏した曲を、演奏場所、演奏日、簡単な日記と紐づけて保存可能

## 機能
* spotifyから楽曲情報を取得機能
  1. spotifyログイン
  2. Artist名 or Titleを入力
  3. 主キーTempoなどの楽曲情報自動取得
* ダイアリー機能
  * 楽曲情報と、演奏日、演奏場所、日記を紐づけて管理
* 作成したリストから検索が可能
* ユーザーの切り替え
  * 今後ユーザー追加機能を実装予定


##　 使用方法
### 初期設定
  1. PostgreSQLで *music_diary* のDBを作成してください
  <br>
  2. `npm install`
  <br>
  必要なパッケージをインストールします

  3. `npm run build`
  <br>
  　music_diaryDBに必要なテーブルと初期データを挿入します

  4. `npm run start`
  <br>
  サーバーを立ち上げてmusic_diaryが起動します
