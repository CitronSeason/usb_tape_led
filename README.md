# usb_tape_led

## Target Device

- STM32F446
- NUCLEO-F446ZE

## Description

このプロジェクトは、STM32F446マイクロコントローラーを使用してLEDテープを制御するためのファームウェアです。
PCに接続し、テープLEDを制御するためのUSBインターフェースを提供します。
テープLEDは、DMX512互換の制御方式が採用されている WS2812B や SK6812 など LEDが組み込まれた柔軟なストリップライトを想定しています。

## TODO
- [ ] PWMペリフェラルを使用したLED制御の実装
- [ ] DMA転送によるDMX512互換のPWM信号の生成
- [ ] USB通信（受信）機能の実装
- [ ] USB EndPointの構成

