# VPN 自动开关

打开指定应用自动连接 VPN，划掉应用或主进程结束自动断开。

只注入 system_server，不改写任何应用进程。

## 功能

- 打开目标应用自动连接，划掉或进程结束自动断开
- 反向规则：打开指定应用时保持断开
- Wi-Fi / SSID 规则
- 手动断开保护
- 快捷设置磁贴
- 客户端适配测试与一键自检

## 安装

1. 安装 APK
2. LSPosed 中启用模块，作用域只勾「系统框架」
3. 重启手机
4. 选择 VPN 客户端与目标应用

## 链接

- 源码与更新：[github.com/yaoiwi/VpnAutoSwitch](https://github.com/yaoiwi/VpnAutoSwitch)
- 问题反馈：[Issues](https://github.com/yaoiwi/VpnAutoSwitch/issues)
