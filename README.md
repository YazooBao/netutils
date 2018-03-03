# RT-Thread 网络小工具集

## 1、介绍

当 RT-Thread 接入网络后，可玩性大大增强。这里汇集了 RT-Thread 可用的全部网络小工具集合，你所需要的小工具都可以在这里找到。

## 2、获取方式

请使用 ENV 工具辅助下载：

包的路径为：`RT-Thread online package` -> `IoT - internet of things` -> `netutils`

## 3、使用说明

每个小工具可使用 menuconfig 独立控制启用/停用，并提供了 Finsh/MSH 的使用命令。在其目录下都存有一份详细的使用文档。如需使用，请单独查看。下面是目前支持的小工具汇总：

|名称|分类|功能简介|使用文档|
|:--|:--:|:--|:--|
|[Ping](https://baike.baidu.com/item/ping/6235)|调试测试|利用“ping”命令可以检查网络是否连通，可以很好地帮助我们分析和判定网络故障|[点击查看](ping/README.md)|
|[TFTP](https://baike.baidu.com/item/TFTP)|文件传输|TFTP是一个传输文件的简单协议，比 FTP 还要轻量级|[点击查看](tftp/README.md)|
|[iperf](https://baike.baidu.com/item/iperf)|性能测试|测试最大 TCP 和 UDP 带宽性能，可以报告带宽、延迟抖动和数据包丢失|[点击查看](iperf/README.md)|
|[NetIO](http://www.nwlab.net/art/netio/netio.html)|性能测试|测试网络的吞吐量的工具|[点击查看](netio/README.md)|
|[NTP](https://baike.baidu.com/item/NTP)|时间同步|网络时间协议|[点击查看](ntp/README.md)|
|[Telnet](https://baike.baidu.com/item/Telnet)|远程访问|可以远程登录到 RT-Thread 的 Finsh/MSH Shell|[点击查看](telnet/README.md)|
