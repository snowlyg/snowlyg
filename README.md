<p align="center">
  <strong><kbd>English</kbd></strong>
  <a href="https://github.com/snowlyg/snowlyg/blob/main/README.zh-CN.md"><kbd>简体中文</kbd></a>
</p>

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
