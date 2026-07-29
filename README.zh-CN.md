[English](./README.md) · **简体中文**

# 罗丹

**RTC / WebRTC 后端工程师 · Go 信令网关 · 设备与音频稳定性**

我是一名偏一线实战的开发主管和核心 Go 后端工程师，拥有 10 年+软件开发经验、6 年+ Go 后端、设备接入与生产交付经验，近 3 年专注于 RTC / WebRTC 网关。

我曾独立设计并实现院内视频电话的 Go 网关核心模块，覆盖会话状态、SDP / ICE、coturn 中继路径、弱网恢复、音视频异常，以及 Android、Linux、Windows 和 OpenHarmony 跨端集成。在 15+ 人团队中承担核心研发、跨端联调和问题推进，参与交付的系统覆盖 30+ 大型医院；典型项目由 1 台服务器覆盖 1500+ 终端。

[个人网站](https://www.lodan.me/zh-cn/) · [技术文章](https://www.lodan.me/zh-cn/posts/) · [X / Twitter](https://twitter.com/rodin990)

## 专注方向

- **RTC 控制面** — 信令、offer / answer、SDP / ICE、STUN / TURN、coturn、会话状态、超时与挂断收敛及异常清理。
- **生产级 Go 后端** — gRPC、HTTP、WebSocket、MQTT、MySQL、Redis、Prometheus / Grafana、并发服务、生命周期可靠性及现场交付。
- **媒体与设备诊断** — Pion WebRTC、RTP、FFmpeg、AEC / AGC / NS、AEC_DUMP、Android Audio、OpenHarmony AudioRenderer、弱网及复杂局域网。

## 代表排障案例

### [WebSocket 假连接与 gRPC Gateway 自动发现](https://www.lodan.me/zh-cn/posts/webrtc-grpc-gateway-discovery-recovery/)

针对机构设备长期在线场景中“连接看似存活、业务消息实际不再流动”的问题，设计双向可达、网关自动发现、显式会话状态和可预期挂断行为的恢复模型。

### [使用 AEC_DUMP 排查 Android WebRTC 音频 3A](https://www.lodan.me/zh-cn/posts/android-webrtc-aecdump-audio-3a-debugging/)

通过对比原始输入、远端播放参考、处理后输出及 Audio Processing Module 配置，将回声、噪声、削波和响度不稳定等主观反馈转化为可检查的音频证据。

### [OpenHarmony WebRTC 音频播放延迟](https://www.lodan.me/zh-cn/posts/openharmony-arkweb-webrtc-audio-playback-latency/)

结合 WebRTC 统计数据、AudioRenderer underrun、PCM 队列行为及 native WebRTC 对照路径，将正常的网络和 ICE 链路与本地播放故障区分开。

[阅读全部技术文章](https://www.lodan.me/zh-cn/posts/)

## 代表公开项目

### [ohscrcpy](https://www.lodan.me/zh-cn/posts/ohscrcpy-openharmony-remote-screen-control/)

面向 OpenHarmony 和 Android 设备的 Windows 投屏与远程控制工具，支持 ADB / HDC 设备路由、多设备工作流、局域网连接、离线分发及带校验的应用更新。

[产品介绍](https://www.lodan.me/zh-cn/posts/ohscrcpy-openharmony-remote-screen-control/) · [版本下载](https://github.com/snowlyg/ohscrcpy-releases/releases)

### [AndroidWebRTCGradle](https://github.com/snowlyg/AndroidWebRTCGradle)

用于双设备通话复现与 AEC_DUMP 采集的公开 Android WebRTC 示例。该项目明确定位为排障工具，而不是生产客户端。

### [GoEasyFfmpeg](https://github.com/snowlyg/GoEasyFfmpeg)

早期用于管理 FFmpeg 推流进程的 Go 服务，覆盖 RTMP、RTSP、HLS 和 FLV 工作流。项目基于 EasyDarwin 扩展，并记录了实际实现取舍与已知限制。

### [iris-admin](https://github.com/snowlyg/iris-admin)

早期开源 Go 项目：围绕 Iris / Gin、GORM、Casbin、Redis、Docker、JWT 和 REST API 构建的 Web Admin / RBAC 基础项目，目前拥有 680+ GitHub stars。

## 当前方向

我目前开放 Go 后端、RTC 基础设施、实时音视频及设备平台稳定性相关职位或技术合作。
