<p align="center">
  <a href="#english"><strong><kbd>English</kbd></strong></a>
  <a href="#zh-cn"><kbd>简体中文</kbd></a>
</p>

<a id="english"></a>

<h1 align="center">Hi, I'm Rodin Luo</h1>

<p align="center"><strong>Go Backend / WebRTC Engineer</strong></p>

<p align="center">
I build and debug backend systems and real-time media applications, with a focus on signaling, call reliability, Android and OpenHarmony integration, and production troubleshooting.
</p>

<p align="center">
  <a href="https://www.lodan.me/">Portfolio</a> ·
  <a href="#selected-work">Selected work</a> ·
  <a href="#engineering-notes">Engineering notes</a> ·
  <a href="https://www.lodan.me/contact/">Contact</a>
</p>

<img src="./assets/neon-rtc-hero.svg" alt="Neon visualization of a real-time communication network" width="100%" />

## What I Work On

- **RTC gateways and call reliability** — signaling, session lifecycle, ICE/STUN/TURN, coturn relay paths, and weak-network troubleshooting.
- **Production Go backends** — concurrent services, gRPC, WebSocket and MQTT event flows, deadlock analysis, and lifecycle reliability.
- **Audio and media debugging** — Pion WebRTC, FFmpeg workflows, RTP-based media, WebRTC audio 3A, and AEC dump analysis.

## Selected Work

### [ohscrcpy](https://www.lodan.me/products/ohscrcpy/)

A Windows screen-mirroring and remote-control tool for OpenHarmony and Android devices. It supports ADB/HDC device routing, single- and multi-device workflows, local-network connections, and offline Windows distribution.

[Product page](https://www.lodan.me/products/ohscrcpy/) · [GitHub releases](https://github.com/snowlyg/ohscrcpy-releases)

### [GoEasyFfmpeg](https://github.com/snowlyg/GoEasyFfmpeg)

A Go service for managing FFmpeg streaming processes and RTMP, RTSP, HLS, and FLV workflows. The project extends earlier EasyDarwin work and documents implementation tradeoffs and known limitations.

[Source code](https://github.com/snowlyg/GoEasyFfmpeg)

### Production RTC Reliability

Most of my production RTC gateway work is private. The engineering notes below document the parts I can share: Android and OpenHarmony call behavior, coturn and ICE paths, audio 3A, playback latency, and production failure analysis.

## Engineering Notes

- **2026-06-14** — [Debugging Android WebRTC Audio 3A with AEC_DUMP and Audacity](https://www.lodan.me/posts/android-webrtc-aecdump-audio-3a-debugging/)
- **2026-06-09** — [Debugging WebRTC Audio Playback Latency on OpenHarmony 5.0](https://www.lodan.me/posts/openharmony-arkweb-webrtc-audio-playback-latency/)
- **2026-06-06** — [WebRTC Echo and Noise Optimization on Android 14 Bedside Devices](https://www.lodan.me/posts/android14-bedside-webrtc-echo-noise-optimization/)

[Read all engineering posts](https://www.lodan.me/posts/)

## Toolkit

- **Backend:** Go, gRPC, WebSocket, MQTT, MySQL, Redis
- **RTC and media:** WebRTC, Pion, coturn, ICE/STUN/TURN, FFmpeg, RTP/RTSP/RTMP/HLS
- **Platforms:** Android, OpenHarmony, Linux, Docker

## Contact

I'm open to Go backend, RTC infrastructure, and real-time media roles or technical collaboration.

[Portfolio](https://www.lodan.me/) · [Contact](https://www.lodan.me/contact/) · [X / Twitter](https://twitter.com/rodin990)

---

<a id="zh-cn"></a>

<p align="center">
  <a href="#english"><kbd>English</kbd></a>
  <strong><kbd>简体中文</kbd></strong>
</p>

<h1 align="center">你好，我是 Rodin Luo</h1>

<p align="center"><strong>Go 后端 / WebRTC 工程师</strong></p>

<p align="center">
我负责构建和排查后端系统与实时音视频应用，重点关注信令、通话可靠性、Android 与 OpenHarmony 集成，以及生产环境故障诊断。
</p>

<p align="center">
  <a href="https://www.lodan.me/zh-cn/">个人主页</a> ·
  <a href="#zh-selected-work">代表工作</a> ·
  <a href="#zh-engineering-notes">技术文章</a> ·
  <a href="https://www.lodan.me/zh-cn/contact/">联系方式</a>
</p>

## 专注方向

- **RTC 网关与通话可靠性** — 信令、会话生命周期、ICE/STUN/TURN、coturn 中继路径及弱网排障。
- **生产级 Go 后端** — 并发服务、gRPC、WebSocket 与 MQTT 事件流、死锁分析及生命周期可靠性。
- **音频与媒体问题排查** — Pion WebRTC、FFmpeg 工作流、基于 RTP 的媒体处理、WebRTC 音频 3A 及 AEC dump 分析。

<a id="zh-selected-work"></a>

## 代表工作

### [ohscrcpy](https://www.lodan.me/zh-cn/products/ohscrcpy/)

面向 OpenHarmony 和 Android 设备的 Windows 投屏与远程控制工具。支持 ADB/HDC 设备识别与路由、单设备和多设备工作流、局域网连接及 Windows 离线分发。

[产品介绍](https://www.lodan.me/zh-cn/products/ohscrcpy/) · [GitHub Releases](https://github.com/snowlyg/ohscrcpy-releases)

### [GoEasyFfmpeg](https://github.com/snowlyg/GoEasyFfmpeg)

用于管理 FFmpeg 推流进程以及 RTMP、RTSP、HLS、FLV 工作流的 Go 服务。项目基于早期 EasyDarwin 工作扩展，并记录了实现取舍与已知限制。

[源代码](https://github.com/snowlyg/GoEasyFfmpeg)

### 生产环境 RTC 可靠性

大部分生产环境 RTC 网关代码属于非公开项目。下面的技术文章记录了我可以公开分享的部分，包括 Android 与 OpenHarmony 通话行为、coturn 与 ICE 路径、音频 3A、播放延迟及生产故障分析。

<a id="zh-engineering-notes"></a>

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
