# fancyss_hnd 离线安装包

> 小于1.3.7的版本是ks开发组维护的版本，因为ks开发组从软件中心项目中移除了科学上网相关文件和在线更新支持，这些版本的固件将无法在线升级插件版本，无法更新最新规则，无法更新v2ray等最新二进制文件。
>1.3.8及以后的版本是接着koolshare开发组更新的最后一个版本基础上开始，在单独的项目（fancyss）内维护，不会有以上的问题。
> 
> **fancyss_hnd**离线安装包仅能在koolshare 梅林/官改 hnd/axhnd/axhnd.675x平台的机器上使用！具体支持机型如下：

## 使用说明

- 请下载离线安装包后将文件名更改为shadowsocks.tar.gz，然后在软件中心离线安装页面上传安装。

## fancyss_hnd 支持机型/固件：

| 机型/固件下载                                                | 类型   | 平台       | CPU     | 架构  | 支持版本 | 皮肤        |
| ------------------------------------------------------------ | ------ | ---------- | ------- | ----- | -------- | ----------- |
| [ASUS RT-AC86U](http://koolshare.cn/thread-127878-1-1.html)  | 梅林改 | hnd        | BCM4906 | ARMV8 | 全部     | asuswrt     |
| [ASUS RT-AX88U](http://koolshare.cn/thread-158199-1-1.html)  | 梅林改 | axhnd      | BCM4908 | ARMV8 | 全部     | asuswrt     |
| [NETGEAR RAX80](https://koolshare.cn/thread-177255-1-1.html) | 梅林改 | axhnd      | BCM4908 | ARMV8 | 全部     | asuswrt     |
| [ASUS RT-AC86U](http://koolshare.cn/thread-139965-1-1.html)  | 官改   | hnd        | BCM4906 | ARMV8 | 全部     | rog  (红色) |
| [ASUS ROG GT-AC5300](http://koolshare.cn/thread-130902-1-1.html) | 官改   | hnd        | BCM4908 | ARMV8 | 全部     | rog  (红色) |
| [ASUS ROG GT-AX11000](http://koolshare.cn/thread-159465-1-1.html) | 官改   | axhnd      | BCM4908 | ARMV8 | 全部     | rog  (红色) |
| [ASUS TUF-AX3000](https://koolshare.cn/thread-179968-1-1.html) | 官改   | axhnd.675x | BCM6750 | ARMV7 | ≥ 1.8.3  | tuf（橙色） |
| [RT-AX86U](https://koolshare.cn/thread-181845-1-1.html)      | 官改   | axhnd.675x | BCM4908 | ARMV8 | ≥ 1.8.3  | asuswrt     |

## 注意：

* fancyss_hnd目前仅支持以上改版固件机型，其它架构/平台固件，原版固件均不能使用fancyss_hnd！
* 使用fancyss_hnd科学上网插件，强烈建议使用chrome或者chrouium内核的浏览器！以保证最佳兼容性！
* 强烈建议在`最新版本的固件`和`最新版本软件中心`上使用fancyss_hnd！
* RT-AC86U/GT-AC5300/GT-AX11000官改固件使用的是ROG皮肤，插件安装会自动识别机型并安装对应皮肤版本。
* TUF-AX3000官改固件使用的是TUF橙色皮肤，插件安装会自动识别机型并安装对应皮肤版本。
* TUF-AX3000暂时不能使用chinadns-ng，smartdns，v2ray-plugin这三个功能（1.8.3），因为这些功能使用的二进制是64位的，而BCM6750作为32位cpu是不能运行的，后期版本将逐渐添加支持。
* RT-AX86U和TUF-AX3000两款机型因为是较新的官改固件，只有fancyss_hnd 1.8.3及以上版本能正常使用。

## 源码

- 查看源码请前往：[https://github.com/hq450/fancyss](https://github.com/hq450/fancyss)

## 更新日志

- https://github.com/hq450/fancyss/blob/master/fancyss_hnd/Changelog.txt
