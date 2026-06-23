<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Zero_Dependencies-✓-brightgreen?style=for-the-badge" alt="Zero Dependencies">
</p>

<h1 align="center">🔮 塔罗牌占卜</h1>

<p align="center">
  <strong>基于 78 张塔罗牌的在线交互式占卜工具</strong><br>
  深色紫红配色 · 3D 翻牌动画 · 6 种场景 · 4 种牌阵 · 完整正逆位解读
</p>

<p align="center">
  <a href="https://nutshell319.github.io/tarot-divination/"><strong>🔗 立即体验</strong></a>
  &nbsp;·&nbsp;
  <a href="#-功能特性">功能特性</a>
  &nbsp;·&nbsp;
  <a href="#-使用方法">使用方法</a>
  &nbsp;·&nbsp;
  <a href="#-牌阵介绍">牌阵介绍</a>
</p>

---

## ✨ 功能特性

<table>
  <tr>
    <td width="50%">
      <h4>🎯 6 种占卜场景</h4>
      <ul>
        <li>🧭 人生方向与成长</li>
        <li>💔 情感与人际关系</li>
        <li>💼 事业与工作</li>
        <li>💰 财务与物质</li>
        <li>🧘 灵性与内在探索</li>
        <li>🏥 身心健康</li>
      </ul>
    </td>
    <td width="50%">
      <h4>📐 4 种占卜牌阵</h4>
      <ul>
        <li><strong>单张牌阵</strong> — 每日指引、快速解答</li>
        <li><strong>三张牌阵</strong> — 过去·现在·未来</li>
        <li><strong>关系牌阵</strong> — 双人 7 张深度分析</li>
        <li><strong>六芒星阵</strong> — 7 张全方位问题拆解</li>
      </ul>
    </td>
  </tr>
</table>

### 核心亮点

| 特性 | 说明 |
|------|------|
| 🃏 **完整牌组** | 78 张全量数据：22 张大阿卡纳 + 56 张小阿卡纳（四花色数字牌+宫廷牌） |
| 🔄 **正逆位系统** | 每张牌独立判定正逆位，解读自动适配 |
| 🎴 **3D 翻牌动画** | CSS perspective + rotateY 实现真实翻牌效果 |
| 🔀 **洗牌动画** | Fisher-Yates 随机算法 + 洗牌过渡动画 |
| 📖 **多层解读** | 逐张解读 + 元素分析 + 牌面联动 + 行动建议 + 结语 |
| 🎨 **深色主题** | 紫红配色，视觉优雅，适合沉浸式体验 |
| 📱 **响应式设计** | 手机、平板、桌面全适配 |
| 📄 **零依赖** | 纯 HTML/CSS/JS，单文件，浏览器直接打开 |

---

## 🚀 使用方法

### 在线使用
直接访问：**[nutshell319.github.io/tarot-divination](https://nutshell319.github.io/tarot-divination/)**

### 本地使用
```bash
git clone https://github.com/nutshell319/tarot-divination.git
cd tarot-divination
# 直接用浏览器打开 index.html 即可
```

### 占卜流程

```
首页 → 选择场景 → 选择牌阵 → 洗牌 → 抽牌 → 逐张翻牌 → 查看最终总结
```

1. **选择场景** — 确定你想探索的人生领域
2. **选择牌阵** — 根据问题类型选择合适的牌阵
3. **洗牌默念** — 集中注意力，默念你的问题
4. **翻牌解读** — 点击每张牌查看正逆位含义
5. **综合总结** — 查看元素分析、牌面联动和行动建议

---

## 📐 牌阵介绍

### 单张牌阵（1 张）
> 一张牌直指核心，适合每日指引和快速解答。

### 三张牌阵（3 张）
> 过去 → 现在 → 未来 的经典时间线分析。

### 关系牌阵（7 张）
> 分别解读你（感受·想法·行为）和对方（感受·想法·行为）各三张牌，加上一张关系走向牌。

### 六芒星阵（7 张）
> 全方位拆解：现状 → 挑战 → 根基 → 远景 → 过去 → 近期未来 → 最终结果。

---

## 🎨 界面预览

```
┌─────────────────────────────────────────┐
│            🔮 塔罗牌占卜                  │
│         倾听内心的声音，照亮前行的路        │
│                 ━━━━                    │
│                                         │
│   ┌─────┐  ┌─────┐  ┌─────┐           │
│   │ 🧭  │  │ 💔  │  │ 💼  │           │
│   │人生 │  │情感 │  │事业 │  ...      │
│   └─────┘  └─────┘  └─────┘           │
│         选择你的占卜场景                  │
│                                         │
│   ┌──────────────────┐                 │
│   │  ★  牌背  ★  │  ← 点击翻牌        │
│   │    ✧    ✧    │                   │
│   └──────────────────┘                 │
│                                         │
│   📋 最终总结解读                        │
│   ┌──────────────────────────┐         │
│   │ 火元素主导...             │         │
│   │ 🔗 牌面联动分析           │         │
│   │ 🎯 关键行动建议           │         │
│   └──────────────────────────┘         │
└─────────────────────────────────────────┘
```

---

## 🛠 技术栈

| 技术 | 用途 |
|------|------|
| **HTML5** | 页面结构 |
| **CSS3** | 样式、动画、3D 变换、响应式布局 |
| **Vanilla JS** | 业务逻辑、牌组管理、DOM 操作 |
| **GitHub Pages** | 静态托管部署 |

### 技术亮点

- **CSS 3D Transforms** — `perspective` + `rotateY(180deg)` + `backface-visibility` 实现无 JS 动画库的翻牌
- **Fisher-Yates 洗牌** — O(n) 时间复杂度，真随机分布
- **智能解读引擎** — 四元素统计 → 牌间关系串联 → 场景匹配 → 行动建议生成
- **CSS Variables** — 统一配色管理，易于定制主题

---

## 📁 项目结构

```
tarot-divination/
├── index.html          # 完整应用（单文件，CSS/JS 全部内联）
├── README.md           # 项目说明
└── .gitignore
```

---

## 🔧 自定义与扩展

### 修改配色
编辑 `index.html` 中 `:root` 的 CSS 变量：
```css
:root {
  --bg: #08090d;        /* 背景色 */
  --purple: #b98eff;    /* 主色 */
  --accent: #e85d75;    /* 强调色 */
  --text: #f6f2e8;      /* 文字色 */
}
```

### 添加新牌阵
在 `SPREADS` 对象中按格式添加新牌阵，并在 `dealCards()` 中实现对应的布局逻辑。

---

## ⚠️ 免责声明

塔罗牌是一种自我反思和内在探索的工具，**不替代专业心理咨询、医疗诊断或法律建议**。占卜结果仅供娱乐和参考，最终的人生决策权永远在你自己手中。

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源。

---

<p align="center">
  Made with ✨ by <a href="https://github.com/nutshell319">nutshell319</a>
</p>
