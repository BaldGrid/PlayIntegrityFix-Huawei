# Huawei-Google-Certification-Bypass

> 华为设备谷歌认证弹窗解决方案 | 免Root | 支持鸿蒙4.2及以下

[![Version](https://img.shields.io/badge/version-2.0-brightgreen.svg)](https://github.com/yourname/Huawei-Google-Certification-Bypass)
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://github.com/yourname/Huawei-Google-Certification-Bypass)
[![ADB](https://img.shields.io/badge/ADB-Required-orange.svg)](https://developer.android.com/studio/command-line/adb)

---

## 📌 项目简介

本项目是一个 Windows 批处理脚本工具，专为**华为鸿蒙（HarmonyOS）4.2及以下**系统设计，用于解决 Google Play 服务频繁弹出**“此设备未获得Play保护认证”** 的提示问题。

**核心原理**：通过 ADB 命令清除 Google 服务相关应用数据，并禁用 Google 服务框架（GSF），使系统重新尝试认证，从而绕过弹窗干扰。

> ⚠️ **注意**：此方案并非永久 Root 破解，而是通过软件层面的重置操作临时解决问题，适合不愿解锁 Bootloader 的用户。

---

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 🔧 **一键修复认证弹窗** | 自动清除 Google Play 服务、服务框架、商店的数据，并禁用 GSF |
| 📱 **ADB 连接检测** | 实时检测手机是否已通过 USB 调试正确连接 |
| 🚀 **驱动安装辅助** | 集成 ADB/Fastboot 驱动安装入口（需手动确认） |
| 📋 **详细日志记录** | 所有操作均记录到临时日志，便于排查问题 |
| 🎨 **友好图形界面** | 彩色中文字符菜单，操作指引清晰 |

---

## 📦 文件结构
