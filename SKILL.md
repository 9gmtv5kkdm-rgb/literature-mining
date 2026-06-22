---
name: literature-mining
slug: literature-mining
version: 1.0.0
displayName: 文献挖掘与笔记
summary: 文献阅读方法论工具包——结构化笔记、文献矩阵、Gap识别、质量评价，帮你把文献"读透"而非"搜到"。
description: |
  # 文献挖掘与阅读笔记 (Literature Mining & Reading Notes)
  
  一个专注于**文献阅读方法论**的技能工具包，提供结构化阅读笔记模板、文献矩阵构建法、研究Gap系统识别框架、PRISMA流程图生成、证据质量分级体系和检索策略构建方法。
  
  本技能**不是搜索引擎**——它不负责查找文献，而是教你如何**深度阅读、横向比较、识别研究空白、评估证据质量**。
  
  ## 触发词 / Triggers
  文献阅读 / 阅读笔记 / literature mining / 文献矩阵 / PRISMA / research gap / 文献质量评价 / reading notes / 结构化笔记 / 文献对比 / 证据分级 / 检索策略 / Gap识别 / 深度阅读 / 快速浏览
  
  ## 适用场景
  - 撰写文献综述前的系统化阅读准备
  - 博士/硕士开题时的研究Gap识别
  - 论文返修时需要补充论证文献覆盖度
  - 进入新研究领域时的文献快速消化
  - 构建理论框架时的方法论质量把关
---

# 文献挖掘与阅读笔记 (Literature Mining & Reading Notes)

## 定位与关系

### 本技能是什么

`literature-mining` 是**"阅读文献的方法论工具包"**。它回答的问题是：

> *"我已经找到了一批论文——现在怎么高效地从中提取信息、构建知识体系、找到研究空白？"*

### 与已有技能的关系

SkillHub 上已有多个优秀的文献检索技能：

| 技能 | 核心功能 |
|------|----------|
| `literature-review` v1.2.0 | 检索 Semantic Scholar / OpenAlex / Crossref / PubMed |
| `literature-reviewer-skill` v3.0 | 检索 CNKI / WoS / ScienceDirect，8阶段工作流 |
| `literature-search` v1.0.3 | 检索 8 大数据库 |
| `literature-manager` v1.1.1 | 搜 + 下 + 转 + 整 + 审全套管理 |

**这些技能负责"找文献"——本技能负责"读文献"。**

它们是互补关系：先用 `literature-review` 或 `literature-reviewer-skill` 检索到目标文献集合，再用本技能提供的工具包进行系统化精读和分析。

```
检索技能 (找到文献)          本技能 (读懂文献)
──────────────────────       ──────────────────────
literature-review            → 结构化阅读笔记
literature-reviewer-skill    → 文献矩阵构建
literature-search            → Research Gap 识别
literature-manager           → 证据质量评价
                              → PRISMA 流程图
                              → 检索策略设计
```

## 快速开始

根据你的需求，选择对应的参考文件：

| 你的需求 | 参考文件 |
|----------|----------|
| 不知道怎么做阅读笔记 | `references/reading-notes.md` |
| 想横向比较多篇文献发现规律 | `references/literature-matrix.md` |
| 想找到研究空白(Gap) | `references/gap-identification.md` |
| 需要画PRISMA流程图 | `references/prisma-guide.md` |
| 想评估文献证据质量 | `references/evidence-hierarchy.md` |
| 想设计检索策略 | `references/search-strategy.md` |

## 推荐工作流

1. **检索策略设计** → 阅读 `references/search-strategy.md`，用 PICO 框架明确检索范围
2. **文献检索** → 使用 `literature-review` / `literature-reviewer-skill` 执行检索
3. **PRISMA 筛选记录** → 阅读 `references/prisma-guide.md`，记录筛选过程并生成流程图
4. **结构化阅读** → 阅读 `references/reading-notes.md`，对核心文献深度阅读，对次要文献快速浏览
5. **文献矩阵构建** → 阅读 `references/literature-matrix.md`，横向比较所有纳入文献
6. **Gap 识别** → 阅读 `references/gap-identification.md`，从矩阵中系统性发现研究空白
7. **证据质量评价** → 阅读 `references/evidence-hierarchy.md`，对纳入文献进行证据分级

## 参考文献索引

```yaml
reading-notes: references/reading-notes.md
literature-matrix: references/literature-matrix.md
gap-identification: references/gap-identification.md
prisma-guide: references/prisma-guide.md
evidence-hierarchy: references/evidence-hierarchy.md
search-strategy: references/search-strategy.md
```
