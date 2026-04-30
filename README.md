# [fancyss - 科学上网离线安装包](https://hq450.github.io/fancyss/)


- Fancyss is a project providing tools to across the GFW on asuswrt/merlin based router with software center. 
- 此项目提供用于asuswrt、asuswrt-merlin为基础的，带软件中心固件（≥384）路由器的科学上网功能。

---
- 📺 广告1：[ChatGPT Plus、Netflix、Disney+、Spotify、YouTube等会员账号合租，95折优惠码: fancyss](https://nf.video/9QQkT)
- 🚀 广告2：[fancyss合作top机场：<b>Nexitally/奶昔</b> | 全中转机场 / 优质线路资源 / 支持udp / 解锁流媒体，ChatGPT](https://nxboom.com/?PartnerCode=af8f126dd490446e80737444dd0064f6)
- ✈️ 广告3：[fancyss高速机场推荐：<b>ssLinks</b> | 性价比全中转机场 / 80+线路 / 流媒体解锁，9折优惠码: fancyss](https://98a6251b6cd7471da86cca993b6dbe6f.36d.biz/#/register?code=yf6ozeEO)

---

## 源码

[https://github.com/hq450/fancyss](https://github.com/hq450/fancyss)

## 目录说明

> * 原适用于380固件的fancyss_arm已经停止维护，更名为fancyss_arm380并存放于legacy目录下
> * 原适用于384/386固件的fancyss_arm384更名为fancyss_arm，目前最新版本为3.x.x
> * 因安全性等原因，fancyss 科学上网插件3.1.6以前版本已经永久移除

1. **fancyss_arm**：存放适用于arm平台（固件版本≥384）的科学上网离线安装包，最新版为3.x.x
2. **fancyss_hnd**：存放适用于hnd armv7l平台的科学上网离线安装包，最新版为3.x.x
3. **fancyss_hnd_v8**：存放适用于hnd aarch64平台的科学上网离线安装包，最新版为3.x.x
4. **fancyss_qca**：存放适用于qca平台的科学上网离线安装包，最新版为3.x.x
5. **fancyss_mtk**：存放适用于mtk联发科平台的科学上网离线安装包，最新版为3.x.x
6. **legacy**：存放不再维护的科学上网离线安装包，如：fancyss_arm380、fancyss_mipsel

## 插件特色

- 多平台支持：博通armv7，博通arm64，联发科Filogic 830 MT7986A
- 多客户端支持：Shadowsocks、ShadowsocksR、V2ray、Xray、Trojan、NaïveProxy、TuicV5、Hysteria2
- shadowsocks支持SIP003插件：simple-obfs和v2ray-plugin；V2ray和Xray支持多种协议配置
- 多种模式支持：gfwlist模式、大陆白名单、游戏模式、全局模式、回国模式
- 提供多种现成的DNS方案，并且可以自由方便的进行DNS方案自定义配置
- 支持SS/SSR/V2ray/Xray/Trojan节点的在线订阅，支持节点生成二维码用以分享
- 故障转移、主备切换、负载均衡、定时重启、定时订阅、规则更新、二进制更新
- 支持kcptun、udpspeeder、udp2raw，可以实现代理加速，游戏加速，应对丢包等
- 同时提供full版本和lite版本，hnd_lite版本安装后占用不到8MB的空间，适合小jffs机型
- armv8机型支持tcp fast open和ss/ssr/trojan多核心运行

## 支持机型/固件

> 以下为fancyss 3.0支持的机型/固件，点击机型可以前往相应固件下载地址

| 机型/固件下载                                                | 类型 | 平台            | CPU       | 架构      | linux内核 | fancyss版本    |
| ------------------------------------------------------------ | ---- | --------------- | --------- | --------- | --------- | -------------- |
| 机型/固件下载                                                | 类型 | 平台            | CPU       | 架构      | linux内核 | fancyss版本    |
| [R6300V2](https://fw.koolcenter.com/KoolCenter_Merlin_New_Gen_386/Netgear/R6300v2/) | 梅改 | 6.x.4708        | BCM4708   | armv7     | 2.6.36.4  | fancyss_arm    |
| [RT-AC68U](https://www.koolcenter.com/posts/38)              | 梅改 | 6.x.4708        | BCM4708   | armv7     | 2.6.36.4  | fancyss_arm    |
| [RT-AC88U](https://www.koolcenter.com/posts/39)              | 梅改 | 7.14.114.x      | BCM4709   | armv7     | 2.6.36.4  | fancyss_arm    |
| [RT-AC3100](https://www.koolcenter.com/posts/40)             | 梅改 | 7.14.114.x      | BCM4709   | armv7     | 2.6.36.4  | fancyss_arm    |
| [RT-AC5300](https://www.koolcenter.com/posts/41)             | 梅改 | 7.14.114.x      | BCM4709   | armv7     | 2.6.36.4  | fancyss_arm    |
| [RT-AC86U](https://www.koolcenter.com/posts/36)              | 梅改 | hnd             | BCM4906   | armv8     | 4.1.27    | fancyss_hnd_v8 |
| [RT-AC86U](https://www.koolcenter.com/posts/139)             | 官改 | hnd             | BCM4906   | armv8     | 4.1.27    | fancyss_hnd_v8 |
| [GT-AC2900](https://fw.koolcenter.com/KoolCenter_Merlin_New_Gen_386/GT-AC2900/) | 梅改 | hnd             | BCM4906   | armv8     | 4.1.27    | fancyss_hnd_v8 |
| [GT-AC2900](https://www.koolcenter.com/posts/37)             | 官改 | hnd             | BCM4906   | armv8     | 4.1.27    | fancyss_hnd_v8 |
| [GT-AC5300](https://www.koolcenter.com/posts/12)             | 官改 | hnd             | BCM4908   | armv8     | 4.1.27    | fancyss_hnd_v8 |
| [RT-AX88U](https://www.koolcenter.com/posts/34)              | 梅改 | axhnd           | BCM4908   | armv8     | 4.1.51    | fancyss_hnd_v8 |
| [RT-AX88U](https://www.koolcenter.com/posts/142)             | 官改 | axhnd           | BCM4908   | armv8     | 4.1.51    | fancyss_hnd_v8 |
| [RAX80](https://www.koolcenter.com/posts/43)                 | 梅改 | axhnd           | BCM4908   | armv8     | 4.1.51    | fancyss_hnd_v8 |
| [GT-AX11000](https://www.koolcenter.com/posts/140)           | 官改 | axhnd           | BCM4908   | armv8     | 4.1.51    | fancyss_hnd_v8 |
| [GT-AX11000](https://www.koolcenter.com/posts/35)            | 梅改 | axhnd           | BCM4908   | armv8     | 4.1.51    | fancyss_hnd_v8 |
| [RT-AX92U](https://www.koolcenter.com/posts/20)              | 官改 | axhnd           | BCM4906   | armv8     | 4.1.51    | fancyss_hnd_v8 |
| [TUF-AX3000](https://www.koolcenter.com/posts/11)            | 官改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [TUF-AX5400](https://www.koolcenter.com/posts/130)           | 梅改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [TUF-AX5400](https://www.koolcenter.com/posts/141)           | 官改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX58U](https://www.koolcenter.com/posts/130)             | 梅改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [RAX50](https://www.koolcenter.com/posts/130)                | 梅改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX82U](https://www.koolcenter.com/posts/18)              | 官改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX82U](https://www.koolcenter.com/posts/130)             | 梅改 | axhnd.675x      | BCM6750   | armv7     | 4.1.52    | fancyss_hnd    |
| [ZenWiFi_XT8](https://www.koolcenter.com/posts/137)          | 官改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [ZenWiFi_XT8](https://www.koolcenter.com/posts/130)          | 梅改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [ZenWiFi_XD4](https://www.koolcenter.com/posts/21)           | 官改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX56U_V2](https://www.koolcenter.com/posts/16)           | 官改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX1800](https://www.koolcenter.com/posts/16)             | 梅改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX56U](https://www.koolcenter.com/posts/130)             | 梅改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [RAX70](https://www.koolcenter.com/posts/130)                | 梅改 | axhnd.675x      | BCM6755   | armv7     | 4.1.52    | fancyss_hnd    |
| [RT-AX68U](https://www.koolcenter.com/posts/136)             | 官改 | 5.02L.07p2axhnd | BCM4906   | armv8     | 4.1.52    | fancyss_hnd_v8 |
| [RT-AX68U](https://www.koolcenter.com/posts/33)              | 梅改 | 5.02L.07p2axhnd | BCM4906   | armv8     | 4.1.52    | fancyss_hnd_v8 |
| [RT-AX86U](https://www.koolcenter.com/posts/135)             | 官改 | 5.02L.07p2axhnd | BCM4908   | armv8     | 4.1.52    | fancyss_hnd_v8 |
| [RT-AX86U](https://www.koolcenter.com/posts/5)               | 梅改 | 5.02L.07p2axhnd | BCM4908   | armv8     | 4.1.52    | fancyss_hnd_v8 |
| [GT-AXE11000](https://www.koolcenter.com/posts/130)          | 梅改 | 5.02L.07p2axhnd | BCM4908   | armv8     | 4.1.52    | fancyss_hnd_v8 |
| [GT-AX6000](https://www.koolcenter.com/posts/125)            | 官改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| [GT-AX6000](https://www.koolcenter.com/posts/148)            | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| [ZenWiFi_Pro_XT12](https://www.koolcenter.com/posts/133)     | 官改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| [ZenWiFi_Pro_XT12](https://www.koolcenter.com/posts/149)     | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| [TUF-AX3000_V2](https://www.koolcenter.com/posts/161)        | 官改 | 5.04axhnd.675x  | BCM6756   | armv7     | 4.19.183  | fancyss_hnd    |
| [RT-AX86U PRO](https://www.koolcenter.com/posts/228)         | 官改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| RT-AX86U PRO                                                 | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| GT-AX11000 PRO                                               | 官改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| GT-AX11000 PRO                                               | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8     | 4.19.183  | fancyss_hnd_v8 |
| [RT-AX89X](https://www.koolcenter.com/posts/126)             | 官改 | qca-ipq806x     | ipq8074/a | armv7[^2] | 4.4.60    | fancyss_qca    |
| TX-AX6000                                                    | 官改 | mtk-MT798X      | MT7986A   | armv8     | 5.4.182   | fancyss_mtk    |

## 版本选择

> 以下描述仅针对fancyss 3.0版本

fancyss 3.0支持hnd、hnd_v8、qca、arm、mtk 五个平台，每个平台又有full版本和lite版本

full版本为全功能版本，支持SS、 SSR、V2ray、 Xray、Trojan、NaïveProxy、TuicV5、Hysteria2 八种客户端，安装包体积较大

lite版本为精简版本，支持SS、 SSR、 V2ray、 Xray、 Trojan 五种客户端，安装包小巧，以下为lite版本精简内容：

1. lite版本移除了v2ray、trojan二进制文件，默认使用xray-core来运行v2ray和trojan协议
2. lite版本移除了NaïveProxy支持及其相关二进制文件：naive、ipt2socks
3. lite版本移除了shadowsocks的v2ray-plugin插件功能及其对应的二进制文件：v2ray-plugin
4. lite版本移除了UDP加速功能及其二进制文件：speederv1、speederv2、udp2raw
5. lite版本移除了KCP加速功能及其二进制文件：kcptun
6. lite版本移除了负载均衡支持及其页面和二进制文件：haproxy
7. lite版本移除了直连解析的DNS方案及其二进制：cdns、chinadns、chinadns1、smartdns、https_dns_proxyy
8. lite版本移除了haveged，因为现在较新的固件系统自带了熵增软件
9. lite版本移除了shadowsocks-rust替换shadowsocks-libev功能，默认由shadowsocks-libev运行ss协议
10. lite版本移除了socks5页面及其脚本及其acl规则文件

如果是不折腾以上被精简功能的用户，完全可以使用体积更小的lite版本

RT-AX56U_V2、RT-AX57 这种jffs分区极小(15MB)的机型，直接使用lite版本即可

要切换为lite版本，直接安装lite版本的离线安装包即可，以后在线更新也会维持为lite版本

要切换为full版本，直接安装full版本的离线安装包即可，以后在线更新也会维持为full版本

RT-AX86U、GT-AX6000等armv8机型（见上表），从3.0.6开始建议安装fancyss_hnd_v8版本，当然fancyss_hnd同样兼容

## 插件下载

1. 根据你的机型和固件版本，进入到相应的离线安装包存放目录后，选择你需要的版本进行下载即可。

2. 或者使用以下插件离线包下载导航表格：

   | 平台   | 最新full版本下载                                             | 最新lite版本下载                                             | 历史版本下载（包含最新版）                                   |
   | ------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | hnd    | [fancyss_hnd_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_full.tar.gz) | [fancyss_hnd_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_lite.tar.gz) | [fancyss_hnd](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_hnd) |
   | hnd_v8 | [fancyss_hnd_v8_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_v8_full.tar.gz) | [fancyss_hnd_v8_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_v8_lite.tar.gz) | [fancyss_hnd_v8](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_hnd_v8) |
   | qca    | [fancyss_qca_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_qca_full.tar.gz) | [fancyss_qca_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_qca_lite.tar.gz) | [fancyss_qca](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_qca) |
   | arm    | [fancyss_arm_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_arm_full.tar.gz) | [fancyss_arm_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_arm_lite.tar.gz) | [fancyss_arm](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_arm) |
   | mtk    | [fancyss_mtk_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_mtk_full.tar.gz) | [fancyss_mtk_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_mtk_lite.tar.gz) | [fancyss_mtk](                                               |

## 插件安装

1. 离线安装：下载并校验好离线安装包后，在软件中心内使用**离线安装**/**手动安装**功能，选择安装包后上传并安装即可。

2. 命令安装：(以fancyss_hnd_lite.tar.gz为例，先下载好安装包，并将其上传到路由器的/tmp目录)

   ```bash
   mv /tmp/fancyss_hnd_lite.tar.gz /tmp/shadowsocks.tar.gz
   tar -zxvf /tmp/shadowsocks.tar.gz
   sh /tmp/shadowsocks/install.sh
   ```

## 关于皮肤

目前插件皮肤支持以下版本：

asuswrt：经典asuswrt皮肤

rog：华硕红色rog皮肤

tuf：华硕橙色tuf皮肤

tx：华硕天选青色皮肤

## 注意事项

* 强烈建议使用chrome或者chrouium内核的浏览器！以保证最佳兼容性！
* 强烈建议在`最新版本的固件`和`最新版本软件中心`上使用fancyss_hnd！
* 插件会自动跟随当前固件的皮肤类型，支持assuwrt、rog、tuf三种皮肤。
* 一些机型的联名版，只要刷了官改/梅林改版固件的，均能安装本插件！
* 原适用于384/386固件的fancyss_arm384更名为fancyss_arm，目前最新版本为3.x.x
* 原适用于380固件的fancyss_arm已经停止维护，更名为fancyss_arm380并存放于legacy目录下
* 原适用于mipsel架构的的fancyss_mipsel已经停止维护，现存放于legacy目录下
* 适用于fw867 Openwrt/LEDE固件的fancyss_X64目前停止维护状态，存放于legacy目录下

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hq450/fancyss_history_package&type=Date)

[^1]: RT-AC86U从384_81918_koolshare固件版本开始，使用的是asuswrt风格ui，而不是rog风格。



