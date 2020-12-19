## 应用概述

Clash for Windows 是一个拥有 GUI 界面基于 Clash 可自定义规则的 Windows 代理应用。

支持 Shadowsocks 协议和其 simple-obfs 插件、v2ray-plugin 插件以及 VMess 协议和其 TCP、WebSocket 等传输方式。

## 应用下载

以下是各平台该应用的下载地址。

- Windows：[Clash for Windows](/ssr-download/ClashforWindows.zip)

## 获取订阅

此处将显示您的订阅链接，请注意为登录状态：

[cinwell website](/sublink?type=clash ':include :type=markdown')

!> 这个 **订阅链接** 非常重要，你应当把它当做密码一样妥善保管。

## 配置 Clash for Windows

1. 打开 Clash for Windows，点击侧边栏的【配置文件】，将订阅链接粘贴在订阅订阅链接框，然后点击【下载】
![1](https://i.loli.net/2020/12/19/fgC1Xz6nUctqIpO.png ':size=600')

2. 鼠标点击选择刚下载的配置文件

3. 点击侧边栏的【代理设置】，上方选择 **Rule**，然后在下方的 **国外流量** 中选择 你中意的节点
![2](https://i.loli.net/2020/12/19/dSxnWIByklDcpKT.png ':size=600')

## 开始使用

点击侧边栏的【常规设置】，打开【设置为系统代理】的开关即可开始上网不用时关掉
![3](https://i.loli.net/2020/12/19/LkiA5DI68X2uMUF.png ':size=600')

## 其他注意

在退出Clash或者电脑关机前请务必将【设置为系统代理】的开关关掉，否则可能会影响正常上网，如果遇到关闭Clash后一些网站打不开的情况，将【设置为系统代理】的开关关掉即可

请不要修改 `~/.config/clash/config.yml` 中的端口配置，否则会导致应用异常。

