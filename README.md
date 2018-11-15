# [linux](https://github.com/OS-Q/linux) 

linux系统硬件环境搭建

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 更多可访问 www.OS-Q.com

---

### linux内核

https://github.com/torvalds/linux.git

---

####  Raspbian

树莓派官方深度定制的硬件驱动与软件程序，树莓派官方推荐的Linux系统版本。Raspbian基于Debian发行版本，所以软件策略偏保守，系统以稳定第一。

Raspbian主要运行于开源硬件树莓派上，拥有丰富的软硬件资源

http://downloads.raspberrypi.org/raspbian_latest

---

#### Armbian

Armbian是轻量级的Debian系统，是为ARM开发板专门发行并重新编译的Ubuntu系统，Armbian使用重新编译的Debian Wheezy，Jessie或Ubuntu。

- 全志A10, A20, A31, H3, A64

- Amlogic S805, S905

- Actionsemi S500

- 飞思卡尔/NXP iMx6

- Marvell Armada A380

- 三星Exynos 5422

- RK3288


https://www.armbian.com/

---

#### RISC OS

RISC OS是一个最初由剑桥Acorn计算机公司（ARM 公司前身）于1987专门设计在ARM芯片上运行。对于现在流行的RISC架构ARM体系来说算是最为精练的操作系统。

1999年1月，Acorn正式停止对该操作系统的开发工作，RISC OS 陆续被出售或被授权给了 RISCOS Ltd、Pace Micro Technology 和 Castle Technology 等公司。

2016年，Castle Technology 在一个部分免费的许可下对外发布 RISC OS 源码，允许非商业免费使用，商业用户需向其支付版税。

2018年，ROD 收购了 Castle Technology Ltd ，并获得 RISC OS 的知识产权。

ROD 将与 RISC OS 社区维护组织 ROOL合作，根据 Apache 2.0 许可证将 RISC OS 的源代码重新分发。

RISC OS 具有快速、紧凑、高效的特点，它并不是Linux的一种，也与Windows没有关系，拥有大量独特的特性及设计模式。

强调rsic的微内核属性，自然就带来了与宏内核linux的对比。linux系统是一个健壮的操作系统，当然我们可以对基内核进行精简，但是这个操作系统还是为了适应多种CPU与硬件进行了“通用化”设计。

现代硬件系统虽然越来越强大，但是不得不说的是，每千行代码总可能出10个BUG代码行的“摩尔定律”并未失效。微内核系统的好处自然有使用场景。

https://www.riscosopen.org/content/


---

### OpenWrt

针对嵌入式设备的 Linux 操作系统。它完全取代了厂商提供的各种无线路由器和非网络设备的固件

https://downloads.openwrt.org/releases/

---

### rockchip-linux

瑞星微的Linux版本，可以在瑞星微的芯片上运行

https://github.com/rockchip-linux/kernel.git

---

### RDA

RDA SOC的Linux系统版本，RDA8810 高性价比SOC

https://github.com/orangepi-xunlong/OrangePiRDA_scripts.git

https://github.com/orangepi-xunlong/OrangePiRDA_kernel.git

https://github.com/orangepi-xunlong/OrangePiRDA_uboot.git

---

### Allwinner

全志芯片的Linux系统版本，可以在全志的芯片上运行

http://linux-sunxi.org/Linux_Kernel

https://github.com/linux-sunxi



---

### 说明

