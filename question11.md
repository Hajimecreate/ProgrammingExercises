# 練習問題11：座席予約システム

あなたは新しいバスの座席予約システムを作成しています。
各座席は0から始まる一意のIDを持っています。以下はシステムの仕様です。

1. バスには50席あります。
1. 予約済みの座席は1、未予約の座席は0で表されます。
1. ユーザーが座席の予約を試みると、その座席が未予約の場合は予約され、成功メッセージが表示されます。予約済みの場合は失敗メッセージが表示されます。

これをJavaScriptで実装してください。

## 1. 座席を表す配列の初期化
- バスの座席を表す配列を初期化し、全ての座席を未予約(0)に設定してください。

## 2. 座席の予約
- ユーザーが座席のIDを指定して予約を試みる関数を作成してください。
- 予約が成功した場合はメッセージを表示し、座席のステータスを予約済み(1)に更新してください。
- 予約が失敗した場合は対応するメッセージを表示してください。

:::success
メッセージを表示するライブラリは[iziToast](https://izitoast.marcelodolza.com/)がオススメです。
:::

## 3. 未予約の座席一覧表示
- 現在の未予約の座席の一覧を表示する関数を作成してください。

## 4. ユーザーによる座席の選択
- ユーザーが座席を選択できるようなインターフェースを作成してください。
- ユーザーが選択した座席の予約を試みる関数を呼び出してください。

## 5. 全座席の予約状況表示
- 全ての座席の予約状況を表示する関数を作成してください。
- 予約済みの場合は `予約済み`、未予約の場合は `未予約` などのメッセージを表示してください。

## 最終問題
完成したソースコードをテストサイトにアップしてください。
