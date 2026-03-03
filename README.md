# 🚀 All-in-One 多协议代理一键部署脚本

[![Version](https://img.shields.io/badge/Version-3.4.10-blue.svg)](https://github.com/fjidbajd/all-in-one)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Debian%20%7C%20Ubuntu%20%7C%20CentOS%20%7C%20Alpine-orange.svg)]()

这是一个高度集成的全能代理部署脚本，旨在通过单一脚本在 Linux 服务器上快速部署、管理及优化多种代理协议。本项目 Fork 自 `Chil30/vless-all-in-one`，并持续进行功能维护与体验优化。

---

## 🌟 核心特性

* **⚡ 双核心驱动**：
    * **Xray 核心**：处理 TCP/TLS 协议（VLESS/VMess/Trojan/SOCKS/SS2022）。
    * **Sing-box 核心**：高效处理 UDP/QUIC 协议（Hysteria2/TUIC），极低内存占用。
* **📡 协议大圆满**：支持共计 **14 种** 协议，包括最新的 **Reality** 伪装与 **XHTTP** 传输。
* **👥 智能用户系统**：支持多用户添加、流量配额限制、过期自动禁用以及 Telegram 实时告警通知。
* **🔗 链式转发与分流**：支持 WARP 落地、链式代理转发、负载均衡组（最快延迟/随机/轮询）。
* **🛠️ 深度优化**：内置 **BBR** 一键开启、**Cloudflare Tunnel (Argo)** 集成，支持自动申请 **Let's Encrypt** 证书。

---

## 🛠️ 快速安装

请在您的 Linux 终端执行以下一键安装命令：

```bash
wget -O vless-server.sh [https://raw.githubusercontent.com/fjidbajd/all-in-one/refs/heads/main/vless-server.sh](https://raw.githubusercontent.com/fjidbajd/all-in-one/refs/heads/main/vless-server.sh) && chmod +x vless-server.sh && bash vless-server.sh
```

---
🤝 鸣谢与声明
原作者：Chil30

核心支持：Xray-core, Sing-box

免责声明：本脚本仅供学习交流及科研使用，请勿用于非法用途。使用本脚本产生的一切后果由使用者自行承担。
---
