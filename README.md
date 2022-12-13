# 102_ColorTFT

102 multi-channel analyzer prototype with TFT colored display.

![5b8ffbd3953b4bff04636ca382a3659](https://user-images.githubusercontent.com/26637782/207245395-03256b1a-f074-4640-8f07-6ce0956785d7.jpg)

Pin Connection:
#define TFT_MISO 19 // (leave TFT SDO disconnected if other SPI devices share MISO)
#define TFT_MOSI 18
#define TFT_SCLK 5
#define TFT_CS    32  // Chip select control pin
#define TFT_DC    27  // Data Command control pin
#define TFT_RST   4  // Reset pin (could connect to RST pin)
