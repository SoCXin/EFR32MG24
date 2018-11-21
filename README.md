# [EFR32MG24](https://doc.soc.xin/EFR32MG24)

* [Silicon Labs](https://www.silabs.com/): [Cortex-M33](https://github.com/SoCXin/Cortex)
* [L2R3](https://github.com/SoCXin/Level): 78 MHz

## [简介](https://github.com/SoCXin/EFR32MG24/wiki)

[EFR32MG24](https://cn.silabs.com/wireless/zigbee/efr32mg24-series-2-socs) 是使用 Matter、OpenThread 和 Zigbee 协议实现网状物联网无线连接的理想选择，适用于智能家居、照明和楼宇自动化产品。

凭借高性能 2.4 GHz RF、低电流消耗、AI/ML 硬件加速器和 Secure Vault™ 等关键功能，物联网设备制造商可以创建智能、稳健、节能的产品，避免远程和本地网络攻击。ARM Cortex® -M33 运行高达 78 MHz、1.5 MB 的闪存和 256kB 的 RAM，可为要求苛刻的应用程序提供资源，同时为未来增长留出空间。

### 关键参数

* 78 MHz Cortex-M33 + DSP (50.9 µA/MHz)
* 256 KB SRAM + 1536 KB Flash
* 2.4GHz射频性能
    * -105.4 dBm 灵敏度（在 250 kbps OQPSK DSSS 条件下）
    * -105.7 dBm 灵敏度（在 125 Kbps GFSK 条件下）
    * -97.6 dBm 灵敏度 @ 1 Mbit/s GFSK
    * -94.8 dBm 灵敏度（在 2 Mbit/s GFSK 条件下）
    * 高达 19.5 dBm 的 TX 电源
* 超低功耗表现
    * 4.4 mA RX 电流（在 1 Mbps GFSK 条件下）
    * 5.1 mA RX 电流（在 250 kbps OQPSK DSSS 条件下）
    * 5 mA TX 电流（在 0 dBm 输出功率条件下）
    * 19.1 mA TX 电流（在 10 dBm 输出功率条件下）
    * 156.8 mA TX 电流（在 19.5 dBm 输出功率条件下）
    * 33.4 μA/MHz（活动模式 (EM0)，在 39.0 MHz 条件下）
    * 1.3 μA EM2 深度睡眠电流（16 kB RAM 保留并从 LFRCO 运行 RTC）
* IADC: 12 位 @ 1 Msps 或 16 位 @ 76.9 ksps, 部分 OPN 支持高速模式（高达 2 Msps）和高精度模式（16 ksps 时高达 3.8 位 ENOB）
* 2 × 模拟比较器 (ACMP)
* 2 × 数模转换器 (VDAC)


## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/EFR32MG24)

[EFR32MG24](https://github.com/SoCXin/EFR32MG24) 是涂鸦Thread模组 [TS24](https://developer.tuya.com/cn/docs/iot/TS24-U?id=Kbws8hvqbsffb) 系列的主控芯片。主要应用领域是 Matter over Thread


## [www.SoC.xin](http://www.SoC.Xin)
