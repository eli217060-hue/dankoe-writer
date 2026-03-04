# Dan Koe Writer + Chinese Style Optimizer

> 双 Skill 协作系统，创作有深度的爆款内容

---

## 两个 Skill 的分工

```
用户提出主题
     ↓
Dan Koe Writer（结构 + 内容）
├── 联网研究真实素材
├── 深度分析底层逻辑
├── 生成内容积木库（8类32块）
├── 动态匹配组装方案
└── 输出初稿
     ↓
Chinese Style Optimizer（文笔优化）
├── 去 AI 味检测
├── 口语化改写
└── 输出最终版本
```

---

## 目录结构

```
dankoe-writer/
├── README.md
├── SKILL.md                    # V4.0 主流程 + 规则
└── knowledge-base/
    ├── articles/               # 7 篇 Dan Koe 文章分析
    ├── videos/                 # 视频转录
    ├── patterns/               # 写作模式库（唯一来源）
    │   ├── titles.md
    │   ├── hooks.md
    │   ├── golden-phrases.md
    │   ├── structures.md
    │   └── short-form.md
    ├── methods/                # 方法论框架
    ├── sop/                    # SOP 模板
    └── META.md

chinese-style-optimizer/
├── README.md
├── SKILL.md                    # V2 含"去AI味"检测
├── knowledge-base/
│   └── patterns/
│       └── wording.md
└── examples/
    └── articles/mimeng/        # 9 篇咪蒙范例
```

---

## V4 核心改进

| 改进点 | 说明 |
|--------|------|
| 联网研究 | 每次创作都搜索真实数据，不凭空编造 |
| 深度追问 | AI 内部追问到底层逻辑，确保多维度 |
| 强制多样性 | 积木必须覆盖不同类型，禁止复读机 |
| 动态组装 | 同一批积木适配不同平台/篇幅 |
| 知识库去重 | 所有模式只在 patterns/ 出现一次 |

---

## 快速开始

```
用户：我想写关于"焦虑"的内容
      身份：芳疗师
      平台：小红书
      篇幅：短文

Dan Koe Writer：
[联网研究 → 提供6+切入角度 → 用户选择 → 深度分析 → 生成积木 → 推荐3个组装方案 → 生成初稿]

Chinese Style Optimizer：
[去AI味检测 → 口语化优化 → 最终版本]
```

---

## 更新记录

- **V4.0**：联网研究 + 深度追问 + 强制多样性 + 动态组装 + 知识库去重
- **V3.x**：积木系统、SOP 库、文章分析
- **V2.0**：初始版本
