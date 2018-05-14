Chatworkコミュニケーションクラス
====

Chatworkとのメッセージ交換を行います。

## Description
  OpenCVで画像や動画を使って、システムを作ってみる。
  目標
  １．お店で客層とカウントをする（いつ、どんなお客さま/性別、年代が何人来られたか）
  ２．メンバーが来店した場合にはアラートする（アテンション、情報表示）
  3.メンバー登録時に、顔の画像も登録する
  4.お客さまがどのゾーンに何名、どれくらいの時間いたかを記録
  5.AWS,LEXサンプル作成

## 依存関係
  ke-utilityを基底としています。

## 使い方

### インストール方法
  npm install ke-chatowrk
  npm install

### クラスリファレンス
  |メソッド|解説|
  |:-|:-|
  |Construct|(token)トークンを渡してオブジェクトを作成します|
  |getRoom|()ルームリストの取得をします。|
  |pushMessage|(message, room)メッセージとルームを指定して送信します。|


### Sample

  ~~~javascript
  const keChatwork=require('ke-chatwork');
  const Cw=new keChatwork();
  Cw.pushMessage('test', 'MyRoom');
  ~~~


## ライセンス

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## 作成者

[m0kimura](https://github.com/m0kimura)
[サイト](http://www.kmrweb.net/)
