# 微型桌面Delta分拣机器人 - 创业项目

<div align="center">

![DeltaSort AI](https://img.shields.io/badge/DeltaSort-AI--Powered%20Sorting-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![Status](https://img.shields.io/badge/Status-Prototyping-orange)

**桌面级 AI 分拣 Delta 机器人，你的不眠不休"超级实验助手"**

[📖 市场调研报告](research.md) •
[🚀 项目落地页](http://localhost:8080/index.html) •
[📋 用户调研问卷](http://localhost:8080/index.html#survey)

</div>

---

## 项目简介

本项目是一个**大学生创新创业项目**，专注于解决科研实验室和小批量精密制造场景中的**微小零件手工分拣痛点**。

我们正在开发一款**微型桌面Delta分拣机器人**，搭载AI视觉识别系统与柔顺控制算法，能够自动识别并分拣**0.5-5mm规格**的微小零件（如贴片电阻、电容、微型弹簧、钟表齿轮、微球、种子等）。

> **核心定位**：将工业级柔性制造能力，以消费级的价格带到每一个实验室桌面

---

## 🎯 目标用户

| 用户群体 | 典型场景 | 核心需求 |
|---------|---------|---------|
| **科研实验室** | 高校材料/化学/生物课题组 | 实验样品分拣、新材料选型 |
| **精密制造** | 钟表/珠宝小批量试产 | 微小零件分类、质量检测 |
| **电子研发** | 硬件初创公司原型验证 | SMT元件分拣、芯片引脚检测 |
| **教育机构** | 机器人/AI专业教学演示 | Delta机构原理教学、机器视觉实验 |

**初期切入重点**：**985/211 高校材料科学与工程实验室**

---

## ✨ 核心功能

### 🤖 AI 视觉与机器人系统

| 功能模块 | 技术规格 |
|---------|---------|
| **AI 显微视觉系统** | 99.5% 分拣准确率，最小识别 0.5mm，自动检测正反面/缺口/异色缺陷 |
| **柔顺抓取执行器** | 力控算法 + 仿生吸嘴，真空/静电自适应切换，无损拾取光滑零件 |
| **Delta 并联机构** | 高 15cm / 底座 10×10cm，轻量化碳纤维/鱼线结构，120次/分钟节拍 |
| **万能料盘系统** | 5分钟任务切换，支持标准96孔板，快拆吸嘴适配各类零件 |

### 📊 高转化率落地页

项目包含一个专业级单页网站（Landing Page）：

- [index.html](file:///d:/trae/微型Delta分拣机器人_AI调研报告/index.html) - 纯 HTML + Tailwind CSS 实现
- **5大核心板块**：Hero 首屏 → 痛点分析 → 解决方案 → 工作流预览 → 预约演示表单
- **用户调研模块**：姓名/年级/专业/体验意愿/关心问题/联系方式
- 完全响应式设计，完美适配手机端/平板/PC

---

## 🚀 如何本地打开

### 方式一：直接双击打开（最简单）

```bash
1. 进入项目文件夹
cd d:\trae\微型Delta分拣机器人_AI调研报告

2. 直接双击文件
- index.html          # 打开落地页（推荐）
- research.md         # 用 Typora/VS Code 查看调研报告
- research.docx       # 用 Word 打开报告
```

### 方式二：本地预览服务器（最佳体验）

```bash
# 启动 Python 本地服务器（端口 8080）
cd d:\trae\微型Delta分拣机器人_AI调研报告
py -m http.server 8080

# 浏览器访问：
# - 首页：http://localhost:8080/index.html
# - 用户调研：http://localhost:8080/index.html#survey
# - 预约演示：http://localhost:8080/index.html#cta
```

### 方式三：在线分享给他人

使用免费托管服务一键生成永久链接：

| 服务 | 操作步骤 |
|-----|---------|
| **Netlify Drop** | 1. 打开 https://app.netlify.com/drop<br>2. 拖拽 index.html 上传<br>3. 获取 `*.netlify.app` 链接 |
| **Vercel** | 1. 打开 https://vercel.com/new<br>2. GitHub 登录后上传 index.html<br>3. 获取 `*.vercel.app` 链接 |
| **GitHub Pages** | 1. 创建 GitHub 仓库<br>2. 上传 index.html<br>3. 在 Settings 开启 Pages |

---

## 📁 项目文件结构

```
d:\trae\微型Delta分拣机器人_AI调研报告\
├── index.html              # ✅ 高转化率落地页（单页网站）
├── research.md             # ✅ RBTR框架完整调研报告
├── research.docx           # ✅ Word版调研报告
├── sources.md              # ✅ 数据来源汇总（47个参考）
├── README.md               # 本说明文件
├── generate_report.py      # 报告自动生成脚本
└── data\
    ├── raw_links.txt       # 原始参考链接列表
    └── collected_notes.md  # 调研过程笔记
```

---

## 📋 下一步计划

### 第一阶段：技术验证（2026.5 - 2026.6）

- [x] **完成**：市场调研报告 + 项目落地页
- [ ] **进行中**：用户调研问卷投放（收集 50+ 有效反馈）
- [ ] **优先做**：核心技术验证 Demo
  - 物理抓取测试：用吸嘴抓取 0.5mm、1mm、2mm、5mm 零件
  - 视觉识别测试：USB 显微摄像头 + OpenCV 识别准确率测试
- [ ] 寻找联合创始人（补充视觉/AI能力）

### 第二阶段：原型开发（2026.7 - 2026.9）

- [ ] Delta 机构 3D 打印原型
- [ ] 视觉算法训练（至少 3 类零件）
- [ ] 第一版可演示样机
- [ ] 参加大学生创新创业大赛

### 第三阶段：产品化（2026.10 - 2027.2）

- [ ] 5 台 Alpha 样机送测（5-10个合作实验室）
- [ ] 收集用户反馈迭代
- [ ] BOM 成本优化（目标成本 1500 元以内）
- [ ] 小批量试产（首批 50 台）

---

## 🔗 相关资源

### 内部文档

- [research.md](file:///d:/trae/微型Delta分拣机器人_AI调研报告/research.md) - RBTR 框架完整市场调研报告
- [sources.md](file:///d:/trae/微型Delta分拣机器人_AI调研报告/sources.md) - 所有数据来源汇总（47个参考链接）
- [data/collected_notes.md](file:///d:/trae/微型Delta分拣机器人_AI调研报告/data/collected_notes.md) - 调研笔记

### 快速访问

| 内容 | 本地链接 | 说明 |
|-----|---------|------|
| 落地页首页 | `index.html` | 展示给潜在用户/投资人 |
| 用户调研 | `index.html#survey` | 收集用户反馈 |
| 预约演示 | `index.html#cta` | 转化首批内测用户 |

---

## 💡 说明与免责

本项目是**大学生创新创业训练项目**，所有市场分析、技术方案均基于公开信息整理。

- **调研报告数据**：部分估算数据标注有"非官方数据"字样，仅供参考
- **落地页表单**：当前为前端演示版本，数据仅打印到控制台，实际使用需对接后端
- **知识产权**：项目方案为公开学习交流使用，如借鉴请注明出处

---

## 📞 联系我们

如果您对这个项目感兴趣：

- **作为用户**：填写 [用户调研问卷](http://localhost:8080/index.html#survey)，优先获得内测资格
- **作为伙伴**：欢迎机电/视觉/算法方向同学加入团队
- **作为导师**：期待专家学者提供指导建议

---

<div align="center">

**Made with ❤️ by 大学生创新创业团队**

*最后更新：2026年5月21日*

</div>
