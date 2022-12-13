# 102_ColorTFT

102 multi-channel analyzer prototype with TFT colored display.

![87ccd79d933e247fdd60486e2e4c18f](https://user-images.githubusercontent.com/26637782/207246660-da2a5398-a32a-47bd-a37f-095bc316858f.jpg)

## Pin Connection:
- #define TFT_MISO 19 // (leave TFT SDO disconnected if other SPI devices share MISO)
- #define TFT_MOSI 18
- #define TFT_SCLK 5
- #define TFT_CS    32  // Chip select control pin
- #define TFT_DC    27  // Data Command control pin
- #define TFT_RST   4  // Reset pin (could connect to RST pin)
