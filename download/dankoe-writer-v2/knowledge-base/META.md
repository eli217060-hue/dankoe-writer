# 知识库元数据

## 基本信息

| 属性 | 值 |
|------|-----|
| 创建日期 | 2024-01-15 |
| 最后更新 | 2024-01-15 |
| 版本 | 1.0.0 |
| 关联 Skill | Dan Koe Writer V2 |

## 统计数据

| 类型 | 数量 |
|------|------|
| 文章总数 | 0 |
| 视频总数 | 0 |
| 提取模式 | 0 |
| 金句数量 | 0 |

## 更新日志

### 2024-01-15
- 初始化知识库结构
- 创建基础模式库

## 学习状态

```
当前学习阶段：初始化
下次自动分析：待触发
待整合模式：无
```

## 配置选项

```yaml
# 自动分析触发条件
auto_analysis:
  trigger_count: 5      # 新增5篇内容时触发
  schedule: weekly      # 每周自动分析

# 学习保留策略
retention:
  temp_memory_days: 30  # 临时记忆保留天数
  promotion_threshold: 3 # 模式出现3次后晋升

# 内容来源
sources:
  - thedankoe.com
  - youtube.com/@DanKoeTalks
  - twitter.com/dankoe
```

## 使用指南

### 添加新文章

1. 将文章文件放入 `articles/YYYY-MM/` 目录
2. 使用标准模板格式（见 `articles/TEMPLATE.md`）
3. 更新 `articles/index.md` 索引

### 添加视频内容

1. 提取视频字幕/笔记放入 `videos/youtube-transcripts/`
2. 提取的洞察放入 `videos/video-insights/`

### 模式提取

当发现可复用的写作模式时：
1. 提取模式到对应的 `patterns/` 文件
2. 如果模式出现多次，考虑整合到主 SKILL.md

### 自我分析

手动触发分析：
```
告诉 AI：分析知识库，看看有什么新发现
```
