# Dan Koe Writer V2

基于 Dan Koe 写作方法论的 OpenClaw Skill，支持智能分析和自我提升。

---

## 核心特点

| 特点 | 说明 |
|------|------|
| **交互式工作流** | 分析→提供选项→用户选择→生成，而非直接批量生成 |
| **知识库系统** | 可持续添加新文章/视频到知识库 |
| **自我提升** | 定期分析新内容，自动优化写作能力 |
| **中文适配** | 专为中文内容创作优化 |

---

## 快速开始

### 安装

```bash
# 方式1：手动安装
git clone [此仓库] ~/.openclaw/skills/dankoe-writer

# 方式2：复制文件
cp -r dankoe-writer-v2 ~/.openclaw/skills/dankoe-writer
```

### 基本使用

```
用户：我想写关于"拖延症"的内容，给我3个方案

AI：[自动分析并返回3个选题方案]

用户：选A

AI：[生成完整文章]
```

---

## 主要功能

### 1. 智能分析与提案

不是直接生成内容，而是：
1. 分析你的主题
2. 提供多个选题方案（标题+框架+大纲）
3. 等你选择后再生成

### 2. 知识库系统

```
~/.openclaw/workspace/.dankoe-knowledge/
├── articles/          # 存放文章
├── videos/            # 存放视频内容
├── patterns/          # 写作模式库
└── insights/          # 学习笔记和金句
```

**添加新内容**：
```
用户：学习这篇文章 https://thedankoe.com/xxxxx
AI：[自动抓取、分析、学习]
```

### 3. 自我提升机制

- 知识库新增5篇内容时自动触发分析
- 可配置每周定期分析
- 识别高频模式，晋升到核心技能

### 4. 与 self-improving-agent 协同

建议同时安装 [self-improving-agent](https://clawhub.ai/pskoett/self-improving-agent)：
- 本 skill：内容分析、模式提取、知识库管理
- self-improving-agent：错误记录、用户反馈、晋升决策

---

## 文件结构

```
dankoe-writer-v2/
├── SKILL.md                    # 核心技能文件（必需）
├── SELF-IMPROVE.md             # 自我提升机制说明
├── README.md                   # 本文件
│
├── workflow/
│   └── WORKFLOW.md             # 工作流详细说明
│
└── knowledge-base/
    ├── META.md                 # 知识库元数据
    ├── articles/
    │   └── TEMPLATE.md         # 文章模板
    ├── videos/
    ├── patterns/
    │   ├── hooks.md            # 钩子模式库
    │   └── structures.md       # 结构模式库
    └── insights/
        ├── LEARNINGS.md        # 学习笔记
        └── GOLDEN-PHRASES.md   # 金句库
```

---

## 常用命令

### 内容创作

| 命令 | 说明 |
|------|------|
| `分析主题 [主题]，给我 [N] 个方案` | 获取选题方案 |
| `选择方案 [A/B/C]` | 选择并生成 |
| `写一篇关于 [主题] 的文章` | 极简模式，自动完成全流程 |

### 知识库管理

| 命令 | 说明 |
|------|------|
| `添加这篇文章到知识库：[URL]` | 学习新文章 |
| `显示知识库状态` | 查看学习进度 |
| `分析知识库，有什么新发现` | 触发自我分析 |

---

## 配置选项

在 `AGENTS.md` 中可自定义：

```markdown
## Dan Koe Writer 配置

### 自我提升设置
- 自动分析频率：每周
- 晋升阈值：出现3次
- 中文适配：必须

### 偏好设置
- 偏好框架：PASTOR
- 偏好风格：反直觉型
- 常用平台：微信公众号
```

---

## 更新日志

### v2.0.0 (2024-01-15)
- 重构为交互式工作流
- 新增知识库系统
- 新增自我提升机制
- 优化中文适配
- 支持 self-improving-agent 协同

---

## 相关资源

- [Dan Koe 官网](https://thedankoe.com/)
- [Dan Koe YouTube](https://www.youtube.com/@DanKoeTalks)
- [self-improving-agent](https://clawhub.ai/pskoett/self-improving-agent)
- [OpenClaw 官网](https://openclaw.ai)

---

*这个 Skill 会随着你添加更多 Dan Koe 的内容而持续进化。*
