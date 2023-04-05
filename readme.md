# ASUS ROG Z370F Hackintosh EFI

关于我发布的EFI，您需要知道：

## ❗️在您使用此EFI后，记得使用OpenCore Configurator刷写三码！
## ❗️所有操作都在您可控范围内执行，若出现错误及任何软硬件损坏本人概不负责！

## 配置信息：

我的配置是根据黑苹果较为完善的进行选取搭配
| Hackintosh | 配置单 |
|---|---|
|  CPU | Intel i7 9850HK（理论上所有8、9代CPU即coffee lake架构都可使用） |
|  GPU | POWERCOLOR RX5600XT 6G|
|  主板 | ASUS ROG Z370F（Z370芯片组） |
|  内存 | CUSO 2666Mhz 8G X2 |
|  机型 | iMac Pro 2017 |
| Wifi | Broadcom 94360CD|

## No Working ❌

* 麦克风（我未外置购买麦克风，无法测试）
* 如有更多需要，你可以进行反馈和联系我。

## Bios 设置
* Advanced • CPU Configuration • CFG Lock = Disabled
* Advanced • Chipset Configuration • Above 4G Decoding = Disabled | or Enabled
* Advanced • Chipset Configuration • IGPU Multi-Monitor = Disabled
* Advanced • USB Configuration • XHCI Hand-off = Enabled
* Security • Secure Boot = Disabled

## 截图预览
<img width="2048" alt="截屏2023-04-05 13 20 55" src="https://user-images.githubusercontent.com/91834755/229987997-2150c3d5-380b-4c3d-aaf1-59a3fcfe3903.png">




## 更新日志
V1.0 2023-4-5
更新OpenCore 0.9.1
