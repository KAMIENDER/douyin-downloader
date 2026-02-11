# 抖音视频下载器 (Douyin Downloader)

这是一个专为 OpenClaw 设计的抖音视频下载工具。它利用 Playwright 深度模拟浏览器行为，能够稳定绕过反爬和 WAF 挑战，一键获取并下载抖音无水印原画视频。无论是用于素材采集、数据分析还是 AI 诊断，它都是你的得力助手。

A specialized Douyin video downloader for OpenClaw, utilizing Playwright to simulate browser behavior and reliably bypass anti-bot and WAF challenges. Get watermark-free, high-quality videos with a single command—perfect for content collection or AI analysis.

---

## 安装 (Installation)

```bash
npx skills add <your-username>/douyin-downloader
```

## 功能特性 (Features)

- **无水印下载**: 自动解析并获取抖音无水印原画视频链接。
- **强力绕过**: 使用 Playwright 模拟真实浏览器行为，有效应对 WAF 验证。
- **异步处理**: 基于 Python 异步 IO，下载过程高效流畅。
- **简单易用**: 支持命令行调用，可轻松集成到其他自动化流程中。

## 依赖要求 (Dependencies)

- Python 3.10+
- Playwright
- aiohttp

请确保已安装必要的依赖：

```bash
pip install playwright aiohttp
playwright install chromium
```

## 使用方法 (Usage)

直接运行下载脚本并提供视频链接：

```bash
python .agent/skills/douyin-downloader/scripts/download_video.py "https://v.douyin.com/xxx/"
```

指定输出路径：

```bash
python .agent/skills/douyin-downloader/scripts/download_video.py "视频链接" --output /path/to/save.mp4
```
