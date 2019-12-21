# AEBLE_Dock

![基板写真](./image/board.jpg)

秋月電子で販売しているBLEモジュール[AE-TYBLE16](http://akizukidenshi.com/catalog/g/gK-12339/)を、J-LINKでデバッグしやすくする基板です。

## 特長

- SWD経由のデバッグ・ファームウェア書き込みが可能
- J-LINKからの5V供給をサポート

## 使い方

1. 各部品を実装する。
1. ICソケットに、ピンヘッダをはんだづけしたAE-TYBLE16を差し込む。アンテナ部が基板の外に出る方向に差し込む。
1. CN1またはCN2にJ-LINKを接続する。
1. J-LINKをPCに接続する。

CN2を使ってデバッグする際は、AE-TYBLE16に電源の供給が必要です。CN1のピンから5Vを入力するか、J2 3番ピンに3.3Vを入力してください。

## 作り方

## 資料

- [部品表](https://docs.google.com/spreadsheets/d/1xVUbobURHwBgAgbBJVKqeSEPdVH2p0qffykU0qcphyc/edit?usp=sharing)
- [回路図](./schematic.pdf)
- [ガーバー](./Gerber)
