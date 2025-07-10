# Windows XP PC

XP 发布于 2001 年，最新版 XP SP3 发布于 2008 年，本文以 XP SP3 为准。

XP 64 位版发布于 2005 年，但并不流行，所以本文以 32 位为准。

XP 支持的最高硬件：

- CPU：Intel 酷睿 4 代
- 主板：Intel 8 系（H81、[B85](https://www.asus.com/us/supportonly/b85-plus/helpdesk_download/)、H87、[Z87](https://us.msi.com/Motherboard/Z87-G43/support#driver) 等），[驱动 Management Engine Interface 9.5.24.1790 5M](https://www.asus.com/us/supportonly/b85-plus/helpdesk_download/)
- 集成显卡：[酷睿 4 代驱动 Intel 14.56.0.5449（6.14.10.5449）](https://drivers.mydrivers.com/drivers/477_190835.htm)，[酷睿 2-3 代驱动 Intel 14.51.11.5437 (6.14.10.5437)](https://www.intel.com/content/www/us/en/download/16543/intel-hd-graphics-driver-for-windows-xp-exe.html)。
- 独立显卡：英伟达 GTX960 2-4G，[驱动 GeForce 368.81](https://www.nvidia.cn/drivers/details/105040/)
- 最大显存：1.5G（多了也没用）
- 最大内存：4G（多了也没用）
- 硬盘接口：装系统建议用 SATA，而 NVME 很麻烦，只适合做数据盘。
- SSD TRIM：不支持，所以影响 SSD 寿命，可考虑用 eMLC（超耐久）。
- SATA 驱动：正版光盘不带此驱动，建议自行集成，或临时修改 BIOS 为 IDE 模式，装好系统后，再安装系统并切换回 AHCI。
- USB 3.0 驱动：正版光盘不带此驱动，建议自行集成，或将键盘插入 USB 2.0 接口。

待研究：

- [ ] 主板：Intel Z390

本博物馆的 XP 硬件：

- [x] 机箱：海尔 潜龙 i60（ITX、SFX、显卡最大长度 20cm 且最多双槽、带蜂鸣器喇叭）
- [x] 电源：Tt TRM SFX 350W
- [x] CPU：Intel i5-4590（集成显卡 HD4600）
- [x] 主板：华硕 H81M-R（17x19，两个 PS/2，有蜂鸣器针脚）
- [x] 显卡：集成显卡或 Nvidia GT640（比 HD4600 强 64%）
- [x] 内存：DDR3 1600 4G 或 8G
- [x] 硬盘：Intel SSD MLC 80G 或 eMLC 200G
- [x] 键盘：IBM PS/2
- [x] 鼠标：罗技滚球 PS/2
- [x] 显示器：浪潮 17 英寸球面 CRT

候选硬件：

- [ ] 显卡：GTX960（比 HD4600 强 760%，但超过了 1.5G 显存发挥不出来）
- [ ] 显示器：17 英寸液晶

参考资料：

> 2001 年 5 月，苹果发布了 17 英寸 Studio Display（型号：M7649），原始分辨率为 1280x1024

> 2001 年国内 LCD 市场开始进入萌芽期，三星显示器于 2001 年下半年投放了一款 151S 液晶显示器，并迅速赢得市场的青睐。

> 2001 年 11 月 4 日，显示器制造商正将 17 英寸液晶显示器的价格降至 1000 美元以下，从而将其推向主流。三星和优派目前已推出两款 17 英寸型号，三星的 SyncMaster 760vTFT 凭借出色的文本显示和出色的色彩保真度脱颖而出。其可旋转的底座设计非常贴心，而且 799 美元的价格也相当亲民。ViewSonic 售价 899 美元的 ViewPanel VE170m 也能呈现出同样清晰细腻的照片和真实饱和的色彩。它对细微色调差异的处理比 SyncMaster 略胜一筹，但屏幕上的图标有时会显得模糊。

> 2002 年 11 月，明基 (BenQ) 推出一款全新高品质 17 英寸液晶显示器（FP767），它拥有 260 尼特的出色亮度和 500:1 的超高对比度。

> 在进入 2003 年下半年之后，市场上各个品牌的 15 寸液晶显示器都或多或少的出现了缺货的现象，而且即使到货的话价格也要比以前略有上升。而与此同时，17 寸的产品价格却逆流而下，多个品牌的 17 寸产品价格已经降到了 3500 元以下，和 15 寸的产品价差已经不到 1000 元。

> 2003 年 9 月 15 日，联想限量推出标配 17 吋液晶显示器的天骄双模式电脑，售价仅为 7999 元。

- [Intel CPU 代系与集成显卡对应表](https://www.intel.com/content/www/us/en/support/articles/000007772/graphics.html)
- [Intel 8 系列安装 XP 系统注意事项及驱动下载（H81，b85，q87）](https://tools.lenovo.com.cn/doc/detail/id/1009/html)
- [2023.9 联想推出 17 英寸液晶电脑](https://finance.sina.cn/sa/2003-09-18/detail-ikknscsi0884121.d.html?from=wap)
- [2004.1 揭秘内幕：17 寸液晶不到 3000 元为哪般？](https://tech.sina.com.cn/c/2004-01-14/26849.html)
- [三星显示器十年专题_新浪网](https://cs.sina.com.cn/minisite/20081208samsung/history01.html)
- [2001 年代表性产品_液晶显示器新闻-中关村在线](https://lcd.zol.com.cn/112/1122083.html)
- [How to Install Windows XP on EVGA Z390 Dark](https://globetrotter.tech/blog/how-to-install-windows-xp-on-evga-z390-dark/)
- [Windows XP on ASUS Z390](https://community.hwbot.org/topic/192682-windows-xp-on-asus-z390-motherboards-and-others/)
