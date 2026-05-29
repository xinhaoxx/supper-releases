<p align="center">
  <picture>
    <source srcset="app-icon-white.svg" media="(prefers-color-scheme: dark)" />
    <img src="app-icon.svg" alt="Supper" width="96" height="96" />
  </picture>
</p>

<h1 align="center">Supper</h1>

[English](README.en.md) | 中文

> 视频字幕批量匹配 · 文件重命名 · 纯本地离线运行

一款桌面端字幕批量重命名工具。自动识别文件名和文件夹名中的季数集数，支持多季剧集递归扫描、压缩包解压，将字幕文件匹配到对应视频并批量重命名，让播放器自动加载字幕。

## 下载

在 [Releases](https://github.com/xinhaoxx/supper-releases/releases) 页面下载对应平台的最新版本。

- **macOS**: 下载 `.dmg` 文件（ARM64），Intel 用户也可使用
- **Windows**: 下载 `.msi` 安装包

## 功能

### 核心流程

1. **选择目录或压缩包** — 浏览/拖入字幕目录或 .zip/.rar/.7z 压缩包，选择视频目录
2. **自动扫描匹配** — 递归扫描子文件夹，识别季数集数并自动匹配
3. **检查并重命名** — 按季分组查看结果、编辑文件名，一键批量重命名或复制重命名

### 亮点特性

- **多季批量匹配** — 支持 S01/S02、Season 1/Season 2、第一季/第二季等子文件夹结构，自动递归扫描
- **按季分组展示** — 匹配结果按季折叠，清晰查看每季内容
- **压缩包支持** — 字幕目录支持 .zip/.rar/.7z 格式，嵌套压缩包自动逐层解压
- **季号冲突检测** — 同一扫描范围内出现多个同季文件夹时自动提示
- **文件夹名识别** — 文件名无季号时自动从文件夹名（S01、Season 1、第一季等）补全
- **复制并重命名** — 将字幕复制到视频目录后重命名，不修改原始文件
- **深色模式** — 支持自动/浅色/深色三种外观模式

### 支持的集数格式

- `S01E02`、`S01-E02`、`S01.E02`
- `1x02`、`01x02`
- `Season 01 Episode 02`
- `第1集`、`第一集`、`第1话`（含中文数字）
- `EP01`、`E01`
- 纯数字 `1.srt`、`01.ass`
- `[01].srt` 等方括号格式

### 支持的文件格式

**视频**: `.mkv` `.mp4` `.avi` `.mov` `.wmv` `.flv` `.webm` `.m4v` `.mpg` `.mpeg` `.ts` `.m2ts`

**字幕**: `.srt` `.ass` `.ssa` `.vtt` `.sub` `.idx` `.sup`

**压缩包**: `.zip` `.rar` `.7z`

### 更多功能

- 复选框逐项选择参与重命名的文件
- 手动匹配未自动匹配的字幕
- 搜索过滤已匹配列表
- 单行/多行编辑模式切换
- 重新扫描保留已编辑的名称和选择状态
- 重命名后可一键撤销，支持批量回退
- 简体中文 / 繁體中文 / English
- 设置页一键检查更新

## 软件截图

<p align="center">
  <img src="screenshots/home.png" alt="首页" />
  <br><sub>首页 — 深色 / 浅色模式</sub>
</p>

<p align="center">
  <img src="screenshots/drag.png" alt="选择目录" />
  <br><sub>选择字幕和视频目录，支持压缩包</sub>
</p>

<p align="center">
  <img src="screenshots/match.png" alt="扫描匹配" />
  <br><sub>递归扫描、自动识别季数集数并匹配</sub>
</p>

<p align="center">
  <img src="screenshots/review.png" alt="检查结果" />
  <br><sub>按季分组查看结果、编辑目标文件名</sub>
</p>

<p align="center">
  <img src="screenshots/done.png" alt="操作完成" />
  <br><sub>重命名完成，可撤销或查看详情</sub>
</p>

## 反馈

有问题或建议？请到 [Issues](https://github.com/xinhaoxx/supper-releases/issues) 提交反馈。
