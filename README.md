#関数Scroller_8x16Dot_Replace2 が抜けていました。大変失礼しました。再アップしました。
# OLED_SSD1351bv2
Arduino IDE library for operating the Adafruit OLED(SSD1351) in ESP-WROOM-02(ESP8266).  
Beta ver2.0

これはAdafruit社製 16bit フルカラー有機EL SSD1351 用のライブラリです。  
日本語の16x16ドットフォントを表示させるクラスもあります。

# Change log (更新履歴)
[Beta ver 2.0]  
他のバージョンとの競合を避けるため、別の名前に変更しました。  
レジスタダイレクトアクセスのピン設定で、他のピンに影響を与えないようにしました。  

[Beta ver 1.53]  
SPI通信を高速化しました。  
表示速度が２～３倍速くなりました。  

[Beta ver 1.40]  
以下のクラスを追加  
SSD1351_Init256 256kカラー（シリアル)で初期化  
SSD1351_BlackOut256 256kカラー（シリアル)で黒画面出力  
SSD1351_1pixel_DisplayOut256 256kカラー（シリアル)でピクセル出力  
  
[Beta ver 1.3]  
以下のクラス追加  
SSD1351_1pixel_DisplayOut 1ピクセル描画  
SSD1351_lineH 水平ライン描画  
SSD1351_lineV 垂直ライン描画  
SSD1351_RectLine 四角の線描画
SSD1351_RectFill 四角形塗りつぶし描画  
その他細かいバグ修正

[Beta ver 1.1]  
電光掲示板風にスクロールする、Scroller_8x16Dot_Replaceクラスを変更しました。

# Credits and license
License MIT [Modified person is Mgo-tec.]

Original License is BSD [Copyright (c) 2012, Adafruit Industries]

詳しくはブログ参照：

https://www.mgo-tec.com
