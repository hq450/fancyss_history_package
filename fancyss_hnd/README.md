# fancyss_hnd 离线安装包

## fancyss_hnd 说明

- 请下载离线安装包后在软件中心离线安装页面上传安装。

- 请安装前核对离线安装包大小和md5校验值

- 如需1.x.x版本，请在`version_1.x.x`文件夹中下载

- 从2.0.0开始，插件包名从shadowsocks更名为fancyss

- 从2.0.0版本开始，同时提供full版本和lite版本，full版本功能全，lite版本安装包小

## fancyss_hnd 支持机型/固件：

> **fancyss_hnd**离线安装包仅能在koolshare 梅林/官改 hnd及其以上平台的机器上使用！具体支持机型如下：

| 机型/固件下载                                            | 类型   | 平台           | CPU     | 架构  | 支持版本 | 皮肤            |
| -------------------------------------------------------- | ------ | -------------- | ------- | ----- | -------- | --------------- |
| RT-AC86U                                                 | 梅林改 | hnd            | BCM4906 | ARMV8 | 全部     | asuswrt         |
| RT-AC86U                                                 | 官改   | hnd            | BCM4906 | ARMV8 | 全部     | rog/asuswrt[^1] |
| GT-AC2900                                                | 梅林改 | hnd            | BCM4906 | ARMV8 | ≥ 1.9.1  | asuswrt [^2]    |
| GT-AC2900                                                | 官改   | hnd            | BCM4906 | ARMV8 | ≥ 1.9.1  | rog             |
| GT-AC5300                                                | 官改   | hnd            | BCM4908 | ARMV8 | 全部     | rog             |
| RT-AX88U                                                 | 梅林改 | axhnd          | BCM4908 | ARMV8 | 全部     | asuswrt         |
| RAX80                                                    | 梅林改 | axhnd          | BCM4908 | ARMV8 | 全部     | asuswrt         |
| GT-AX11000                                               | 官改   | axhnd          | BCM4908 | ARMV8 | 全部     | rog             |
| RT-AX92U                                                 | 官改   | axhnd          | BCM4906 | ARMV8 | ≥ 1.9.1  | asuswrt         |
| TUF-AX3000                                               | 官改   | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.8.3  | tuf             |
| TUF-AX5400                                               | 梅林改 | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.9.7  | tuf             |
| TUF-AX5400                                               | 官改   | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.9.7  | tuf             |
| RT-AX58U                                                 | 梅林改 | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.8.4  | asuswrt         |
| RAX50                                                    | 梅林改 | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.8.4  | asuswrt         |
| RT-AX82U                                                 | 官改   | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.8.4  | asuswrt         |
| RT-AX82U                                                 | 梅林改 | axhnd.675x     | BCM6750 | ARMV7 | ≥ 1.9.1  | asuswrt         |
| ZenWiFi_XT8                                              | 官改   | axhnd.675x     | BCM6755 | ARMV7 | ≥ 1.8.7  | asuswrt         |
| ZenWiFi_XT8                                              | 梅林改 | axhnd.675x     | BCM6755 | ARMV7 | ≥ 1.9.1  | asuswrt         |
| ZenWiFi_XD4                                              | 官改   | axhnd.675x     | BCM6755 | ARMV7 | ≥ 1.8.8  | asuswrt         |
| RT-AX56U_V2                                              | 官改   | axhnd.675x     | BCM6755 | ARMV7 | ≥ 1.9.0  | asuswrt         |
| RT-AX56U                                                 | 梅林改 | axhnd.675x     | BCM6755 | ARMV7 | ≥ 1.9.1  | asuswrt         |
| RT-AX68U                                                 | 官改   | p1axhnd.675x   | BCM4906 | ARMV8 | ≥ 1.9.1  | asuswrt         |
| RT-AX68U                                                 | 梅林改 | p1axhnd.675x   | BCM4906 | ARMV8 | ≥ 1.9.1  | asuswrt         |
| RT-AX86U                                                 | 官改   | p1axhnd.675x   | BCM4908 | ARMV8 | ≥ 1.8.3  | asuswrt         |
| RT-AX86U                                                 | 梅林改 | p1axhnd.675x   | BCM4908 | ARMV8 | ≥ 1.9.1  | asuswrt         |
| GT-AXE11000                                              | 梅林改 | p1axhnd.675x   | BCM4908 | ARMV8 | ≥ 1.9.1  | asuswrt         |
| [GT-AX6000](https://www.koolcenter.com/posts/125)        | 官改   | 5.04axhnd.675x | BCM4912 | ARMV8 | ≥ 1.9.6  | rog             |
| [GT-AX6000](https://www.koolcenter.com/posts/148)        | 梅林改 | 5.04axhnd.675x | BCM4912 | ARMV8 | ≥ 1.9.8  | asuswrt         |
| [ZenWiFi_Pro_XT12](https://www.koolcenter.com/posts/133) | 官改   | 5.04axhnd.675x | BCM4912 | ARMV8 | ≥ 1.9.6  | asuswrt         |
| [ZenWiFi_Pro_XT12](https://www.koolcenter.com/posts/149) | 梅林改 | 5.04axhnd.675x | BCM4912 | ARMV8 | ≥ 1.9.6  | asuswrt         |
| [TUF-AX3000_V2](https://www.koolcenter.com/posts/161)    | 官改   | 5.04axhnd.675x | BCM6756 | ARMV7 | ≥ 1.9.8  | tuf             |

## 注意：

* fancyss_hnd目前仅支持以上改版固件机型，其它架构/平台固件，原版固件均不能使用fancyss_hnd！
* 相关机型的梅林改/官改固件下载请前往：[https://www.koolcenter.com/](https://www.koolcenter.com/)
* 使用fancyss_hnd科学上网插件，强烈建议使用chrome或者chrouium内核的浏览器！以保证最佳兼容性！
* 强烈建议在`最新版本的固件`和`最新版本软件中心`上使用fancyss_hnd！
* GT-AC2900/GT-AC5300/GT-AX11000/GT-AX6000官改使用ROG皮肤，插件安装会自动识别机型并安装对应皮肤版本。
* TUF-AX3000/TUF-AX3000_V2/TUF-AX5400官改固件使用的是TUF橙色皮肤，插件安装会自动识别机型并安装对应皮肤版本。
* TUF-AX5400梅林改版固件使用的是TUF橙色皮肤，插件安装会自动识别机型并安装对应皮肤版本。
* 一些机型的联名版如GT-AX11000使命召唤黑色行动版/海妖版，RT-AX86U高达版/鬼灭之刃版，RT-AX82U高达版，RT-AX88U高达版本等各种联名版均是默认支持的。
* 部分机型只有达到特定版本后才能使用，386固件至少需要fancyss_hnd ≥ 1.9.1版本才能使用，建议使用最新版本插件！

[^1]: RT-AC86U从384_81918_koolshare固件版本开始，使用的是asuswrt风格ui，而不是rog风格。

[^2]: RT-AC86U从384_81918_koolshare固件版本开始，使用的是asuswrt风格ui，而不是rog风格。

## lite版本和full版本区别

1. lite版本移除了v2ray、trojan二进制文件，默认使用xray-core来运行v2ray和trojan协议

2. lite版本移除了shdowsocks的v2ray-plugin插件功能及其对应的二进制文件：v2ray-plugin

3. lite版本移除了KCP加速功能及其二进制文件：speederv1、speederv2、udp2raw

4. lite版本移除了UDP加速功能及其二进制文件：kcptun

5. lite版本移除了koolgame协议支持及其二进制文件：koolgame、pdu

6. lite版本移除了负载均衡支持及其页面和二进制文件：haproxy

7. lite版本移除了直连解析（非远端解析）的国外DNS方案及其二进制文件：cdns、chinadns、chinadns1、smartdns
   直连解析本身国外cdn效果就较差，很多时候还无法解锁Netflix！不过保留下了一个直连解析方案：https_dns_proxy
   https_dns_proxy因为有ECS的支持，还是具有一定的cdn效果的（针对直连机场，中转机场效果可能差）
   个人建议直接使用chinadns-ng即可，既有很好的国外（远端解析）和国内cdn效果，又可以帮dnsmasq减轻规则负担。

8. lite版本移除了haveged，因为现在较新的固件系统自带了熵增软件

9. lite版本移除了shdowsocks-rust替换shadowsocks-libev功能，默认由shadowsocks-libev运行ss协议

10. lite版本移除了socks5页面及其脚本及其acl规则文件

**总结1：**和全功能版本相比，Lite版本没有KCP加速、UDP加速、SS+v2ray-plugin、负载均衡、独立的socks5设定、koolgame协议，并且精简了一些直连解析的国外DNS解析方案

**总结2：**所以现在lite版本是支持SS、 SSR、 V2ray、 Xray、 Trojan 五种客户端的科学上网、游戏加速工具。

- 如果是不折腾以上被精简功能的用户，完全可以使用体积更小的lite版本
- 当然，RT-AX56U_V2这种jffs分区极小的机型，也建议直接使用lite版本
- 要切换为lite版本，直接安装shadowsocks_lite.tar.gz即可，以后在线更新也维持为lite版本
- 要切换为全功能版本，直接安装shadowsocks.tar.gz即可，以后在线更新也维持为全功能版本

## 其它

- 小于1.3.7的版本是ks开发组维护的版本，因为ks开发组从软件中心项目中移除了科学上网相关文件和在线更新支持，这些版本的固件将无法在线升级插件版本，无法更新最新规则，无法更新v2ray等最新二进制文件。
- 1.3.8及以后的版本是接着koolshare开发组更新的最后一个版本基础上开始，在单独的项目（fancyss）内维护，不会有以上的问题。

## 源码

- 查看源码请前往：[https://github.com/hq450/fancyss](https://github.com/hq450/fancyss)

## 更新日志

- https://github.com/hq450/fancyss/blob/master/fancyss_hnd/Changelog.txt
