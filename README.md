# Navicat Premium 17 for mac 无限重置试用期脚本

## 免责声明

本脚本为免费使用，本脚本只供个人学习使用，使用需严格遵守开源许可协议。严禁用于商业用途，禁止进行任何盈利活动。对一切非法使用所产生的后果，概不负责！

## 使用声明

- 本脚本适用于 mac 系统，不适用于 windows
- 如果遇到 bug 问题，请反馈 issue 给我

## 使用方式

> 从 [navicat premium](https://www.navicat.com.cn/download/navicat-premium) 官网下载最新版。安装并运行，选择试用 14 天。

1. 当试用期结束后，关闭 Navicat Premium
2. 打开 Terminal.app 或其他终端并执行下列命令

```Bash
rm ~/Library/Preferences/com.navicat.NavicatPremium.plist
find ~/Library/Application\ Support/PremiumSoft\ CyberTech/Navicat\ CC/Navicat\ Premium -type f -name '.*' -exec rm "{}" \;


```

3. 打开 Navicat Premium 即可显示试用期已重置
