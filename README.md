# 📊 vnStat Telegram 流量日报管理工具

一个基于 **vnStat** 的服务器流量统计脚本，支持 **Telegram 每日自动推送流量报告**，适用于 VPS / 独立服务器流量监控。

---

## ✨ 功能特性

- 📈 **昨日流量统计**（下载 / 上传 / 合计）
- 📅 **自定义流量统计周期**
- 🔄 **按月自动重置周期**
- 🛡️ **隐私保护**：报表中隐藏服务器 IP 地址，保护隐私安全。
- 📊 **周期累计用量 & 百分比进度条**
- 🔧 **初始流量校准**：支持输入本周期已用流量，解决月中安装统计不全的问题（仅限当前周期生效，下周期自动清零）。
- ⚡ **终端快捷键**：安装后在终端输入 `vps` 即可一键唤出管理菜单。
- 🤖 **Telegram Bot 自动推送**
- ⏰ **Cron 定时任务**
- 🧩 **一键安装 / 修改 / 卸载**
- 🌐 **自动识别默认网卡**
- 🧮 **单位自动换算（MB / GB / TB）**

---

## 📦 依赖环境

脚本会自动检测并安装以下依赖：

- `vnstat`, `bc`, `curl`, `cron / crond`

支持系统：

- ✅ Debian / Ubuntu, CentOS 7+, 主流 Linux 发行版

---

## 🚀 一键安装

直接在终端执行以下命令：

```bash
bash -c "$(curl -L [https://raw.githubusercontent.com/cormer932056417/vps_traffic/main/vps_vnstat_telegram.sh](https://raw.githubusercontent.com/seg932/vps_traffic/main/vps_vnstat_telegram.sh))" @ install