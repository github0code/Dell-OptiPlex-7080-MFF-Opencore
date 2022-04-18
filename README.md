# Dell-OptiPlex-7080-MFF-Opencore
OpenCore for macOS Monterey (12.3.1) on Dell OptiPlex 7080 MFF

# 基本配置：

&ensp;&ensp;处理器：Intel Comet Lake I7-10700T

&ensp;&ensp;芯片组：Intel Q470

&ensp;&ensp;内存：16G DDR4 3200 8G * 2

&ensp;&ensp;显卡：Intel UHD 630

&ensp;&ensp;声卡：ALC256 (内置扬声器+耳麦一体+音频输出)

&ensp;&ensp;网卡：Intel I219-LM7

&ensp;&ensp;无线网卡/蓝牙：博通 BCM94360Z3

&ensp;&ensp;硬盘:  WD SN730 M.2 256G

# 正常工作：

1. 变频 HWP

2. 睡眠

3. 显卡，支持4K/60Hz, HiDPI

4. 有线网卡

5. 无线网卡和蓝牙，支持隔空投送，接力，通用控制

6. 声卡

7. DP音频输出，双屏4K输出

8. USB, 已定制

9. 重启关机正常

# BIOS设置：

| 设置项     | 值 |
| ----------- | ----------- |
| System Configuration → Integrated NIC      | Enabled       |
| System Configuration → SATA Operation   | AHCI        |
| Security → PTT Security/PTT On     | Disabled       |
| Secure Boot → Secure Boot Enable   | Disabled        |
| Secure Boot → Secure Boot Mode      | Audit Mode       |
| Intel SGE → SGX   | Disabled        |
| Power Management → USB Wake Support      | Enabled       |
| Power Management → Wake on LAN/WLAN   | Lan Only        |
| Power Management → Block Sleep      | Disabled       |
| Virtualization Support → Virtualization   | Enabled        |
| Virtualization Support → VT For Direct I/O      | Enabled       |
| Advanced configurations → ASPM   | Auto        |

# 参考教程：
[折腾 7080MFF 黑苹果 OpenCore][1]<br/>
[3dudu/dell-optiplex-7080-hackintosh-opencore][2]  

[1]:https://www.jianshu.com/p/d7cfaae60509
[2]:https://github.com/3dudu/dell-optiplex-7080-hackintosh-opencore

# 效果图：

<img width="697" alt="截屏2022-04-18 21 27 12" src="https://user-images.githubusercontent.com/103224673/163815123-d6cc5169-fd56-418e-80e3-932a634402ea.png">

<img width="698" alt="截屏2022-04-18 21 15" src="https://user-images.githubusercontent.com/103224673/163815142-0c21d9a5-529a-4796-93b6-86ea3028270e.png">

<img width="698" alt="截屏2022-04-18 21 15 55" src="https://user-images.githubusercontent.com/103224673/163815175-8befcafe-664e-4d3a-9ba3-ca55c42c851f.png">

<img width="780" alt="截屏2022-04-18 21 21 48" src="https://user-images.githubusercontent.com/103224673/163815204-d6ce9a45-9161-4dbb-9770-c235333ee9f2.png">

<img width="780" alt="截屏2022-04-18 21 21 21" src="https://user-images.githubusercontent.com/103224673/163815251-d53c7fbb-1f4b-48e7-aa79-47c2609dafc4.png">

<img width="822" alt="截屏2022-04-18 21 20 43" src="https://user-images.githubusercontent.com/103224673/163815295-75a9ee5e-d557-4b3d-9b2f-108ba6a70721.png">

<img width="822" alt="截屏2022-04-18 21 20 17" src="https://user-images.githubusercontent.com/103224673/163815332-360ff195-c23a-4431-bb14-6194359cc4a1.png">

<img width="825" alt="截屏2022-04-09 21 47 18" src="https://user-images.githubusercontent.com/103224673/163817302-61581fa2-0796-4140-9287-8fe564d5bc6e.png">
