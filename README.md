# DogTag

![dogtag](https://github.com/takashicompany/dogtag/blob/master/images/qmk.jpg?raw=true)

DogTagは9キーのコンパクトなマクロパッドです。  
100mm x 100mm 以内のPCBから組み立てます。  
リバーシブルに対応しており、2台をTRRSケーブルで接続することで分割型のマクロパッドとしても使用できます。  
その他にもロータリーエンコーダの搭載やMXソケットによるキースイッチの付け替え(ホットスワップ)も可能です。  
LEDによるアンダーグロウも可能です。  

DogTag is a compact macro pad with 9 keys.  
It is assembled from a PCB no larger than 100mm x 100mm.  
It is reversible and can be used as a split macro pad by connecting two units with a TRRS cable.  
Other features include a rotary encoder and MX sockets for hot-swapping of keyswitches.  
LED underglow is also available.  

## 必要な部品

### キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|ダイオード（リードタイプ)|9||
|m2スペーサー(3.5mm)|5||
|m2ネジ(3mm)|5||
|m2ネジ(4mm)|5||
|リセットスイッチ|1||
|TRRSソケット|1||
|滑り止めシール|4||

### 別途用意するもの
|部品|個数|備考|
|:--|:--|:--|
|キースイッチ|9|Cherry MX互換のもの。|
|キーキャップ|9|全て1u。Chery MX互換のもの。|
|Pro Micro|1||
|USBケーブル|1|Pro MicroとPCを接続します。|

### オプション
|部品|個数|備考|
|:--|:--|:--|
|コンスルー|2|Pro Microに取り付けます。|
|MXソケット|9|キースイッチの付け替えが可能になります。|
|ロータリーエンコーダ|1||
|LED(WS2812B)|3|アンダーグロウライトとしてキーボードの底面を光らせることができます。|

## 組み立て方

### 1. トッププレートとPCBを切り離す

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8835.jpg?raw=true" width="600px">

切り離す  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8838.jpg?raw=true" width="600px">

必要に応じてヤスリがけをする  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8840.jpg?raw=true" width="600px">

### 2. ダイオードをはんだ付けする  

ダイオードの向きを確認  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8846.jpg?raw=true" width="600px">

ダイオードの足を曲げる  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8847.jpg?raw=true" width="600px">

ダイオードをはんだ付け穴に挿す  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8850.jpg?raw=true" width="600px">

基板をひっくり返す  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8851.jpg?raw=true" width="600px">

はんだ付けを行う  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8853.jpg?raw=true" width="600px">

９箇所をはんだ付けする  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8855.jpg?raw=true" width="600px">

### 3. リセットスイッチの取り付け

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8856.jpg?raw=true" width="600px">

取り付け位置を確認する  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8857.jpg?raw=true" width="600px">

リセットスイッチを挿し込む  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8859.jpg?raw=true" width="600px">

基板をひっくり返す  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8860.jpg?raw=true" width="600px">

はんだ付けをする  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8861.jpg?raw=true" width="600px">

平らにする  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8862.jpg?raw=true" width="600px">

### 4. TRRSソケットの取り付け

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8863.jpg?raw=true" width="600px">

取り付け位置を確認する  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8864.jpg?raw=true" width="600px">

取り付ける  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8865.jpg?raw=true" width="600px">

マスキングテープなどで貼り付ける  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8866.jpg?raw=true" width="600px">

ひっくり返してはんだ付けを行う  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8867.jpg?raw=true" width="600px">

### 5. トッププレートの取り付け
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8868.jpg?raw=true" width="600px">

ネジとスペーサー  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8871.jpg?raw=true" width="600px">

赤丸の位置に挿す  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8873.jpg?raw=true" width="600px">

ネジで止める  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8874.jpg?raw=true" width="600px">

トッププレートを取り付けてネジで止める  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8876.jpg?raw=true" width="600px">

### 6. Pro Micro

コンスルーとPro Micro　　
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8879.jpg?raw=true" width="600px">

Pro Microにコンスルーを挿す　　
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8880.jpg?raw=true" width="600px">

コンスルーでPro MicroとPCBをつなげる  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8883.jpg?raw=true" width="600px">

はんだ付けを行う  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8885.jpg?raw=true" width="600px">

もう片方も  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8886.jpg?raw=true" width="600px">

### 7. キースイッチのはんだ付け
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8887.jpg?raw=true" width="600px">

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8889.jpg?raw=true" width="600px">

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8890.jpg?raw=true" width="600px">

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8891jpg?raw=true" width="600px">

MXソケットを使う場合  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8894.jpg?raw=true" width="600px">
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8896.jpg?raw=true" width="600px">

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8897.jpg?raw=true" width="600px">

<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8898.jpg?raw=true" width="600px">


<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8900.jpg?raw=true" width="600px">

### 8. ゴム足を付ける
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8902.jpg?raw=true" width="600px">
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8903.jpg?raw=true" width="600px">
