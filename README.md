# USBPrinterInfo

更新发布通道：更新清单 + Windows x64 下载包（USBPrinterInfo）。

- 当前版本：**1.0.0.1**（build 1）
- 最近更新：首个正式发布：修复1284设备ID未剥离长度头导致信息显示为空的问题；无设备与失败时给出下一步指引；新增自动更新检查与一键升级。

## 下载

| 用途 | 文件 |
|---|---|
| 便携版 / 自动更新载荷 | [USBPrinterInfo-1.0.0.1-win-x64.zip](https://github.com/xmuhl-tools/USBPrinterInfo-updates/releases/download/v1.0.0.1/USBPrinterInfo-1.0.0.1-win-x64.zip) |

## 校验（sha256）

```text
USBPrinterInfo-1.0.0.1-win-x64.zip
  151b0c816f6d3a8e1e39c02e7ec4a6c1057d6a265d3e909febc7a6a72d19c4e9
```

## 自动更新

程序启动时会读取本仓库的更新清单 [`update.json`](update.json)（镜像通道见清单内 `mirrors`），
按 build 号比较；发现新版本时提示下载，校验 sha256 后自动替换并重启。手动检查入口在程序主界面。

---
本文件由发布流程自动生成/更新（portable-app-release 技能，2026-09-18），请勿手工改动。
