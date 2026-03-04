# Dan Koe Writer V4

> 研究驱动的内容积木系统，学习 Dan Koe 方法论，创作有深度的爆款内容

## 这个 Skill 做什么？

负责内容创作的**研究、结构与框架**：

1. 联网研究最新素材（每次创作都搜真实数据）
2. 提供切入角度选项（基于研究结果，不是凭空编的）
3. 深度分析底层逻辑（AI 内部追问，找到多维度支撑）
4. 生成内容积木库（8 类 32 块，强制多样性检查）
5. 动态匹配组装方案（根据平台/篇幅从 SOP 库中挑选）
6. 传递给 Chinese Style Optimizer 进行文笔优化

## V4 核心改进

| 改进 | 说明 |
|------|------|
| 联网研究 | 每次创作搜索 3-6 次，获取真实数据和案例 |
| 深度追问 | AI 内部分析角度的底层逻辑，防止"一个观点翻来覆去说" |
| 多样性检查 | 积木和组装方案都有硬约束，不通过则重新生成 |
| 动态组装 | 积木全量生成，根据平台/篇幅动态挑选，一次研究多次产出 |
| 知识库去重 | 所有模式只在 patterns/ 出现一次，消除 3 处重复 |

## 知识库内容

### 文章分析（7 篇）
- The Unpleasant Truth: AI Is Coming For Your Job
- How to fix your entire life in 1 day
- If you have multiple interests, do not waste the next 2-3 years
- 12 rules to change your life in 12 months
- The Death Of Thoughtful Creation
- The Future Of Productivity
- The death of value-based content

### 写作模式库（patterns/）
- 标题策略（4 种类型）
- 开场钩子（5 种模式）
- 金句公式（6 种类型）
- 结构模式（5 种 + 短文专用）
- 短内容写作模式（新增）

### SOP 库（10 个）
反共识型、方法论型、规则列表型、钩子库、金句库、对比表格、行动号召、引用权威、标题公式、内容积木

## 使用方法

1. 将此 Skill 安装到 Claude
2. 说"我想写关于[主题]的内容"
3. AI 会引导你完成创作流程

## 与 Chinese Style Optimizer 协作

- **Dankoe Writer**：负责研究、结构、框架、积木
- **Chinese Style Optimizer**：负责文笔、表达、金句

两个 Skill 配合使用，效果最佳。

## 目录结构

```
dankoe-writer/
├── SKILL.md                    # 主文件（流程 + 规则）
├── README.md                   # 说明文档
└── knowledge-base/
    ├── articles/               # 7 篇文章分析
    ├── videos/                 # 视频转录
    ├── patterns/               # 写作模式库（去重后唯一来源）
    │   ├── titles.md
    │   ├── hooks.md
    │   ├── golden-phrases.md
    │   ├── structures.md
    │   └── short-form.md
    ├── methods/                # 方法论框架
    │   └── dankoe-methods.md
    ├── sop/                    # SOP 模板
    │   └── content-sop.md
    └── META.md
```

## 更新记录

- **V4.0**：联网研究 + 深度追问 + 多样性检查 + 动态组装 + 去重
- **V3.2**：积木和方案的动态生成机制
- **V3.0**：7 篇文章分析、9 个 SOP
- **V2**：初始版本
