# Changelog

All notable changes to **openEggle** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-11-27

### Added
- **原生 GPU 零 CGO 架构**：基于 MyGo v0.10.0 与 Satin 设计系统构建，零 WebView、零 CGO，支持 macOS / Windows / Linux 极速冷启动。
- **极速粘贴与拖放入库**：支持截图、图片文件、纯文本、Markdown、代码与链接自动识别落盘，内置 SHA-256 精确去重与原子写入。
- **悬停极速复制**：鼠标移至任意图片或文字卡片（支持瀑布流、规整网格、紧凑列表）无需先点击选中，直接按 `Ctrl+C` / `⌘C` 即可复制到剪贴板；按 `Ctrl+Shift+C` / `⌘⇧C` 复制原图绝对路径。
- **多视图布局与 FLIP 动效**：支持瀑布流（`⌘1`）、规整网格（`⌘2`）、紧凑列表（`⌘3`）丝滑切换，侧栏高斯半透明毛玻璃与开合丝滑重排。
- **树形合集与全文检索**：支持无限级嵌套树形文件夹、拖拽/右键移动层级、防环校验、面包屑路径与 SQLite FTS5 全文检索。
- **沉浸看图器与详情抽屉**：支持双击缩放、拖拽平移、旋转还原、缩略图胶片条、Markdown 预览与标签编辑。
- **Satin 物理微动效体系**：全套原生抽屉滑入滑出、弹窗缩放/标题栏拖拽/防误关轻顶、分段控件与 Tabs 双沿液态拉伸、输入框聚焦光环生长与报错轻抖、底部液态 Toast 弹入退场。
- **系统状态栏常驻与全局快采**：支持关闭窗口常驻状态栏、`⌘⇧V` 全局后台快采剪贴板。
- **在线签名更新**：内置 Ed25519 签名验证与 bsdiff 增量在线更新，支持启动自动静默检查、实时下载进度与一键重启更新。
