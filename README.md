# 惠普HP EliteDesk 800 G2 mini 黑苹果相关文件
## 简介 
这是惠普HP EliteDesk 800 G2 mini的黑苹果相关文件,这套配置我仅在macOS 10.15.4(macOS Catalina)上测试基本完美.

:warning: :warning: :warning: 

本项目提供的EFI并不能通用于所有惠普的mini主机,直接覆盖EFI分区可能导致无法启动等问题.
推荐了解clover和黑苹果驱动的相关知识后,参考config.plist和驱动修改自己的EFI文件,尤其是需要修改黑苹果三码部分,切勿直接盲目使用,如果因为直接共用我EFI文件中的三码导致apple ID被ban,本人概不负责!!!

有问题可以提issue,有时间我会尽可能的提供帮助.
## 本机硬件
- CPU: intel i5-6500T
- 内存: Crucial 8GB x 2
- 硬盘: 1. M.2 512G WD SSD; 2. SATA 512G Acer SSD
- 网卡/蓝牙: 添加BCM94352Z(DW1560)
- 显卡: HD530,无独显
## 用前准备
- BIOS版本: N21 Ver.02.44
- BIOS设置: 参照黑果小兵博客或者Tonymac x86的通用设置就可以,无需特殊设置
- Clover版本: macOS 10.15.4最低要求r5107
## 哪些可以用？
- [x] CPU变频
- [x] 显卡硬件加速(QE/CI)
- [x] 音频完美
- [x] DP 原生4k输出完美
- [x] USB3.0 USB2.0
- [x] WIFI/蓝牙(需更换网卡BCM94352Z后可以正常驱动,但我目前拿不到天线,无法做更多测试)
- [x] 睡眠和唤醒
## 等待修复的问题
- [] 睡眠和唤醒(仍在测试)
####

