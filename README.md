# 📱 ADB Tool GUI

**适用于 Android 设备的图形化调试工具**  
![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

<div align="center">
  <img src="https://img.icons8.com/color/96/000000/android-os.png" alt="ADB Logo"/>
</div>

## 🌟 功能特性

### 🔗 设备连接
- 通过 IP 地址连接/断开 ADB 设备
- 实时设备连接状态检测

### 📦 APK 管理
- 强制安装 APK 文件 (`-r -d` 参数)
- 批量卸载应用程序
- 查看已安装包列表

### ⚙️ 设备控制
- 清除应用缓存数据
- 获取 Root 权限
- 设备重启功能
- 系统分区重新挂载

### 📊 信息查询
- 应用版本号查询
- Android 系统版本检测
- 设备序列号获取

### 🖥️ 调试工具
- 实时日志抓取 (logcat)
- 自动保存 ANR 报告
- 屏幕截图功能
- 日志文件自动命名 (`月日-时分秒.log`)

## 🛠️ 安装指南

### 前置要求
- Python 3.7+
- ADB 工具 [下载地址](https://developer.android.com/studio/releases/platform-tools)
- 依赖库安装：
  ```bash

## 快速启动
git clone https://github.com/yourusername/C_ADBtools.git
cd C_ADBtools
python main.py


🖼️ 界面预览
![image](https://github.com/user-attachments/assets/8f11ef1a-98bb-4b97-b943-63545eff5321)


🚀 使用说明
基本操作流程
输入设备 IP 地址 → 点击 Connect ADB
选择 APK 文件 → 点击 Force Install
输入包名 → 执行卸载/清缓存操作
使用 Start Logcat 开始抓取日志

⚠️ 注意事项
确保设备与电脑处于同一局域网
部分功能需要开启 USB 调试模式
Root 操作可能导致设备失去保修
日志文件默认保存至 D:\ 根目录
Windows 系统建议以管理员身份运行

🤝 贡献指南
欢迎通过 Issue 和 Pull Request 参与项目改进：

Fork 本仓库
创建功能分支 (git checkout -b feature/新功能)
提交修改 (git commit -m '添加新功能')
推送更改 (git push origin feature/新功能)
创建 Pull Request

📜 开源协议
本项目采用 MIT License
