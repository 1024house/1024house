# Windows Vista PC

Vista 诞生于 2006 或 2007 年，寿命终止于 2017 年：

- 2006 年 11 月 8 日，仅提供 MSDN 订阅者、TechNet 用户下载。
- 2006 年 11 月 30 日，商业版于全球同步发布，提供给企业用户。
- 2007 年 1 月 30 日，零售版本（包含旗舰版、家庭高级版、家庭普通版、入门版）正式销售。
- 2012 年 4 月 10 日，结束主流技术支持。
- 2017 年 4 月 11 日，结束延长技术支持。

最新版 Vista SP2 发布于 2009 年，本文以 Vista SP2 为准。

32 位系统只支持 4G 内存，64 位从 Vista 开始逐渐普及，所以本文以 64 位为准。

Vista 支持的最高硬件：

- CPU：Intel 酷睿 3 代
- 主板：集成显卡支持到 Intel 6 系（H61、H67、P67、Q65、Q67、Z68），独立显卡支持到 Intel 7 系（B75、H77、Z77 等）
- 集成显卡：[Intel 官方](https://www.intel.com/content/www/us/en/download/16652/intel-hd-graphics-driver-for-windows-vista-64-exe.html)声称只支持酷睿 2 代自带的 HD Graphics 3000/2000，不支持酷睿 3 代的 HD 2500/4000，但曾经支持过，[互联网档案馆](http://web.archive.org/web/20170825082730/https://downloadcenter.intel.com/download/20758/Graphics-Intel-HD-Graphics-Driver-for-Windows-Vista)能下载到，页面上表明支持 6 代主板，实测 B75 安装报错：[低于最低系统要求](https://forums.tomshardware.com/threads/ivy-bridge-intel-hd-has-no-vista-support.1320994/)，但有人说[成功了](https://msfn.org/board/topic/174605-intel-hd-graphics-b75-chipset-drivers/page/2/)。
- 独立显卡：英伟达 GTX 980Ti 6G，[驱动 GeForce 361.75](https://www.nvidia.cn/geforce/drivers/results/97793/)
- SSD TRIM：不支持，所以影响 SSD 寿命，可考虑用 eMLC（超耐久）。
- SATA 驱动：原版系统自带。
- USB 3.0 驱动：原版系统不带，USB 3.0 规范是 2008 年发布的，晚于 Vista。装好系统之后，如果 USB 厂商提供驱动，可再安装，但 Intel USB 3.0 芯片不提供 Vista 驱动。

本博物馆的 Vista 硬件：

- [x] 机箱：迎广 ITX（装不下任何显卡）或壁挂开放式机箱（取决于是否必须显卡）
- [x] 电源：机箱自带 180W 电源
- [x] CPU：Intel i5-3450（集成显卡 HD2500）
- [x] 主板：技嘉 B75N（17x17，一个两用 PS/2，无蜂鸣器针脚）
- [x] 显卡：集成显卡或 Nvidia GT640（比 HD2500 强 338%）
- [x] 内存：DDR3 1600 8G
- [x] 硬盘：特科芯 SSD MSATA 128G（需要 MSATA 转 SATA，这个机箱有 2.5 英寸位置，而 XP 机箱里没有，那边用 MSATA 转 SATA 更合适）
- [x] 键盘：黑色 戴尔键盘 SK-8115
- [x] 鼠标：银黑色 戴尔鼠标 MO56UOA
- [x] 显示器：戴尔 19 英寸液晶 p1914sf

候选硬件：

- [ ] 银黑色 戴尔键盘 SK-8135
- [ ] 戴尔 30 英寸显示器
- [ ] 戴尔小主机（SFF 或更小的 USFF/MFF）
- [ ] 联想小主机 m92p

参考资料：

> 2006 年宽屏元年，虽说宽屏液晶的品种数量不到整体市场 1/4，但却获得了近 40%的关注度，可见宽屏产品正在飞速地占领市场，并努力成为今后液晶显示器发展的大趋势。

> 2007 年 19 英寸宽屏液晶显示器正式成为市场主流，压缩了 17 英寸和 19 英寸普屏机型的市场份额。22 英寸宽屏液晶显示器受到用户认可，有望于 2008 年成为主流产品。24 英寸宽屏液晶显示器在 2007 年下半年经各大厂商高调推广之后成为市场热点。

> 2007 年，戴尔推出首款 DisplayPort 接口显示器。虽然在 2007 年 7 月，三星宣布将于明年 8 月推出 Displayport 接口液晶显示器，但戴尔在 12 月率先上市（30 英寸宽屏液晶 3008WFP），不过其 18999 元的官方售价显然不是面向普通消费群体的。


- [微软正式发布 Windows Vista](https://news.sina.com.cn/w/2006-12-02/020910661007s.shtml)
- [Windows Vista 生命周期](https://learn.microsoft.com/zh-cn/lifecycle/products/windows-vista)
- [Compatible hardware with Windows Vista](https://msfn.org/board/topic/177576-compatible-hardware-with-windows-vista/)
- [[Guide] Windows Vista on the Intel Ivy Bridge platform](https://msfn.org/board/topic/177136-guide-windows-vista-on-the-intel-ivy-bridge-platform/)
- [显世界 2006 年度显示器市场回顾与展望](https://lcd.zol.com.cn/topic/494119.html)
- [2007 年显示器 TOP10 新闻回顾](https://lcd.zol.com.cn/77/770224.html)
- [2007-2008 中国液晶显示器市场研究报告](https://zdc.zol.com.cn/80/801974.html)
