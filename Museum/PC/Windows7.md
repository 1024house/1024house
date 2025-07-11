# Windows 7 PC

Win7 发布于 2009 年，寿命终止于 2020 年。最新版 Win7 SP1 发布于 2011 年，本文以 Win7 SP1 为准。

64 位已成为主流，所以本文以 64 位为准。

Win7 支持的最高硬件：

- CPU：Intel 酷睿 9 代
- 集成显卡：酷睿 6 代和至强集成的 Iris P580（Xeon E3-1585 v5）、Iris 580（i7-6785R、i5-6685R、移动 6770HQ）和 HD530（i5-6500）等,[驱动 Intel 15.45](https://www.intel.com/content/www/us/en/support/articles/000090440/graphics.html)。
- 独立显卡：英伟达 RTX 3090 Ti，[驱动 GeForce 473.62](https://www.nvidia.cn/drivers/details/189496/)
- 主板：酷睿 9 代匹配 Intel 300 系，首选 22nm DDR3 的 [H310C（Win7 专用，支持 6-9 代 CPU）](https://www.asrock.com/mb/Intel/H310CM-HDVP/index.asp#Download)，其次 22nm DDR4 的 Z370、B365，其次 14nm 的 B360。酷睿 6 代匹配 Intel 100 系（H110、[B150](https://www.msi.cn/Motherboard/B150I-GAMING-PRO/support#driver)、[H170](https://www.asus.com.cn/supportonly/h170i-pro/helpdesk_download/)、[Z170](https://www.gigabyte.cn/Motherboard/GA-Z170N-WIFI-rev-10/support#support-dl-driver-chipset)、H310C）。
- SSD TRIM：支持。
- SATA 驱动：原版系统自带。
- NVME 驱动：原版系统不带，可自行集成。
- USB 3.0 驱动：原版系统不带，可自行集成。

本博物馆的 Win7 硬件（待定）：

- [x] CPU：Intel i3-9100F（无集成显卡）
- [x] 主板：准系统自带 B360
- [x] 显卡：GT640 刀卡（50 元的显卡太弱了，和 9 代集成显卡 UHD630 一样，而 i3-9100F 和 9100 差价正好 50 元，用独显纯属浪费电）
- [x] 机箱：白色 NEC SFF 9 代
- [x] 电源：机箱自带航嘉 180w（80Plus 铜牌，商家缩水了，别家 210w）
- [x] 内存：DDR4 8G
- [x] 硬盘：NVME 或 SATA
- [x] 键盘：白色微软 PS/2
- [x] 鼠标：白色微软 USB
- [x] 显示器：白色 NEC 27 英寸液晶

候选硬件：

- [x] CPU：Intel i5-6500（集成显卡 HD530）
- [x] 主板：技嘉 Z170n ITX
- [x] 显卡：P106-100（相当于 GTX 1060，安装 Win10 双系统使用）
- [x] 机箱：黑色 银欣 ITX
- [x] 电源：银欣 ITX 自带 600W

参考资料：

> Windows 7 系统发布时，USB 3.0 接口尚未完全普及，因此其原生系统镜像中未集成 USB 3.0 驱动程序。尤其是从英特尔第六代 CPU 开始，主板的 USB 主控芯片发生了变化，采用了 XHCI 主控，而 Windows 7 原生只有面向 USB 2.0 标准的 EHCI 驱动，没有 XHCI 驱动，这就导致在新平台上安装 Win7 系统时，可能会出现无法识别 USB 3.0 设备的情况。

> 2009 年，27 英寸显示器市场迎来了一个重要里程碑，多个厂商发布了各自的 27 英寸显示器产品。其中，苹果发布了 27 英寸 iMac，拥有 2560x1440 分辨率和 LED 背光。惠普也推出了 2709m，是其首款面向主流市场的 27 英寸液晶显示器。此外，明基也发布了其首款 27 寸全高清液晶显示器 M2700HD。

- [Windows 7 生命周期](https://learn.microsoft.com/zh-cn/lifecycle/products/windows-7)
- [Windows 7 及更低版本支持的 Intel 处理器](https://learn.microsoft.com/zh-cn/windows-hardware/design/minimum/supported/windows-7-supported-intel-processors)
- [映泰 H310 支持 Win7 教程](http://biostar.com.cn/app/en-us/event/H310MH/H310MH-win7.html)
- [Intel H310C 主板实测：被魔改得支持 DDR3 和 Win7](https://news.mydrivers.com/1/594/594071.htm)
