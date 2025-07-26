# name
Web Serial

![screenShot](https://github.com/user-attachments/assets/dc817ad6-daa9-4637-aaeb-af7245bc9344)

## Overview
Web Serial APIを使ったシリアル通信テスト

## Requirement
Google Chrome、Microsoft edge

注意：古いバージョンなど Web Serial API が動作しない場合には使用できません。

## Usage
ブラウザで Web_Serial_API.html を開いて通信設定を入力後に Openボタン でデバイスを選択してください。

文字データを入力し sendボタン を押すと送信します。ヘッダ文字とターミネータ文字を選択できます。

バイナリデータを送信する場合は、16進数文字列を入力し sendByteボタン を押します。

受信データは都度表示をされます。

## Features
受信データが分断されて表示される場合は、タイムアウト値を長めに設定してください。

送受信データは下段テキストボックスに16進数のバイナリデータとして表示します。

文字エンコードは、UTF-8とSJISに対応しています。

## Author
シリアル通信をブラウザで気軽にテストできます。

マイコン開発、情報機器、産業ロボットなどの動作確認にて活用ください。

## Licence
The source code is licensed MIT. The website content is licensed CC BY 4.0,see LICENSE.
