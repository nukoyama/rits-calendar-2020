# rits-calendar-2020
カレンダーサービスへの学年暦のインポート用データ。

- ritsの[学年暦][http://www.ritsumei.ac.jp/profile/info/calendar/]

## how to import

### [Google Calendar][https://www.google.com/calendar?tab=cc1]

1. 設定ページから[新しいカレンダー][https://calendar.google.com/calendar/r/settings/createcalendar]を作成。
   - 既存のカレンダーにインポートする場合は不要
2. 設定ページの[インポート/エクスポート][https://calendar.google.com/calendar/r/settings/export]で、PCからcsvファイルと追加するカレンダーを選択してインポート。



### iCloudのカレンダー

1. Macでicsファイルを（ダブルクリックして）カレンダーアプリで開く。
2. インポートするカレンダーを選択。



## メモ

- icsファイルの生成
  - csvファイルをGoogle Calendarにインポートして、[設定] > [マイカレンダーの設定] からインポートしたカレンダーを選択
  - [カレンダーをエクスポート] をクリックしてzipファイルをDL
  - 解凍すればicsファイルが出てくる。

- csvファイルの生成
  - [学年暦][http://www.ritsumei.ac.jp/profile/info/calendar/]をブラウザで開いて、ドラッグ and コピー（！？）
  - エクセル（ゴミアプリ）に貼り付けて **手動で** 調整（！？）
    - Google Calendarの形式（ソース参照）に従う。
    - 日付の部分はソースにおいてあるxlsxファイルを参考に。
  - 別ファイルに貼り付けてcsvで保存。

