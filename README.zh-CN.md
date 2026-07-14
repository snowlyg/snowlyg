<p align="center">
  <a href="https://github.com/snowlyg"><kbd>English</kbd></a>
  <strong><kbd>简体中文</kbd></strong>
</p>

<h1 align="center">你好，我是 Rodin Luo</h1>

<p align="center"><strong>Go 后端 / WebRTC 工程师</strong></p>

<p align="center">
我负责构建和排查后端系统与实时音视频应用，重点关注信令、通话可靠性、Android 与 OpenHarmony 集成，以及生产环境故障诊断。
</p>

<p align="center">
  <a href="https://www.lodan.me/zh-cn/">个人主页</a> ·
  <a href="#代表工作">代表工作</a> ·
  <a href="#技术文章">技术文章</a> ·
  <a href="https://www.lodan.me/zh-cn/contact/">联系方式</a>
</p>

<img src="./assets/neon-rtc-hero.svg" alt="实时通信网络霓虹图" width="100%" />

## 专注方向

- **RTC 网关与通话可靠性** — 信令、会话生命周期、ICE/STUN/TURN、coturn 中继路径及弱网排障。
- **生产级 Go 后端** — 并发服务、gRPC、WebSocket 与 MQTT 事件流、死锁分析及生命周期可靠性。
- **音频与媒体问题排查** — Pion WebRTC、FFmpeg 工作流、基于 RTP 的媒体处理、WebRTC 音频 3A 及 AEC dump 分析。

## 代表工作

### [ohscrcpy](https://www.lodan.me/zh-cn/products/ohscrcpy/)

面向 OpenHarmony 和 Android 设备的 Windows 投屏与远程控制工具。支持 ADB/HDC 设备识别与路由、单设备和多设备工作流、局域网连接及 Windows 离线分发。

[产品介绍](https://www.lodan.me/zh-cn/products/ohscrcpy/) · [GitHub Releases](https://github.com/snowlyg/ohscrcpy-releases)

### [GoEasyFfmpeg](https://github.com/snowlyg/GoEasyFfmpeg)

用于管理 FFmpeg 推流进程以及 RTMP、RTSP、HLS、FLV 工作流的 Go 服务。项目基于早期 EasyDarwin 工作扩展，并记录了实现取舍与已知限制。

[源代码](https://github.com/snowlyg/GoEasyFfmpeg)

### 生产环境 RTC 可靠性

大部分生产环境 RTC 网关代码属于非公开项目。下面的技术文章记录了我可以公开分享的部分，包括 Android 与 OpenHarmony 通话行为、coturn 与 ICE 路径、音频 3A、播放延迟及生产故障分析。

## 技术文章

- **2026-06-14** — [使用 AEC_DUMP 与 Audacity 排查 Android WebRTC 音频 3A](https://www.lodan.me/zh-cn/posts/android-webrtc-aecdump-audio-3a-debugging/)
- **2026-06-09** — [排查 OpenHarmony 5.0 上的 WebRTC 音频播放延迟](https://www.lodan.me/zh-cn/posts/openharmony-arkweb-webrtc-audio-playback-latency/)
- **2026-06-06** — [Android 14 床旁设备上的 WebRTC 回声与噪声优化](https://www.lodan.me/zh-cn/posts/android14-bedside-webrtc-echo-noise-optimization/)

[阅读全部技术文章](https://www.lodan.me/zh-cn/posts/)

## 技术栈

- **后端：** Go、gRPC、WebSocket、MQTT、MySQL、Redis
- **RTC 与媒体：** WebRTC、Pion、coturn、ICE/STUN/TURN、FFmpeg、RTP/RTSP/RTMP/HLS
- **平台：** Android、OpenHarmony、Linux、Docker

## 联系方式

我目前开放 Go 后端、RTC 基础设施、实时音视频相关职位及技术合作机会。

[个人主页](https://www.lodan.me/zh-cn/) · [联系方式](https://www.lodan.me/zh-cn/contact/) · [X / Twitter](https://twitter.com/rodin990)
