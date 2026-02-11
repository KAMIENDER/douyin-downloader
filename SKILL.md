---
name: 抖音视频下载器 (Douyin Downloader)
description: 使用 Playwright 下载无水印抖音视频。
---

# 抖音视频下载器 (Douyin Downloader)

此技能允许您下载无水印的抖音视频。它使用 `playwright` 渲染页面并提取视频 URL。

## 前置条件

您需要安装 `playwright` 并下载浏览器。

```bash
pip install playwright aiohttp
playwright install chromium
```

## 使用方法

要下载视频，请使用视频 URL 运行 `scripts/download_video.py` 脚本。

```bash
python .agent/skills/douyin_downloader/scripts/download_video.py <video_url>
```

您可以选择指定输出文件路径：

```bash
python .agent/skills/douyin_downloader/scripts/download_video.py <video_url> --output <path/to/save.mp4>
```

## 示例

```bash
python .agent/skills/douyin_downloader/scripts/download_video.py "https://www.douyin.com/video/7312345678901234567"
```
