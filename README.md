建议直接用下面这版替换 README：修正了 TIFF、编辑、实时大小、隐私表述和重复链接。

```md
<h1 align="center">LightPic</h1>

<p align="center">
  <a href="https://github.com/Augenstern1120/LightPic/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/Augenstern1120/LightPic?display_name=tag&amp;label=Latest%20Version&amp;color=blue"
      alt="Latest Version"
    />
  </a>
  <a href="https://github.com/Augenstern1120/LightPic/releases/latest/download/LightPic.zip">
    <img
      src="https://img.shields.io/badge/Download-LightPic-brightgreen"
      alt="Download LightPic"
    />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Augenstern1120/LightPic/releases/latest">⬇️ 下载最新版 / Download Latest Release</a>
</p>

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/06bd64e6-03e2-4cdc-8ba1-6219464b8793"
    alt="LightPic 主界面"
    width="72%"
  />
</p>

## 简介

LightPic 是一款简洁、轻量、离线运行的 macOS 批量图片缩放与压缩工具。

拖入图片，设置尺寸、格式、画质或目标体积，再选择输出文件夹即可导出。适合发送图片、上传网站或节省存储空间。

所有图片处理均在本机完成，不会上传网络，也不会修改原图。

## 主要功能

- 批量导入 JPEG、HEIC、PNG 和 TIFF 图片
- 支持保持原始尺寸、预设长边、自定义长边与自定义宽 × 高
- 支持锁定宽高比例，避免放大小尺寸照片
- 支持 JPEG、HEIC、PNG 和 TIFF 导出
- 支持 JPEG / HEIC 画质调整和目标文件体积限制
- 实时试算当前照片的预计输出尺寸和文件大小
- 支持单张自由裁切、比例裁切、旋转和水平/垂直镜像
- 支持编辑撤销、重做、还原本次修改和恢复原图
- 提供快速、标准、高清和超清四档预览
- 支持 sRGB、Display P3、Adobe RGB、ProPhoto RGB、DCI-P3 和 Rec. 2020 色彩空间
- 支持导出分辨率设置，包括预设 PPI 与自定义 PPI/PPCM
- 支持导出所选照片或全部照片
- 自动避免覆盖原图和已有文件
- 保留目标格式支持的照片元数据
- 记住上次导出设置和输出文件夹
- 支持简体中文和英文
- 支持手动检查 GitHub 最新版本

## 快捷操作

| 操作 | 快捷键 |
| --- | --- |
| 添加照片 | `Command-O` |
| 连续选择 | `Shift-点击` |
| 多项选择 | `Command-点击` |
| 全选照片 | `Command-A` |
| 移除所选照片 | `Delete` |
| 全部导出 | `Command-Return` |
| 编辑撤销 | `Command-Z` |
| 编辑重做 | `Shift-Command-Z` |
| 应用编辑 | `Return` |
| 取消编辑 | `Esc` |

## 系统要求

- macOS 13.0 或更高版本
- Intel 或 Apple Silicon Mac

## 使用说明

- JPEG / HEIC 的 `100%` 代表尽量少压缩，不等于保留原文件的压缩方式；文件体积可能明显变大。日常建议使用 `80%–90%`，或启用目标文件体积限制。
- 分辨率（PPI/PPCM）仅影响打印尺寸和排版软件识别，不会改变图片像素、清晰度或文件大小。
- 高清和超清预览只影响屏幕预览清晰度，不影响最终导出质量或文件大小。

## 隐私

图片处理完全在本机进行，不会上传、收集或修改原始图片。

LightPic 仅在你手动点击“检查更新”时连接 GitHub 获取最新版本信息。

## 下载与安装

1. 在 [Releases 页面](https://github.com/Augenstern1120/LightPic/releases/latest) 的 **Assets** 中下载 `LightPic.zip`
2. 解压后，将 `LightPic.app` 拖入“应用程序”文件夹
3. 首次打开时，右键点击 LightPic，选择“打开”
4. 如仍被阻止，请前往“系统设置 → 隐私与安全性”，点击“仍要打开”

---

## English

LightPic is a lightweight offline batch image resizer and compressor for macOS.

Import your images, choose dimensions, format, quality, or a target file size, then select an output folder and export. It is ideal for sharing images, uploading to websites, or saving storage space.

All image processing happens locally on your Mac. Images are never uploaded, and original files are never modified.

## Features

- Batch import JPEG, HEIC, PNG, and TIFF images
- Keep original size, use long-edge presets, custom long edge, or custom width × height
- Preserve aspect ratio and prevent upscaling
- Export as JPEG, HEIC, PNG, or TIFF
- Adjustable JPEG / HEIC quality and optional target file-size limit
- Real-time output dimension and file-size estimation for the selected photo
- Per-image freeform and aspect-ratio crop, rotation, and horizontal/vertical flip
- Edit undo, redo, revert-this-session, and restore-original controls
- Four preview modes: Fast, Standard, HD, and Ultra HD
- sRGB, Display P3, Adobe RGB, ProPhoto RGB, DCI-P3, and Rec. 2020 color-space options
- Output-resolution controls with presets and custom PPI/PPCM values
- Export selected photos or the entire list
- Prevents overwriting originals and existing files
- Preserves metadata supported by the output format
- Remembers export settings and the output folder
- Simplified Chinese and English interface
- Manual GitHub update checking

## Shortcuts

| Action | Shortcut |
| --- | --- |
| Add photos | `Command-O` |
| Range selection | `Shift-click` |
| Multiple selection | `Command-click` |
| Select all photos | `Command-A` |
| Remove selected photos | `Delete` |
| Export all | `Command-Return` |
| Undo edit | `Command-Z` |
| Redo edit | `Shift-Command-Z` |
| Apply edits | `Return` |
| Cancel editing | `Esc` |

## Requirements

- macOS 13.0 or later
- Intel or Apple Silicon Mac

## Notes

- JPEG / HEIC quality at `100%` uses minimal compression. It does not preserve the original file's compression, so output files may be much larger. `80%–90%` is recommended for everyday use.
- Resolution (PPI/PPCM) affects print size and layout applications only. It does not change pixel dimensions, image quality, or file size.
- HD and Ultra HD preview modes affect on-screen preview clarity only, not export quality or output size.

## Privacy

All image processing happens locally on your Mac. Images are never uploaded, collected, or modified.

LightPic only connects to GitHub when you manually choose **Check for Updates**.

## Download and Installation

1. Download `LightPic.zip` from the **Assets** section on the [Releases page](https://github.com/Augenstern1120/LightPic/releases/latest)
2. Unzip it and drag `LightPic.app` into Applications
3. On first launch, right-click LightPic and choose **Open**
4. If macOS still blocks it, go to **System Settings → Privacy & Security** and choose **Open Anyway**
```
