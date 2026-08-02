下面是可直接保存为 `README.md` 的完整中英文版本：

````markdown
<h1 align="center">LightPic</h1>

<p align="center">
  <strong>拖进去 → 点导出 → 搞定。</strong>
  <br />
  <sub>Drop in → Export → Done.</sub>
</p>

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
  <a href="https://github.com/Augenstern1120/LightPic/releases/latest">
    ⬇️ 下载最新版 / Download Latest Release
  </a>
</p>

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/e290049a-704f-444c-837f-0d02b5c85bf4"
    alt="LightPic 主界面"
    width="72%"
  />
</p>

## 简介

LightPic 是一款简洁、轻量、离线运行的 macOS 批量图片缩放与压缩工具。

操作就是这么简单：拖入图片，按需调整尺寸、格式、画质或目标体积，然后点击导出，图片就处理好了。

适合发送图片、上传网站、转换格式或节省存储空间。所有图片处理均在本机完成，不会上传网络，也不会修改原图。

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

- JPEG / HEIC 的 `100%` 代表尽量少压缩，不等于保留原文件的压缩方式，因此导出文件的体积可能明显变大。日常使用建议选择 `80%–90%`，或启用目标文件体积限制。
- 分辨率（PPI/PPCM）仅影响打印尺寸和排版软件的识别，不会改变图片的像素尺寸、屏幕清晰度或文件大小。
- 高清和超清预览只影响软件内的屏幕预览清晰度，不影响最终导出的图片质量或文件大小。

## 隐私

图片处理完全在本机进行，不会上传、收集或修改原始图片。

LightPic 仅在你手动点击“检查更新”时连接 GitHub，以获取最新版本信息。

## 下载与安装

1. 前往 [Releases 页面](https://github.com/Augenstern1120/LightPic/releases/latest)
2. 在页面底部的 **Assets** 中下载 `LightPic.zip`
3. 解压后，将 `LightPic.app` 拖入“应用程序”文件夹
4. 首次打开时，右键点击 LightPic，然后选择“打开”
5. 如果 macOS 仍然阻止运行，请前往“系统设置 → 隐私与安全性”，点击“仍要打开”
6. 如果仍提示 App 已损坏或被阻止，请确认文件来自本项目的 GitHub Release，然后在终端执行：

```bash
xattr -dr com.apple.quarantine /Applications/LightPic.app
```

> 下载使用时，请选择 **Assets** 中的 `LightPic.zip`。  
> `Source code` 压缩包仅供查看或修改源码，普通用户无需下载。

---

## English

LightPic is a lightweight, offline batch image resizer and compressor for macOS.

The workflow is simple: drop in your images, adjust the dimensions, format, quality, or target file size when needed, then click Export. Done.

LightPic is ideal for sharing images, uploading them to websites, converting formats, or saving storage space. All image processing happens locally on your Mac. Images are never uploaded, and original files are never modified.

## Features

- Batch import JPEG, HEIC, PNG, and TIFF images
- Keep the original size, use long-edge presets, set a custom long edge, or specify a custom width × height
- Preserve the aspect ratio and prevent smaller images from being upscaled
- Export as JPEG, HEIC, PNG, or TIFF
- Adjust JPEG / HEIC quality and optionally set a target file-size limit
- Estimate the output dimensions and file size of the selected photo in real time
- Apply freeform or aspect-ratio cropping to individual images
- Rotate images and flip them horizontally or vertically
- Undo, redo, revert the current editing session, or restore the original image
- Four preview modes: Fast, Standard, HD, and Ultra HD
- Support sRGB, Display P3, Adobe RGB, ProPhoto RGB, DCI-P3, and Rec. 2020 color spaces
- Configure output resolution with preset or custom PPI/PPCM values
- Export selected photos or the entire list
- Prevent originals and existing files from being overwritten
- Preserve metadata supported by the selected output format
- Remember the previous export settings and output folder
- Simplified Chinese and English interfaces
- Manually check GitHub for the latest version

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

- JPEG / HEIC quality at `100%` uses minimal compression. It does not preserve the compression settings of the original file, so the exported file may be significantly larger. A quality setting of `80%–90%` is recommended for everyday use, or you can enable the target file-size limit.
- Resolution settings such as PPI and PPCM affect print dimensions and how layout applications interpret the image. They do not change the image's pixel dimensions, on-screen quality, or file size.
- HD and Ultra HD preview modes affect only the clarity of the on-screen preview. They do not affect the final export quality or output file size.

## Privacy

All image processing happens locally on your Mac. Images are never uploaded, collected, or modified.

LightPic connects to GitHub only when you manually choose **Check for Updates**.

## Download and Installation

1. Open the [Releases page](https://github.com/Augenstern1120/LightPic/releases/latest)
2. Download `LightPic.zip` from the **Assets** section at the bottom of the page
3. Unzip the file and drag `LightPic.app` into the Applications folder
4. On first launch, right-click LightPic and choose **Open**
5. If macOS still blocks the app, go to **System Settings → Privacy & Security** and choose **Open Anyway**
6. If macOS still reports that the app is damaged or blocked, confirm that it was downloaded from this project's GitHub Release page, then run:

```bash
xattr -dr com.apple.quarantine /Applications/LightPic.app
```

> Download `LightPic.zip` from the **Assets** section to use the app.  
> The `Source code` archives are intended only for viewing or modifying the source code and are not required for normal use.
````
