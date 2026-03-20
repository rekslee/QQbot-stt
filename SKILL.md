---
name: local-stt
description: 使用 mlx-qwen3-asr 在 Apple Silicon 上进行本地语音转文字
version: 1.0.0
author: reks
metadata:
  openclaw:
    emoji: "🎙️"
    requires:
      bins: ["python3", "ffmpeg"]
---

# Local STT - mlx-qwen3-asr

基于 mlx-qwen3-asr 的本地语音转文字技能，Apple Silicon 原生 MLX 加速。

## 调用方式

```bash
python3 {baseDir}/scripts/transcribe.py -f <音频文件路径>

