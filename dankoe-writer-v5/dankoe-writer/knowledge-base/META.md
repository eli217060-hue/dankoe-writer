# Dan Koe Writer Knowledge Base

## 知识库概述

本知识库基于 Dan Koe 的文章、视频和播客内容创建，配合联网研究系统，用于生成有深度、有真实数据支撑的内容。

## V5 更新说明

- **核心变化**：大纲前置流程（先生成 5 个完整大纲，再定向填充积木）
- **新增**：三种情感原型（耐心观察者 / 戏剧性预言家 / 静默颠覆者）
- **新增**：APAG 长文框架（Attention → Perspective → Advantage → Gamify）
- **新增**：积木情感功能标签（颠覆认知 / 制造共鸣 / 秒懂 / 建立信任 / 让人截图 / 制造紧迫 / 提供希望）
- **新增**：积木质量检查（画面感 / 12 岁 / 截图 / 真实性测试）
- **新增**："攻击敌人"开场法（hooks.md）
- **新增**：策略性模糊 + 保留规则（short-form.md）
- **新增**：节奏示范（short-form.md）
- **新增**：金句截图测试标准（golden-phrases.md）
- **精简**：用户决策从 3 次减少到 2 次
- **降级**：SOP 从主要分类维度降级为参考材料

## 目录结构

```
knowledge-base/
├── articles/              # 7 篇 Dan Koe 文章深度分析
│   ├── 01-ai-coming-for-your-job.md
│   ├── 02-fix-your-life-in-1-day.md
│   ├── 03-multiple-interests.md
│   ├── 04-12-rules-change-life.md
│   ├── 05-death-of-thoughtful-creation.md
│   ├── 06-future-of-productivity.md
│   └── 07-death-of-value-content.md
│
├── videos/                # 视频和播客转录
│   └── video-transcript-fix-life.md
│
├── patterns/              # 写作模式库（每个模式只出现一次）
│   ├── titles.md          # 标题策略（4 种类型）
│   ├── hooks.md           # 开场钩子（5 种模式）
│   ├── golden-phrases.md  # 金句公式（6 种类型）
│   ├── structures.md      # 结构模式（5 种 + 短文专用）
│   └── short-form.md      # 短内容写作模式（新增）
│
├── methods/               # 方法论框架
│   └── dankoe-methods.md  # 核心方法论（不含模式，已移至 patterns/）
│
├── sop/                   # SOP 模板
│   └── content-sop.md     # 10 个 SOP 合并为 1 个文件
│
└── META.md                # 本文件
```

## 文件引用关系

```
SKILL.md（流程 + 规则）
    ↓ 引用
patterns/（具体模式）
    ↑ 引用
sop/content-sop.md（SOP 模板引用 patterns，不重复内容）
methods/dankoe-methods.md（方法论框架引用 patterns，不重复内容）
articles/（真实文章分析，SOP 和 patterns 的来源）
```

## 关键主题

| 主题 | 核心观点 |
|------|----------|
| 身份与行为 | 行为是身份的外在表现，改变身份才能持久改变行为 |
| 目标设定 | 目标是认知的镜头，决定你看到什么信息 |
| 多元兴趣 | 多兴趣是优势而非劣势，是现代通才的基石 |
| 创作经济 | 创作是最后的护城河，独特的视角不可复制 |
| AI 时代 | AI 消除平庸，放大独特性 |

## 更新记录

- **2026-03 V5.0**：大纲前置 + 情感原型 + APAG 框架 + 积木情感标签 + 质量检查
- **2025-01 V4.0**：知识库重组，新增 patterns/ 目录，消除重复
- **2025-01 V3.0**：初始创建，7 篇文章分析 + 9 个 SOP
