# DOUBAO AGENT — Boot Sequence 🚀

一个仿 **OpenAI Codex 启动动画** 风格的 AI 终端开机动画，属于豆包 Doubao 的专属启动画面。

> 纯 HTML / CSS / JavaScript，零依赖，开箱即用。

## ✨ 效果

- 🖥️ 仿 Codex 终端界面（黑底绿字霓虹风 + CRT 扫描线 + 暗角）
- 🌌 矩阵雨动态背景
- 🔤 DOUBAO ASCII 艺术 Logo，开机逐行点亮 + 故障闪烁（glitch）
- 📜 内核风格启动日志（时间戳 + 状态校验）
- 📊 动态进度条 `▰▰▰▰▰▱▱▱` + 旋转指示器 `⠋⠙⠹...`
- ⚠️ 启动彩蛋：假警告 + 加速解除
- ✦ 最终 `SYSTEM ONLINE` 高亮就绪态 + 打招呼
- 🔄 点击任意位置 / 按任意键 → 重新启动；开机过程中点击可跳过

## 🚀 快速开始

直接打开 `index.html` 即可，或者访问 GitHub Pages 在线体验：

👉 **在线体验**：`https://<你的用户名>.github.io/doubao-boot-animation/`

## 🗂️ 文件结构

```
doubao-boot-animation/
├── index.html   # 全部动画逻辑（单文件）
└── README.md
```

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 + CSS3 | 终端窗口、霓虹/CRT 特效、动画 |
| Vanilla JS | 打字机效果、进度条、矩阵雨 Canvas、开机时序编排 |
| GitHub Pages | 免费托管 |

## 📝 自定义

想改启动文字 / Logo / 颜色？直接编辑 `index.html`：
- 顶部 `:root` 变量可改主题色
- `LOGO` 常量可换 ASCII 艺术字
- `boot()` 函数里的日志文本随意替换

---

Made with ❤️ by Doubao · 灵感来自 OpenAI Codex CLI
