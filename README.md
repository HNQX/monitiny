# Monitiny：Linux 终端实时监控脚本


轻量级、高颜值的 Linux 终端实时监控脚本，专为嵌入式设备 / 开发板 / 服务器设计，一键运行、秒级监控。

## 🌟 项目介绍

Monitiny 是一个极简的 **Linux 实时监控 Shell 脚本**，无需依赖、无需编译，直接运行即可展示完整系统状态。
专为 **NanoPC\-T4 / 开发板 / 服务器** 优化，界面美观、占用极低、支持自动刷新。

## 🖥 适用平台

- 主支持：**NanoPC\-T4 \(Debian 13\)**

- 兼容平台：

    - 全系列 ARM 开发板（OrangePi / RockPi / BananaPi 等）

    - Debian / Ubuntu / Armbian 全系

    - 树莓派 3B\+/4B/5

    - x86 Linux 服务器

## ✨运行截图

<img width="419" height="392" alt="image" src="https://github.com/user-attachments/assets/96b0db99-7531-4f70-8baf-81b1905fb8af" />


## ✨ 功能特性

- 实时监控 **CPU 使用率 \+ 动态压力条**

- 实时显示 **CPU 温度 / GPU 温度**

- 实时显示 **大小核频率**（小核 / 大核）

- **内存使用率 \+ 动态进度条** 展示

- **磁盘使用率 \+ 动态进度条** 展示

- **Docker 容器监控**（运行中数量 / 镜像统计 / 容器内存占用）

- **网络状态**（在线 / 离线自动判断）

- **实时网速**（下载 / 上传，自动切换 KB/s/ MB/s）

- **累计流量统计**

- **内网 IP 地址**

- **系统运行时间**

- 彩色终端界面，美观不花哨

- 1 秒自动刷新

- 一键安装，全局命令调用

## 🚀 快速安装

```bash
# 下载脚本
sudo wget -O /usr/bin/monitiny https://github.com/HNQX/monitiny/raw/refs/heads/main/main

# 添加执行权限
sudo chmod +x /usr/bin/monitiny
```

## 🎯 使用方法

**直接在终端输入命令即可启动：**

```bash
monitiny
```

退出：`Ctrl \+ C`

## 📁 项目结构

```Plain Text
monitiny/
├── monitiny.sh    # 主监控脚本
└── README.md      # 说明文档
```

## 🛠 命令位置

脚本安装后路径：

```Plain Text
/usr/bin/monitiny
```

系统任何路径直接输入 `monitiny` 即可运行。

## 📊 监控项一览

- 系统运行时间

- 内网 IP 地址

- 网络连接状态

- CPU 使用率 \+ 压力条

- CPU 温度 / GPU 温度

- 小核频率 / 大核频率

- 内存使用率 \+ 进度条

- 磁盘使用率 \+ 进度条

- Docker 运行容器数

- Docker 镜像统计

- Docker 内存占用

- 实时下载速度（自动单位）

- 实时上传速度（自动单位）

- 累计下载 / 上传流量

## 📝 作者与说明

- 设备：NanoPC\-T4

- 系统：Debian 13

- 脚本语言：Bash

- 界面：终端彩色 UI

- 刷新频率：1 秒

---
