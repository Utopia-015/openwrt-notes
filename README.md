# openwrt-notes
### 编译 [官方源码](https://github.com/openwrt/openwrt)
以下这些默认没有勾选
1. WebUI  
+ 勾选 LuCI;  
+ Translation 勾选简体中文;  
+ modules 勾选 luci-compat, 没有这个的话 ssr 插件界面可能异常
2. 内核模块的 NAT 支持
+ 勾选 Kernel Modules -> kmod-ipt-nat
