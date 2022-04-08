# Dell-OptiPlex-7080-MFF-Opencore
OpenCore for macOS Monterey (12.3.1) on Dell OptiPlex 7080 MFF

# 基本配置：

&ensp;&ensp;处理器：Intel Comet Lake I7-10700T

&ensp;&ensp;芯片组：Intel Q470

&ensp;&ensp;内存：8G DDR4 3200 * 2

&ensp;&ensp;显卡：UHD 630

&ensp;&ensp;声卡：ALC256 (内置扬声器+耳麦一体+音频输出)

&ensp;&ensp;网卡：Intel I219-LM7

&ensp;&ensp;无线网卡/蓝牙：博通 BCM94360Z3

&ensp;&ensp;固态硬盘:  WD SN730 M.2 256G

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
