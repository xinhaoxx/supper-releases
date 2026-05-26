<p align="center">
  <img src="app-icon.svg" alt="Supper" width="96" height="96" />
</p>

<h1 align="center">Supper</h1>

[English](README.en.md) | 中文

> 视频字幕批量匹配 · 文件重命名 · 纯本地离线运行

一款桌面端字幕批量重命名工具。自动识别文件名中的集数编号，将字幕文件匹配到对应视频并批量重命名，让播放器自动加载字幕。

## 下载

在 [Releases](https://github.com/xinhaoxx/supper-releases/releases) 页面下载对应平台的最新版本。

- **macOS**: 下载 `.dmg` 或 `.zip` 文件
- **Windows**: 下载 `.exe` 安装包

## 功能

1. **选择目录** — 浏览或拖入字幕/视频文件夹
2. **自动匹配** — 识别文件名中的集数编号（S01E02、1x02、第1集、E01 等）并自动匹配
3. **确认重命名** — 检查匹配结果、编辑目标文件名，一键批量重命名

### 支持的集数格式

- `S01E02`、`S01-E02`、`S01.E02`
- `1x02`、`01x02`
- `Season 01 Episode 02`
- `第1集`、`第一集`、`第1话`（含中文数字）
- `EP01`、`E01`
- 纯数字 `1.srt`、`01.ass`
- `[01].srt` 等方括号格式

### 支持的格式

**视频**: `.mkv` `.mp4` `.avi` `.mov` `.wmv` `.flv` `.webm` `.m4v` `.mpg` `.mpeg` `.ts` `.m2ts`

**字幕**: `.srt` `.ass` `.ssa` `.vtt` `.sub` `.idx` `.sup`

### 更多功能

- 复选框逐项选择参与重命名的文件
- 手动匹配未自动匹配的字幕
- 重新扫描保留已编辑的名称和选择状态
- 重命名后可一键撤销
- 简体中文 / 繁體中文 / English
- 设置页一键检查更新

## 软件截图

| 截图 | 说明 |
|---|---|
| ![step1](screenshots/step1.png) | 选择字幕和视频目录 |
| ![step2](screenshots/step2.png) | 检查匹配结果并编辑 |
| ![step3](screenshots/step3.png) | 重命名完成 |

## 反馈

有问题或建议？请到 [Issues](https://github.com/xinhaoxx/supper-releases/issues) 提交反馈。
