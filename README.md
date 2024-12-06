# HAT Flipper for WIZnet Ethernet HAT

WIZnet Ethernet HATの向きを180度回転させて、PicoのMicroUSBコネクターとRJ-45の口の向きを揃えるためのアダプターボードです。また、Ethernet HAT配線をSPI0からSPI1に変更して、被りがちなピン配置を回避します。

おまけとして、Picoのリセットボタン用回路を実装しています。TSB001タクタイルスイッチを使用して実装可能です。

| 役割 | EthernetHAT(SPI0) | 変換基板(SPI1) |
| ---- | ----------------- | -------------- |
| MISO | GP16              | GP12           |
| CSn  | GP17              | GP9            |
| SCLK | GP18              | GP10           |
| MOSI | GP19              | GP11           |
| RSTn | GP20              | GP15           |
| INTn | GP21              | GP14           |

## 解説

https://akkiesoft.hatenablog.jp/entry/20240819/1724048755

## License

MIT License

2024 @Akkiesoft
