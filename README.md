# asus_b450m-k_rx570_hackintosh
## 硬件
1. 主板: 华硕b450m-k
2. 处理器: r3 3300x
3. 内存：酷兽 ddr4 3200 16g x 2
4. 显卡：rx570 (rx580 2048sp降级）
5. 固态：铠侠 rc10 500g
6. 无线网卡: intel 7260 ac
7. 显示器: dell u2720qm (这个显示器会频繁唤醒休眠机器，需要在显示器中将唤醒机器关闭)

# macOS 版本
12.6.1 12的最后一个小版本，升到最新的13相关驱动可能需要调整，请晓！！
<img width="586" alt="image" src="https://user-images.githubusercontent.com/32238306/206835282-b76a6ed0-a2da-4368-b437-c1378092d3b8.png">



# opencore
1. 版本: 0.8.7

# 已知问题：
1. intel无线网卡不可airdrop
2. amd cpu 固有问题
  * 关于本机中cpu型号显示未知(需手动进系统修复)；
  * 有些软件不可以使用或使用不正常：虚拟化软件vmware, adobe, 达芬奇等；
  * 诸如腾讯柠檬等系统辅助软件不能读取到 cpu温度 和 cpu风扇转速；
  * 不支持 HEVC 硬解，b站需要选择其他视频编码浏览，否则页面机器卡顿。

未提及问题全部正常！

# bios设置
参考国光给的[配置](https://apple.sqlsec.com/3-%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C/3-1/#amd-bios)

# 引用
1. 系统镜像：[黑果小兵](https://blog.daliansky.net/)
2. 参考网站：[国光的黑苹果安装教程](https://apple.sqlsec.com/)
3. 工具
  * [OC GEN X](https://github.com/Pavo-IM/OC-Gen-X)
  * [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
  * [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/)
