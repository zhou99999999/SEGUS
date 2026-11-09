# SEGUS 赛格斯 · 桌面版

本地私人 AI 助理（Electron 桌面壳 + Python 后端）。

## 下载安装

前往 [Releases](https://github.com/zhou99999999/SEGUS/releases) 下载最新版：

| 文件 | 说明 |
|---|---|
| `SEGUS-Desktop-Setup-<ver>-Lite.exe` | 安装器（引导） |
| `SEGUS-Desktop-Setup-<ver>-Lite-1.bin` | 分卷数据包（必须与 exe 放在同一文件夹） |
| `SHA256SUMS-<ver>.txt` | 校验和 |

> 这是 Inno Setup 分卷安装包：只下 exe 无法安装，两个文件必须同目录。

## 校验

用系统自带 certutil 算 SHA256，与 `SHA256SUMS-<ver>.txt` 逐项核对：

```
certutil -hashfile SEGUS-Desktop-Setup-1.22.2-Lite.exe SHA256
certutil -hashfile SEGUS-Desktop-Setup-1.22.2-Lite-1.bin SHA256
```
