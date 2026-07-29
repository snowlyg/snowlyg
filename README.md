**English** · [简体中文](./README.zh-CN.md)

# Rodin Luo

**RTC / WebRTC Backend Engineer · Go Signaling Gateway · Device and Audio Reliability**

I am a hands-on development lead and core Go backend engineer with 10+ years in software engineering, 6+ years in Go backend systems, device integration, and production delivery, and nearly 3 years focused on RTC / WebRTC gateways.

I have independently designed and implemented core Go gateway modules for hospital video calling, covering session state, SDP / ICE, coturn relay paths, weak-network recovery, media failures, and Android, Linux, Windows, and OpenHarmony integration. Within a 15+ member team, I have helped deliver systems used across 30+ large hospitals; a typical deployment covers 1,500+ terminals with one server.

[Website](https://www.lodan.me/) · [Engineering notes](https://www.lodan.me/posts/) · [X / Twitter](https://twitter.com/rodin990)

## What I Work On

- **RTC control plane** — signaling, offer / answer, SDP / ICE, STUN / TURN, coturn, session state, timeout and hangup convergence, and abnormal cleanup.
- **Production Go backends** — gRPC, HTTP, WebSocket, MQTT, MySQL, Redis, Prometheus / Grafana, concurrent services, lifecycle reliability, and field delivery.
- **Media and device diagnosis** — Pion WebRTC, RTP, FFmpeg, AEC / AGC / NS, AEC_DUMP, Android audio, OpenHarmony AudioRenderer, weak networks, and complex LANs.

## Selected Engineering Cases

### [WebSocket Half-Open Connections and gRPC Gateway Discovery](https://www.lodan.me/posts/webrtc-grpc-gateway-discovery-recovery/)

Designed a recovery model for institutional device fleets where connections can appear alive while application messages no longer move. The case covers bidirectional reachability, automatic gateway discovery, explicit session state, and predictable hangup behavior.

### [Android WebRTC Audio 3A with AEC_DUMP](https://www.lodan.me/posts/android-webrtc-aecdump-audio-3a-debugging/)

Turned subjective reports of echo, noise, clipping, and unstable loudness into inspectable evidence by comparing raw input, reverse playback reference, processed output, and Audio Processing Module settings.

### [OpenHarmony WebRTC Audio Playback Latency](https://www.lodan.me/posts/openharmony-arkweb-webrtc-audio-playback-latency/)

Separated network and ICE health from a local playback failure using WebRTC statistics, AudioRenderer underruns, queued PCM behavior, and a native WebRTC comparison path.

[Read all engineering notes](https://www.lodan.me/posts/)

## Selected Public Work

### [ohscrcpy](https://www.lodan.me/posts/ohscrcpy-openharmony-remote-screen-control/)

A Windows screen-mirroring and remote-control tool for OpenHarmony and Android devices. It supports ADB / HDC device routing, multi-device workflows, LAN connections, offline distribution, and verified application updates.

[Product notes](https://www.lodan.me/posts/ohscrcpy-openharmony-remote-screen-control/) · [Releases](https://github.com/snowlyg/ohscrcpy-releases/releases)

### [AndroidWebRTCGradle](https://github.com/snowlyg/AndroidWebRTCGradle)

A public Android WebRTC sample used as a reproducible debugging utility for two-device calls and AEC_DUMP capture. It is intentionally presented as a diagnostic tool rather than a production client.

### [GoEasyFfmpeg](https://github.com/snowlyg/GoEasyFfmpeg)

An earlier Go service for managing FFmpeg streaming processes across RTMP, RTSP, HLS, and FLV workflows. It extends EasyDarwin work and records practical implementation tradeoffs and known limitations.

### [iris-admin](https://github.com/snowlyg/iris-admin)

Earlier open-source Go work: a web admin and RBAC foundation built around Iris / Gin, GORM, Casbin, Redis, Docker, JWT, and REST APIs, with 680+ GitHub stars.

## Current Focus

I am open to Go backend, RTC infrastructure, real-time media, and device-platform reliability roles or technical collaboration.
