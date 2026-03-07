# Dan Koe Writer V5

> 研究驱动的内容积木系统，学习 Dan Koe 方法论，创作有深度的爆款内容

## 这个 Skill 做什么？

负责内容创作的**研究、结构与框架**：

1. 联网研究最新素材（每次创作都搜真实数据）
2. 生成 5 个完整大纲（含核心悖论、敌人、转变弧线、读者异议、难忘结尾）
3. 为选定大纲定向生成积木（带情感功能标签 + 质量检查）
4. 推荐 3 种情感原型写法（耐心观察者/戏剧性预言家/静默颠覆者）
5. 基于 APAG 框架生成长文 / 基于节奏示范生成短文
6. 传递给 Chinese Style Optimizer 进行文笔优化

## V5 核心改进

| 改进 | 说明 |
|------|------|
| 大纲前置 | 直接给 5 个完整大纲，不再给角度名称让用户猜 |
| 情感原型 | 同一大纲 3 种写法（观察者/预言家/颠覆者），替代 SOP 结构分类 |
| APAG 框架 | 长文默认使用 Attention → Perspective → Advantage → Gamify |
| 定向积木 | 大纲需要什么就生成什么，不再固定 8 类 32 块 |
| 情感功能标签 | 每块积木标注情感功能（颠覆认知/制造共鸣/秒懂/让人截图等） |
| 积木质量检查 | 画面感测试 / 12 岁测试 / 截图测试 / 真实性测试 |
| 攻击敌人开场 | 所有文章开头必须指出"大多数人做错了什么" |
| 策略性模糊 | 短文"保留"规则，不把所有东西说完 |
| 节奏示范 | 三种情感原型各有具体节奏模板 |
| 决策简化 | 用户决策从 3 次减少到 2 次，每次决策质量更高 |

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
- 开场钩子（5 种模式 + "攻击敌人"开场法）
- 金句公式（6 种类型 + 截图测试标准）
- 结构模式（5 种 + 短文专用 + APAG 长文框架）
- 短内容写作模式（+ 节奏示范 + 策略性模糊 + 情感弧线）

### 方法论（methods/）
- 核心方法论（身份-行为模型、目标镜头理论等）
- APAG 框架详解
- 三种情感原型

### SOP 库（参考）
反共识型、方法论型、规则列表型等（V5 中降级为参考资料）

## 使用方法

1. 将此 Skill 安装到 Claude
2. 说"我想写关于[主题]的内容"
3. AI 会引导你完成创作流程（只需做 2 次选择）

## 与 Chinese Style Optimizer 协作

- **Dankoe Writer**：负责研究、大纲、积木、情感原型、结构
- **Chinese Style Optimizer**：负责文笔、表达、金句润色

两个 Skill 配合使用，效果最佳。

## 目录结构

```
dankoe-writer/
├── SKILL.md                    # 主文件（V5 流程 + 大纲模板 + 规则）
├── README.md                   # 说明文档
└── knowledge-base/
    ├── articles/               # 7 篇文章分析
    ├── videos/                 # 视频转录
    ├── patterns/               # 写作模式库
    │   ├── titles.md
    │   ├── hooks.md            # + "攻击敌人"开场法
    │   ├── golden-phrases.md   # + 截图测试标准
    │   ├── structures.md       # + APAG 长文框架
    │   └── short-form.md       # + 节奏示范 + 策略性模糊 + 情感弧线
    ├── methods/                # 方法论框架
    │   └── dankoe-methods.md   # + APAG 详解 + 三种情感原型
    ├── sop/                    # SOP 模板（降级为参考）
    │   └── content-sop.md
    └── META.md
```

## 更新记录

- **V5.0**：大纲前置 + 情感原型 + APAG 框架 + 定向积木 + 质量检查
- **V4.0**：联网研究 + 深度追问 + 多样性检查 + 动态组装 + 去重
- **V3.2**：积木和方案的动态生成机制
- **V3.0**：7 篇文章分析、9 个 SOP
- **V2**：初始版本
