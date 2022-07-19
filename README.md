# TRSS Liteyuki 轻雪机器人管理脚本
[![Stars](https://img.shields.io/github/stars/TimeRainStarSky/TRSS_Liteyuki?color=yellow&label=收藏)](https://github.com/TimeRainStarSky/TRSS_Liteyuki/stargazers)
[![Downloads](https://img.shields.io/github/downloads/TimeRainStarSky/TRSS_Liteyuki/total?color=blue&label=下载)](https://gitee.com/TimeRainStarSky/TRSS_Liteyuki/raw/main/Install.sh)
[![Releases](https://img.shields.io/github/v/release/TimeRainStarSky/TRSS_Liteyuki?color=green&label=发布版本)](https://github.com/TimeRainStarSky/TRSS_Liteyuki/releases/latest)  
[![访问量](https://profile-counter.glitch.me/TimeRainStarSky-TRSS_Liteyuki/count.svg)](https://timerainstarsky.github.io/TRSS_Liteyuki)

## 使用教程
1. 准备：[Arch Linux](https://archlinux.org) 推荐使用[TMOE](https://gitee.com/mo2/linux)安装：
```
bash -c "$(curl -L https://gitee.com/mo2/linux/raw/2/2)"
```

2. 安装：
```
curl -LO "https://gitee.com/TimeRainStarSky/TRSS_Liteyuki/raw/main/Install.sh" && bash Install.sh
```
视频教程：https://b23.tv/av983453309

## 使用说明
- NoneBot2 <-WS连接-> go-cqhttp <-网络连接-> QQ服务器
- go-cqhttp：提供QQ账号管理，收发消息等功能
- NoneBot2：对消息进行处理，完成目标操作

## 常见问题
- 问：无法连接到反向 WebSocket Universal 服务器
- 答：请确认 Liteyuki 正常运行并启动了 Uvicorn WebSocket 服务器

- 问：address already in use
- 答：WebSocket 端口被占用，请尝试停止占用进程、重启设备，或修改配置文件，更换 WebSocket 端口

- 问：未知错误：open terminal failed: not a terminal
- 答：
  - 1.TMOE proot 容器首次启动会出现，退出容器重启就行了，推荐使用 chroot 容器
  - 2.Windows 出现这种情况，是你使用的终端不支持 tmux，请换一个终端

- 问：我有其他问题
- 答：提供详细问题描述，通过下方 联系方式 反馈问题

## 联系方式
- QQ群组：[211414032](https://jq.qq.com/?k=QU1xGLEB)
### 时雨🌌星空
- GitHub：[TimeRainStarSky](https://github.com/TimeRainStarSky)
- 酷安：[时雨丶星空](http://www.coolapk.com/u/2650948)
- QQ：[2536554304](https://qm.qq.com/cgi-bin/qm/qr?k=x8LtlP8vwZs7qLwmsbCsyLoAHy7Et1Pj)
- Telegram：[TimeRainStarSky](https://t.me/TimeRainStarSky)

## 界面展示
[![主界面](https://cdn.jsdelivr.net/gh/TimeRainStarSky/TRSS_Liteyuki@main/Picture/Main.png)](https://github.com/TimeRainStarSky/TRSS_Liteyuki)
[![Liteyuki](https://cdn.jsdelivr.net/gh/TimeRainStarSky/TRSS_Liteyuki@main/Picture/Liteyuki.png)](https://github.com/snowyfirefly/Liteyuki-Bot)