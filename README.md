# SDU-m5stack-avatar-mic
SD-Updaterに対応した m5stack-avatar-mic です。<br>

<br>
mongonta0716 さんのソフトから次の修正を行いました。<br>
- SD-Updater対応。<br>
- BtnB 押下で画面の上限反転（トグル）機能を追加<br>

<br>
ブート時に、SD_Updater用の画面が立ち上がります。<br>
SDに入れたソフトを切り替えることができるようになります。<br>
<br>



## ボタンの機能
・<b>BtnA-Pressed</b>: 画面の顔の背景色が変わります。<br>
・<b>BtnA-DoubleClicked</b>:　逆さ画面<br>
・<b>BtnB-Pressed</b>： 上下反転(トグル)<br>
<br>
<br>


## 必要なもの
### 本体<br>
いずれかを用意してください。<br>
・M5Stack Core2 for AWS<br>
・M5Stack Core2 <br>
・M5Stack Core2 v1.1　（未確認）<br>
<br>

### SDカード
<br>


## 最新BINの取得
コンパイル済みの最新BINファイルは、下記のリポジトリから取得できます。
- [BinsPack-for-StackChan-Core2](https://github.com/NoRi-230401/BinsPack-for-StackChan-Core2)<br>
<br>


## SD-Updaterについて
tobozoさん開発。SDに複数のBINファイルを入れて、ソフトを切替えて使用できるようになります。<br>

 https://github.com/tobozo/M5Stack-SD-Updater<br><br>


タカオさん、2023/7/29 ｽﾀｯｸﾁｬﾝ お誕生日会 2023のLTで、M5Stack-SD-Updaterの概要を説明した時のスライド<br>
https://speakerdeck.com/mongonta0716/sutatukutiyandefu-shu-apuriwoqie-riti-erutekunituku

<br><br>


## 基のリポジトリ
- [m5stack-avatar-mic　(mongonta0716さん)](https://github.com/mongonta0716/m5stack-avatar-mic)<br>
<br>
<br><br>

ここから、基のソフトの説明書です。

-----




# m5stack-avatar-mic
マイクを使ったM5Stack Avatarの例です。
音に合わせてAvatarが口パクしたり、傾いたりします。

# 対応デバイス

- M5Stack Core2/Core2 V1.1/AWS
- M5StickC
- M5StickCPlus
- ATOMS3 + PDMUnit
- M5Stack CoreS3
- M5Stack CoreS3SE
- M5Stack Fire
- M5Dial + PDMUnit(Port.A)

# 環境

・VSCode + PlatformIO

ArduinoIDEの場合は下記のように名前を変更してください。
- srcフォルダ -> m5stack-avatar-mic
- main.cpp -> m5stack-avatar-mic.ino

# 動作確認済みボード・ライブラリバーョン

詳細はplatformio.iniを見てください。

## ボード

- espressif 6.5.0

## ライブラリ
- M5Stack-Avatar v0.9.2
- M5Unified v0.1.16

# LICENSE
[MIT](https://github.com/mongonta0716/m5stack-avatar-mic/blob/main/LICENSE)

# Author

[Takao Akaki](https://github.com/mongonta0716)