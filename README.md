
🚀 All-in-One 多协议代理一键部署脚本
这是一个高度集成的全能代理部署脚本，旨在通过单一脚本在 Linux 服务器上快速部署、管理及优化多种代理协议。本项目 Fork 自 Chil30/vless-all-in-one，并持续进行功能维护与优化。

🌟 核心特性
⚡ 双核心驱动：

Xray 核心：处理 TCP/TLS 协议（VLESS/VMess/Trojan/SOCKS/SS2022）。

Sing-box 核心：高效处理 UDP/QUIC 协议（Hysteria2/TUIC），极低内存占用。

📡 协议大圆满：支持共计 14 种 协议，包括最新的 Reality 伪装与 XHTTP 传输。

👥 智能用户系统：支持多用户添加、流量配额限制、过期自动禁用以及 Telegram 实时告警通知。

🔗 链式转发与分流：支持 WARP 落地、链式代理转发、负载均衡组（最快延迟/随机/轮询）。

🛠️ 深度优化：内置 BBR 一键开启、Cloudflare Tunnel (Argo) 集成，支持自动申请 Let's Encrypt 证书。

🛠️ 快速安装
在您的 Linux 终端执行以下一键安装命令：

Bash
wget -O vless-server.sh https://raw.githubusercontent.com/fjidbajd/all-in-one/refs/heads/main/vless-server.sh && chmod +x vless-server.sh && bash vless-server.sh
快捷入口：安装完成后，您可以直接在终端输入 vless 快速进入交互式管理菜单。

🖥️ 菜单功能预览
脚本提供全中文交互菜单，操作简单直观：

安装新协议：多协议并发运行，系统自动避开已占用端口。

用户管理：创建独立账号，设置流量限额及到期时间。

订阅管理：一键生成 Clash、Surge、V2Ray 格式的订阅链接。

分流管理：配置 OpenAI、Netflix、YouTube 等特定服务的出口规则。

CF Tunnel：配置 Argo 隧道，实现内网穿透并隐藏服务器真实 IP。

系统优化：BBR 内核提速、自动定时同步流量。

📋 适配系统
Debian 10+

Ubuntu 18.04+

CentOS 7+ / AlmaLinux / Rocky Linux

Alpine Linux (轻量化系统支持)

🛡️ 安全建议
防火墙设置：请确保在云服务商控制台中开放了您所设置的端口（TCP 或 UDP）。

证书申请：建议拥有域名的用户使用脚本内置的证书申请功能，以获得最佳伪装效果。

TG 通知：强烈建议配置 Telegram Bot，及时获取流量超限或服务异常通知。

🤝 鸣谢与声明
原作者：Chil30

核心支持：Xray-core, Sing-box

免责声明：本脚本仅供学习交流及科研使用，请勿用于非法用途。使用本脚本产生的一切后果由使用者自行承担。
