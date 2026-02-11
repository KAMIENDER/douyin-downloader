# 抖音视频下载器 (Douyin Downloader)

简单、快速的抖音无水印视频下载工具。只需提供视频链接，即可一键保存高清原片。

A simple and fast Douyin video downloader. Get high-quality, watermark-free videos with just a link.

---

## 安装 (Installation)

```bash
npx skills add <your-username>/douyin-downloader
```

## 功能 (Features)

- **无水印**: 下载最清晰的无水印原视频。
- **一键下载**: 输入链接即可自动保存。
- **简单稳定**: 专注下载，无多余配置。

## 环境准备 (Setup)

运行前请确保安装以下必要组件：

```bash
pip install playwright aiohttp
playwright install chromium
```

## 使用方法 (Usage)

在终端输入以下命令：

```bash
python .agent/skills/douyin-downloader/scripts/download_video.py "视频链接"
```

如需指定保存位置：

```bash
python .agent/skills/douyin-downloader/scripts/download_video.py "视频链接" --output /path/to/save.mp4
```
