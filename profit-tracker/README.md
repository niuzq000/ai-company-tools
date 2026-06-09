# 星际贪吃蛇 ◆ STAR SNAKE

> 暗色科幻风格的经典贪吃蛇游戏 — 在星空中穿梭，收集能量晶体！

## 🎮 游戏地址

[在线试玩](https://你的用户名.github.io/snake-game/)（部署到 GitHub Pages 后可用）

## ✨ 特色

- **暗色科幻风格** — JARVIS 控制台美学，霓虹光效与全息投影感
- **粒子特效** — 吃食物时绽放粒子爆炸，蛇身拖尾光迹
- **能量晶体系统** — 普通蓝色晶体 + 金色星级能量（30分）
- **自适应难度** — 随分数增加游戏速度逐渐提升
- **排行榜** — 本地记录 Top 5 最高分（localStorage）
- **移动端适配** — 触屏滑动 + 虚拟方向键
- **完全离线** — 单 HTML 文件，零外部依赖（仅 Google Fonts 为在线资源，不影响功能）

## 🕹️ 操作方式

| 操作 | 键盘 | 移动端 |
|------|------|--------|
| 移动 | ↑↓←→ 或 WASD | 滑动屏幕 / 点击方向键 |
| 暂停 | 空格键 (Space) | - |
| 重新开始 | R 键 | 点击"再来一局" |

## 🧩 玩法规则

1. 控制蛇头移动，收集蓝色**能量晶体**（+10分）
2. 收集金色**星级能量**（+30分，限时出现）
3. 避开墙壁和自身身体
4. 分数越高速度越快
5. 连击无奖励但连续吃有快感 😄

## 📦 部署到 GitHub Pages

```bash
# 1. 在 GitHub 创建仓库（如 snake-game）
# 2. 将 index.html 推送到仓库
git init
git add index.html
git commit -m "✨ 星际贪吃蛇 v1.0"
git remote add origin https://github.com/你的用户名/snake-game.git
git push -u origin main

# 3. 在仓库 Settings → Pages 中启用
#    选择 main 分支，根目录，保存
#    等待几分钟即可访问
```

## 🛠️ 技术栈

- 纯 HTML5 + CSS3 + JavaScript
- Canvas 2D 渲染
- 无任何外部框架或库

## 📝 许可

MIT — 随意使用、修改和分享。
