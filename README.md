# EPD-nRF52-hema213

电子墨水屏固件，带有一个[网页版上位机](https://tsl0922.github.io/EPD-nRF5/)，可以通过蓝牙传输图像到墨水屏，也可以把墨水屏设置为日历模式（支持农历、节气、节假日调休显示）。

仅支持的主控芯片： nrf52811，支持的墨水屏驱动有`SSD1619`三色墨水屏），，支持蓝牙 OTA 固件升级。

## 支持设备

盒马2.13寸三色墨水屏价签

## 上位机

本项目自带一个基于浏览器蓝牙接口实现的网页版上位机，可使用手机或电脑打开下面地址使用，或者在本地直接双击打开 `html/index.html` 来使用。

- 地址：https://tsl0922.github.io/EPD-nRF5
- 演示：https://www.bilibili.com/video/BV1KWAVe1EKs
- 交流群: [1033086563](https://qm.qq.com/q/SckzhfDxuu) (点击链接加入群聊)

![](docs/images/0.jpg)

上位机支持多种图片抖动算法，且可以对图片进行涂鸦、添加文字。除了显示图片作为电子相框外，还可以切换到日历模式，显示月历、农历节气、节假日、放假调休等信息。

## 致谢

本项目使用或参考了以下项目的代码：

- [ZinggJM/GxEPD2](https://github.com/ZinggJM/GxEPD2)
- [waveshareteam/e-Paper](https://github.com/waveshareteam/e-Paper)
- [atc1441/ATC_TLSR_Paper](https://github.com/atc1441/ATC_TLSR_Paper)
