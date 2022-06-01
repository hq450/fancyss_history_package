# fancyss_arm 离线安装包使用说明
请下载离线安装包后将文件名更改为shadowsocks.tar.gz，然后在软件中心离线安装页面上传安装。

# 注意
3.6.5 - 4.0.2之间的版本是ks开发组维护的版本，因为ks开发组从软件中心项目中移除了科学上网相关文件和在线更新支持，这些版本的固件将无法在线升级插件版本，无法更新最新规则，无法更新v2ray等最新二进制文件。

4.0.3及以后的版本是接着koolshare开发组更新的最后一个版本基础上开始，在单独的项目（fancyss）内维护，不会有以上的问题。

# 机型/固件支持
### [fancyss_arm](https://github.com/hq450/fancyss/tree/master/fancyss_arm)
**fancyss_arm**离线安装包仅适用于merlin koolshare arm架构机型改版固件（arm架构，linux内核版本：2.6.36.4，，bcm470X系列cpu）

**fancyss_arm**支持机型（需刷梅林koolshare改版固件）：
* 华硕系列：`RT-AC56U` `RT-AC68U` `RT-AC66U-B1` `RT-AC1900P` `RT-AC87U` `RT-AC88U` `RT-AC3100` `RT-AC3200` `RT-AC5300`
* 网件系列：`R6300V2` `R6400` `R6900` `R7000` `R8000` `R8500`
* linksys EA系列：`EA6200` `EA6400` `EA6500v2` `EA6700` `EA6900`
* 华为：`ws880`

#### 注意： 
* fancyss_arm仅支持版本号≥X7.2的固件（订阅功能需要版本号≥X7.7）
* *RT-AC86U*和*GT-AC5300*两款机器不能使用fancyss_arm！因为这两款机器的是新架构，请使用fancyss_hnd！
* *RT-AC66U*和*RT-N66U*也不能使用fancyss_arm！因为这两款机器的是mipsel架构，请使用fancyss_mipsel！

# 源码
查看源码请前往：[https://github.com/hq450/fancyss](https://github.com/hq450/fancyss)

# 更新日志
https://github.com/hq450/fancyss/blob/master/fancyss_arm/Changelog.txt
