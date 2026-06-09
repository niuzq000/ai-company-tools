# Code to Markdown · 代码转 Markdown 工具

将代码粘贴进去，选择语言，一键转换为格式化的 Markdown 代码块。纯前端、单 HTML 文件，即开即用。

## ✨ 功能

- **代码转 Markdown** — 输入代码 → 自动生成带语言标识的 Markdown 代码块（\`\`\` 格式）
- **语法高亮** — 右侧输出区可直接预览高亮效果
- **一键复制** — 点击「复制」按钮，Markdown 原文即复制到剪贴板
- **行号显示** — 左侧输入面板带行号，方便定位
- **语言选择** — 支持 JavaScript、Python、TypeScript、HTML、CSS、JSON、Bash、YAML、SQL、Markdown
- **本地存储** — 自动记住上次使用的语言
- **键盘快捷键**
  - `Ctrl+Enter` / `Cmd+Enter` — 转换
  - `Tab` — 输入 2 空格缩进
  - `Esc` — 清空输入
- **粒子背景** — 动态星云粒子动画，鼠标悬停产生交互效果
- **Toast 通知** — 复制成功时底部弹出提示
- **玻璃拟态 UI** — 毛玻璃卡片、渐变色强调、平滑过渡动画

## 🚀 使用

直接用浏览器打开 `index.html` 即可，无需安装任何依赖。

或者用本地服务器（推荐，部分浏览器剪贴板 API 需要 secure context）：

```bash
# Python
python -m http.server 8080

# Node
npx serve .
```

然后访问 `http://localhost:8080`。

## 🎨 技术栈

- 纯 HTML + CSS + JavaScript（单文件）
- [highlight.js](https://highlightjs.org/)（CDN 加载，用于预览语法高亮）
- Canvas 粒子动画（零依赖）

## 📁 文件结构

```
code-to-markdown/
├── index.html    # 主应用（单文件）
└── README.md     # 本说明
```

## 🧩 支持的编程语言

| 选项        | Markdown 标识符 |
|------------|----------------|
| JavaScript | `javascript`    |
| Python     | `python`        |
| TypeScript | `typescript`    |
| HTML       | `html`          |
| CSS        | `css`           |
| JSON       | `json`          |
| Bash       | `bash`          |
| YAML       | `yaml`          |
| SQL        | `sql`           |
| Markdown   | `markdown`      |

## 📄 License

MIT — 随便用。
