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

<img src="https://github.com/takashicompany/dogtag/blob/master/images/04.jpg?raw=true" width="600px">

## 必要な部品

### キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|ダイオード（リードタイプ)|9||
|m2スペーサー(3.5mm)|5||
|m2ネジ(3mm)|10||
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
|ロータリーエンコーダ|1|親指に近いキーにロータリーエンコーダを取り付けることができます。
|LED(WS2812B)|3|アンダーグロウライトとしてキーボードの底面を光らせることができます。|

## 組み立て方

以下の組み立て方は左手用になります。
右手側の場合は基板を裏返して組み立ててください。

### 1. トッププレートとPCBを切り離す

トッププレートとPCBが結合しているので、これを切り離します。  
(場合によっては切り離し済みのケースがあります。)  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8835.jpg?raw=true" width="600px">

基板を接続部の折れ線に沿って曲げると切り離せます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8838.jpg?raw=true" width="600px">

残った接続部分はペンチなどで折ると取りやすいです。  
折った場所をヤスリがけすると仕上がりがキレイになります。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8840.jpg?raw=true" width="600px">

### 2. ダイオードをはんだ付けする  

ダイオードを取り付けます。  
余談ですが、ダイオードは電流の向きを制御する役割があります。  
自作キーボードでは主にキーが同時に押されたことを検知する役割があります。  
以上のことは知らなくても当キーボードは完成させられますのでご安心ください🙏  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8846.jpg?raw=true" width="600px">

ダイオードが基板のはんだ付け穴に入るように足を曲げます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8847.jpg?raw=true" width="600px">

ダイオードをはんだ付け穴に挿します。  
ダイオードの端の黒い線が、基板の矢印(|◁)側になるようにPCBに挿します。
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8850.jpg?raw=true" width="600px">

はんだ付けをするために基板を反対側にします。  
この時、ダイオードの足を少し開くとPCBから抜けづらくなります。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8851.jpg?raw=true" width="600px">

はんだ付けを行います。  
はんだ付けがはじめての方は[こちら](https://www.youtube.com/watch?v=iCJXT3d4140)の動画を参考に進めるとスムーズに行くかと思います。  
(難しそうなイメージがありますが、要はくっついていれば良いのです)

はんだ付けが済んだら、ニッパーで足を切ります。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8853.jpg?raw=true" width="600px">

合計9箇所をはんだ付けします。  
**ダイオードの向きが写真と異なっていないかを確認してください。**
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8855.jpg?raw=true" width="600px">

### 3. リセットスイッチの取り付け

リセットスイッチはファームウェアを書き込む際などに使用します。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8856.jpg?raw=true" width="600px">

取り付け位置はキーボードの手前の「RESET」の印刷がされている箇所です。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8857.jpg?raw=true" width="600px">

穴にリセットスイッチの足を挿し込みます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8859.jpg?raw=true" width="600px">

基板をひっくり返してリセットスイッチの足が穴から出ていることを確認します。   
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8860.jpg?raw=true" width="600px">

はんだ付けを行います。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8861.jpg?raw=true" width="600px">

はんだ付けを済ませたらニッパーなどではんだ付け部分を切り取り、可能な限り平らにするとキーボードが安定しやすくなります。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8862.jpg?raw=true" width="600px">

### 4. TRRSソケットの取り付け

TRRSソケットは、分割キーボードとして利用する場合にキーボード同士を繋げるために使います。  
単体で使う場合は使用しませんが、気が変わって両手分欲しくなっても良いように取り付けましょう笑  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8863.jpg?raw=true" width="600px">

取り付け位置は、基板手前側の「TRRS」と印刷されている箇所です。
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8864.jpg?raw=true" width="600px">

穴に沿って挿し込みます。  
いくつか穴が余ってしまうのは、右手側で利用する際の穴です。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8865.jpg?raw=true" width="600px">

はんだ付けの際にひっくり返す時にTRRSソケットが抜けてしまう場合は、マスキングテープなどで固定すると良いです。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8866.jpg?raw=true" width="600px">

ひっくり返して、リセットスイッチと同様にはんだ付けを行います。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8867.jpg?raw=true" width="600px">

### 5. トッププレートの取り付け  

トッププレートを取り付けます。  
**取り付けるPro Microによっては、トッププレートと干渉してしまう場合があるので、必要に応じてヤスリなどで削るとスムーズに取り付けられるかと思います。**  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8868.jpg?raw=true" width="600px">

取り付けにはネジとスペーサーを使用します。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8871.jpg?raw=true" width="600px">

赤丸の位置に、スペーサーをネジで固定します。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8873b.jpg?raw=true" width="600px">

このように5箇所にスペーサーを取り付けます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8874.jpg?raw=true" width="600px">

最後にトッププレートを取り付けます。  
スペーサーとトッププレートをネジで固定します。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8876.jpg?raw=true" width="600px">

### 6. Pro Microの取り付け。

Pro Microはキーボードの頭脳となる部分です。  
キースイッチが押されたことを検知して、PCにキーの入力を伝えます。  
Pro MicroをPCBに固定する際は[コンスル](https://shop.yushakobo.jp/products/31)ーという部品を用いるのがオススメです。  
コンスルーを使うと、Pro Microを基板から楽に取り外せるので、メンテナンスがしやすかったり、他の自作キーボードに使い回すことが容易になります。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8879.jpg?raw=true" width="600px">

[コンスルーがはんだ付けされたものが遊舎工房さんで販売されている](https://shop.yushakobo.jp/products/a0500ph?variant=37665498497185)ので、難しそう…と感じた方は購入するのもアリだと思います。

Pro Microにコンスルーを挿します。  
左手側の場合はPro Microのチップなどが配置されている側が裏になるようにしてください。  
(右手側の場合は逆にチップ側が表になるようにしてください。)  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8880.jpg?raw=true" width="600px">

コンスルーでPro MicroとPCBを接続します。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8883.jpg?raw=true" width="600px">

Pro Microをはんだ付けします。  
トッププレートとPro Microがぶつかってしまうことがあるので、正しく挿されているか側面から確認するとミスを避けられます。 
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8885.jpg?raw=true" width="600px">

全ての端子をはんだ付けできたら完了です。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8886.jpg?raw=true" width="600px">


### 7. キースイッチのはんだ付け

キースイッチを取り付けます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8887.jpg?raw=true" width="600px">

キースイッチの取り付け方は2種類あります。

#### a. キースイッチを直にはんだ付けする場合

キースイッチをトッププレートに挿し込みます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8889.jpg?raw=true" width="600px">

キースイッチの足がはんだ付け穴(周りが銀箔になっている)から出ていることを確認します。　　
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8890.jpg?raw=true" width="600px">

キースイッチの足をはんだ付けします。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8891.jpg?raw=true" width="600px">

#### b. MXソケットを使う場合  

MXソケットをPCBにはんだ付けし、キースイッチをMXソケットで固定する方式です。  
手間が増えますが、キースイッチを付け替えられることがメリットです。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8894.jpg?raw=true" width="600px">

MXソケットのプリントのうち片方のはんだ付け箇所に事前にはんだを載せておきます。(予備ハンダというそうです。)  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8896.jpg?raw=true" width="600px">

MXソケットをピンセットで抑えながら、予備ハンダを溶かしながらMXソケットの片方をはんだ付けします。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8897.jpg?raw=true" width="600px">

もう一方のはんだ付け箇所もはんだ付けして完了です。  
表面からキースイッチをMXソケットに挿し込みます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8898.jpg?raw=true" width="600px">

9箇所にキースイッチを挿し込めば完了です。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8900.jpg?raw=true" width="600px">

### 8. ゴム足を付ける

ゴム足をつけて完成です。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8902.jpg?raw=true" width="600px">

底面に取り付けます。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/build/IMG_8903.jpg?raw=true" width="600px">

### 9. キーキャップを取り付ける

最後にキーキャップを取り付けて完成です。  
<img src="https://github.com/takashicompany/dogtag/blob/master/images/05.jpg?raw=true" width="600px">

### 10. ファームウェアの書き込み

ファームウェアは[Remap](https://remap-keys.app/catalog/1vSyBflE9L18u1AavBH4/firmware)から書き込めます。  
キーボードをPCに接続し、GoogleChromeで上述したサイトを開き「Flash」をクリックするとファームウェアの書き込みが始まります。  
![image](https://user-images.githubusercontent.com/4215759/143573907-80bfd6d5-ab7e-43f7-891c-7e50e6fe353c.png)

Remapでのキーマップの書き換え方は[こちら](https://salicylic-acid3.hatenablog.com/entry/remap-manual)。

QMKへのプルリクエストは下記になります。
https://github.com/qmk/qmk_firmware/pull/15259

### 11. 自慢する
完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。  
Twitterのハッシュタグは`#DogTag_KBD`を付けていただけば幸いです。  
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！  

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければと思います！
