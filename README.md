# 4d-tips-picture-conversion

PICTピクチャの変換ツール

### [PICT_Convert by JPR](https://github.com/4D-JP/4d-tips-picture-conversion/releases/tag/1.0)

<img width="918" alt="2018-03-29 11 58 37" src="https://user-images.githubusercontent.com/10509075/38067652-896ffb64-3348-11e8-9804-3ef7548653cf.png">

### 使い方

古い形式（``QuickDraw (PICT)``, ``QuickTime``）ライブラリピクチャ・ピクチャリソース・スタティックピクチャの変換を支援するツールです。

``Components``フォルダーにインストールし，32ビット版でストラクチャを開いて，``HTP_DoIt``メソッドを実行します。詳細はPDFドキュメント（英文）を参照してください。

---

### simple converter by miyako

### 使い方

[変換SOAPサーバー](https://github.com/4D-JP/4d-tips-picture-conversion/releases/tag/1.2)を32ビット版で起動します。デフォルトの設定はポート番号``80``です。

[変換SOAPクライアント](https://github.com/4D-JP/4d-tips-picture-conversion/releases/tag/1.1)を起動します。リソースピクチャを使用していないのであれば，64ビット版でもOKです。リソースピクチャ（``RSR``ファイル）を使用している場合は32ビットで起動してください。

``FixIt``メソッドを実行すると，変換メソッドがインストールされます（コンポーネントではありません）。デフォルトのURLは``http://localhost/4DSOAP``です。

フォームのピクチャを一括修正するには``FIX_FORM``，ライブラリを一括修正するには``FIX_LIBRARY``を実行します。

ペーストされたスタティックピクチャーを変換することはできませんが，フォームエディターで「スタティックピクチャー」を適当に選択し，「タイプ」プロパティを「スタティックピクチャー」から「ライブラリピクチャー」に変更すれば，画像がピクチャライブラリに追加されますので，``FIX_LIBRARY``で修正することができます。

リソースファイルを変換した場合，フォームエディターでソースを「リソースファイル」から「ピクチャライブラリ」に変更してください。
