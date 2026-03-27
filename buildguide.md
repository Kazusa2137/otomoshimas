# Build Guide
こちらは自作キーボードキット otomoshimas のビルドガイドになります。

This build guide is Japanese If you do not understand Japanese, please refer to the video build guide. 

## はじめに
この度は、「otomoshimas」をお買い上げいただきまして誠にありがとうございます。

この製品はNintendoSwitch2のケースに入る様に作られた自作キーボードキットです。

ファームウェアについては、VIA Custom UI for Vial を用いてカスタマイズする事が出来ます。

本製品は組み立てが必要なキットです。

組立工程の中には、ハンダ付けや細いねじを締める工程があります。
あらかじめ必要な工具（後述）を用意した上で、組立を始めてください。

キット内容物の不足や不明点等ありましたら、以下連絡先のご連絡ください。

mail: heshajingping@gmail.com

![otomoshimas](https://github.com/Kazusa2137/otomoshimas/blob/main/image/DSC00811.jpg)

## Parts

### キット内容物

キット内容物は以下のようになっています。

| 部品名                 | 個数 | 詳細                                                   |
|:---------------------|:-----------|:----------------------------------------------------------|
| PCB(ミドルプレート)                  | 1   |                                                           |
| スイッチプレート             | 1   |                                                           |
| ボトムプレート         | 1  |                                               |
| スルーホールダイオード         | 40 |        | 
| ホットスワップ（CherryMX用）         | 48以上 | 予備を入れています。基本的に50個程度同封されています。 |
| リセットスイッチ             | 1      | タクタイルスイッチ - 2pin 3.5x6x4.3mm |
| 六角スペーサーM2 11mm         | 6       |                                                           |                                                         |
| M2小ネジ 4 mm          | 12以上| 予備を入れています。基本的に14個程度同封されています。 |
| ゴム足          | 4以上 | 予備を入れています。基本的に6個程度同封されています。 |
| Promicro          | 1 |  |

### 別途用意する物


| 部品名                 | 必要個数   |  主な購入先                          | 補足 |
|:---------------------|:--------|:----------------------------------|:-----------------------------------------------|
| コンスルー(必要であれば)| 2   | https://shop.yushakobo.jp/products/31?variant=37665714438305 |**高さ2.5mm** の 12ピン or 13ピン         | 
| キースイッチ         |  48  | 遊舎工房等、お好みの物 |Cherry MX である事。(ロープロファイル不可)                                              | 
| キーキャップ         | 1U×48  |  遊舎工房等、お好みの物  |  |
|  microBケーブル        | 1  |  データ通信が可能なもの  |  |

### 必要な工具等
| 名前                 | 補足                                                   |
|:---------------------|:----------------------------------------------------------|
| はんだごて | はんだ付けを行うのに必要です。 |
| はんだ     | はんだ付けを行うのに必要です。|
| ニッパー    | 部品の足を切るのに使用します。                  |
| ＋ドライバ | ネジを止める際に使用します。 |
| （はんだ吸い取り線）   | はんだ付けを外す際に使用します。失敗しなければ必要ありませんが、用意をオススメします。  |


## 組み立て

### 初心者の方へ

取り付ける部品にはミドルプレートの付ける面に印が付いています。

基板のどちらの面にはんだ付けしたら良いか分からない時は、基板上に書かれた部品のマークを確認しましょう。

### ダイオードを取り付ける

まず、ダイオードの足を曲げ、取り付けます。

取り付ける場所は、裏面に書かれている D1 ~ D5 の場所です。

**ダイオードには向きがあり** 、黒く塗られた向きを示す線が入っています。

この線を、基板の四角のマークに合わせます。

![diode](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7237.jpg)


はんだ付け出来たら、はみ出ている足をニッパーで切ります。

![nipper](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7245.jpg)

### ホットスワップを取り付ける
次にホットスワップを取り付けましょう。ホットスワップは表面に取り付ける形になりますので、先に盛りはんだをすると取り付けやすいです↓

![hotswap_morihanda](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7250.jpg)

盛りはんだをした後、ホットスワップを取り付けます。

![hotswap](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7251.jpg)

### 途中経過
![totyu](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7252.jpg)

### リセットスイッチを取り付ける

![resetswitch](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7253.jpg)

リセットスイッチをはんだ付けします。この部品に向きはありません。


### キースイッチを取り付ける
まず、スイッチプレートとPCBミドルプレートを重ねてキーをはめ込みます。

スイッチプレートにはめ込む時から、基板の穴を見て、向きに注意してください。

四角→外周→中の順にはめ込むとやりやすいと思います。

![switchplate](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7254.jpg)
![switchplate](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7255.jpg)
![switchplate](https://github.com/Kazusa2137/otomoshimas/blob/main/image/IMG_7256.jpg)

このキットはホットスワップなので、あとでスイッチを取り替えることができます。


### Promicro
コンスルーを画像のように、金の点の部分がBLE側になるような向きで差し込みます。

BLEへコンスルーの取り付けが出来たら、そのまま基盤にも差し込みましょう。

※12ピンのコンスルーを使っている方は、USBポート側に寄せて使ってください。

![BLE](https://github.com/uruzunyaa/kazu-laser/blob/main/image/BLE.jpg)

差し込んだら、BLE Micropro側のみはんだ付けします。 (はんだ付けしなくても動作しますが、BLEを外したくなった時、上手く外す事が出来ません。)

### 動作確認等
組み立ては後ネジを取り付ければ完了です。ネジを取り付ける前に、動作確認を行いましょう。

まず、電池を入れる前に、部品の向きを確認してください。

向きに注意が必要な部品は以下の4つです。

- ダイオード(黒い部分と四角が一致しているか)
- コンデンサ(塗装が白くなっている部分が **－** )
- DCDCコンバーター(丸みを帯びた部分が基板の外側を向いているか)
- レーザーモジュール(赤が **＋** 黒が **－** となっているか)
- 電池ホルダー(2つとも右側にバネが付いているか)

これらの部品の向きを間違えた状態で電源を入れてしまうと、部品の故障したり、**最悪の場合発火します。**

確認出来たら、電池を入れ、レーザーポインタが付くか確認します。

その後、ファームウェアを書き込み、ネジを閉めたら完成です。

## ファームウェアの書き込み
ここからはファームウェアの書き込みを行います。

### BLE Micro proの設定
まず、BLE Micropro本体を、kazu-laserであると認識させるための設定を行います。

ここは動画版に設定デモがあるので、分かりにくい場合は動画版もご参照ください。
[https://www.youtube.com/watch?v=zEUvSC2t4i8](https://youtu.be/zEUvSC2t4i8?si=E2XbTMDPBJJxyKCP&t=545)

BLEと有線接続をした状態で、以下サイトにアクセスしてください。

https://sekigon-gonnoc.github.io/BLE-Micro-Pro-WebConfigurator/

### ブートローダーのアップデート
Update Bootloaderのタブをクリックします。

ble_micro_pro_bootloader_1_3_2を選択し、アップデートを行います。

### アプリケーションアップデート
Update Applicationのタブへ移動します。

ble_micro_pro_vial_1_3_6を選択し、アップデートします。

### キーボードの設定
Edit configのタブへ移動します。

Select keyboardの中から、 ble_micro_pro を選択します。

### kazu-laserの設定を書き込む
以下のファイルをダウンロードし、BLEMicropro のストレージ直下にアップロードしてください。

https://github.com/uruzunyaa/kazu-laser/blob/main/kazu_laser_config.bin

アップロード完了後、USB接続を一度解除し、再度接続する事で、設定が完了します。

### キーマップの設定
キーマップの設定を行います。以下サイトにアクセスし、キーボードを選択し接続します。

https://sekigon-gonnoc.github.io/via-custom-ui-for-vial/

UP SETTING から以下のデフォルトキーマップをアップロードするか、Keymapをクリックし、手動で編集を行ってください。

デフォルトキーマップは以下のようになっています。

![Keymap](https://github.com/uruzunyaa/kazu-laser/blob/main/image/defalt%20keymap.png)

使用ソフトに合わせてご使用ください。

- Googleスライド用
https://github.com/uruzunyaa/kazu-laser/blob/main/kazu_laser-vial-setting-GoogleSlide.json

- PowerPoint用
https://github.com/uruzunyaa/kazu-laser/blob/main/kazu_laser-vial-setting-PowerPoint.json

- KeyNote用(Mac)
https://github.com/uruzunyaa/kazu-laser/blob/main/kazu_laser-vial-setting-KeyNote.json

### 動作確認
USB接続を解除し、ペアリングを行います。

電源をONにした状態にすると、PC側からBluetoothの欄にKazu-laserが出てくるはずです。

![Bluetooth](https://github.com/uruzunyaa/kazu-laser/blob/main/image/Bluetooth.png)

接続後、正常に動作するか確認してください。

ペアリング後からは、キーマップの編集が無線でも行えます。

### ネジの取り付け
動作確認が完了したら、ネジを取り付け、ボトムプレートを閉じましょう。

## 完成！！
組み立てお疲れ様でした！

ぜひ、発表等を行う際にご活用し、良き自作キーボードライフをお過ごしください！

![Bluetooth](https://github.com/uruzunyaa/kazu-laser/blob/main/image/DoneBuild2.jpg)
