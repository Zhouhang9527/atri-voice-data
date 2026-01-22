# ATRI Voice Data / ATRI 语音数据

<div align="center">
  <img src="https://img.shields.io/badge/Files-1555-blue" alt="Files">
  <img src="https://img.shields.io/badge/Format-Opus-green" alt="Format">
  <img src="https://img.shields.io/badge/License-Fair_Use-yellow" alt="License">
</div>

## 📖 介绍 / Introduction

本仓库包含从游��《ATRI -My Dear Moments-》中提取的 ATRI 角色语音文件，用于 Hexo 博客看板娘功能。

This repository contains ATRI character voice files extracted from the game "ATRI -My Dear Moments-" for use in Hexo blog mascot features.

## 📁 文件结构 / File Structure

```
atri-voice-data/
├── voice/              # 语音文件目录 (1555 个 .opus 文件)
├── voice-config.json   # 语音配置文件 (含台词分类)
└── README.md           # 说明文档
```

## 🎵 语音分类 / Voice Categories

- **welcome**: 欢迎语 (22 条)
- **click**: 点击反应 (56 条)
- **hover**: 悬停提示 (184 条)
- **talk**: 对话语音 (447 条)
- **special**: 特殊语音 (889 条)

## 📥 使用方法 / Usage

### 方法1：直接下载 / Direct Download

```bash
git clone https://github.com/Zhouhang9527/atri-voice-data.git
```

### 方法2：使用 CDN / Use CDN

通过 jsDelivr 加速访问：

```
https://cdn.jsdelivr.net/gh/Zhouhang9527/atri-voice-data@main/voice/ATR_b101_001.opus
```

### 方法3：整合到 Hexo 博客 / Integrate with Hexo

1. 下载 `voice-config.json`
2. 修改配置中的 `basePath` 为 CDN 地址：
   ```json
   {
     "basePath": "https://cdn.jsdelivr.net/gh/Zhouhang9527/atri-voice-data@main/voice/"
   }
   ```
3. 将配置文件放到 `source/` 目录
4. 使用提供的 JavaScript 代码加载语音

## ⚖️ 版权声明 / Copyright

所有语音文件版权归原游戏开发商 ANIPLEX.EXE 和 枕 (Makura) 所有。

本仓库仅供个人学习和非商业用途使用。请支持正版游戏。

All voice files are copyrighted by ANIPLEX.EXE and Makura.
This repository is for personal learning and non-commercial use only. Please support the official game.

## 🎮 游戏信息 / Game Info

- **游戏名称**: ATRI -My Dear Moments-
- **开发商**: 枕 (Makura) / ANIPLEX.EXE
- **Steam**: https://store.steampowered.com/app/1230140/ATRI_My_Dear_Moments/

## 📝 更新日志 / Changelog

### 2025-12-22
- 初始发布，包含 1555 个筛选后的语音文件
- 添加配置文件和分类信息
