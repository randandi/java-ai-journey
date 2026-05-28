# Java AI Journey

> 一个 10 年 Java 后端工程师转型 AI 工程化的公开学习日志 · 2026.06 启动

[![Java](https://img.shields.io/badge/Java-21-007396?logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring AI](https://img.shields.io/badge/Spring%20AI-1.x-6DB33F?logo=spring&logoColor=white)](https://spring.io/projects/spring-ai)
[![PgVector](https://img.shields.io/badge/PgVector-latest-336791?logo=postgresql&logoColor=white)](https://github.com/pgvector/pgvector)
[![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-000000)](https://modelcontextprotocol.io/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 关于本仓库

这是一个**真实的、按周推进的学习仓库**，记录我在 12 个月内系统转型 AI 工程化的全部过程：

- 不是教程，是**实战代码 + 踩坑笔记 + 技术博客**的合集
- 不学算法本身（不手撕 Transformer、不训模型），专注**应用层架构**
- 所有项目都跑得起来、有 README、有架构图
- 所有博客同步发布到 [掘金](https://juejin.cn)（链接见下方索引）

---

## 关于作者

- 10 年 Java 后端开发经验
- 历经单体 / 微服务 / 高并发 / 中间件多个阶段
- 现专注：**Spring AI · RAG · Agent · MCP · 大模型应用架构**
- 信奉一句话："**AI 时代，工程能力是最稀缺的护城河**"

---

## 12 个月路线图

| 阶段 | 时间 | 主题 | 核心产出 |
|------|------|------|---------|
| **Q1** | 2026.06 - 08 | Spring AI 打地基 | 第一个 RAG（v0.1 → v0.4）+ MCP 集成 |
| **Q2** | 2026.09 - 11 | 生产级 RAG 深耕 | 多路召回 + Rerank + Ragas 评估 |
| **Q3** | 2026.12 - 2027.02 | Agent 进阶 | Function Calling + Multi-Agent + 落地项目 |
| **Q4** | 2027.03 - 05 | 架构沉淀 | 《大模型应用 Java 架构实践》文档 + 公开分享 |

---

## 进度追踪

### 2026 年 6 月（进行中）

> 主题：**Spring AI 入门 + 第一个 RAG**

| 周次 | 时间 | 目标 | 状态 |
|------|------|------|------|
| Week 1 | 06/01 - 06/07 | 环境 + Hello World | ⏳ 待开始 |
| Week 2 | 06/08 - 06/14 | Spring AI 核心抽象 | ⏳ |
| Week 3 | 06/15 - 06/21 | Embedding + PgVector | ⏳ |
| Week 4 | 06/22 - 06/28 | RAG v0.1 完工 | ⏳ |
| Week 5 | 06/29 - 06/30 | 月度复盘 | ⏳ |

详细计划见 [`docs/2026-06.md`](./docs/2026-06.md)（同步链接到学习计划仓库）

---

## 项目清单

> 每完成一个项目，在这里追加一行。

| 项目 | 技术栈 | 状态 | 链接 |
|------|--------|------|------|
| `rag-v0` 内部知识助手 | Spring AI + PgVector + DeepSeek | 🔧 开发中 | 待发布 |
| `rag-v1` 生产级 RAG | + Rerank + Ragas + Langfuse | 📅 计划 Q2 | - |
| `agent-v1` 落地 Agent | + Function Calling + MCP | 📅 计划 Q3 | - |

---

## 博客索引

> 同步发布到掘金，每周至少 1 篇。

### 2026 年 6 月
- 待发布｜《2026 年，一个 Java 程序员决定学 AI》
- 待发布｜《Spring AI 核心抽象一篇看懂：从 ChatClient 到 Advisor》
- 待发布｜《Java 程序员的向量数据库入门：从 Embedding 到检索》
- 待发布｜《用 Spring AI 一周搭出 RAG 应用：从 0 到 1 完整代码》

---

## 技术栈选型（已锁定）

| 类别 | 主选 | 说明 |
|------|------|------|
| AI 框架 | **Spring AI 1.x** | Java 生态主流，与 Spring Boot 无缝集成 |
| 模型 API | **DeepSeek** | 性价比高 + 中文好 + OpenAI 协议兼容 |
| 向量数据库 | **PgVector** | Postgres 插件，运维零成本 |
| 可观测性 | **Langfuse** | 开源 LLM 应用观测平台 |
| 协议 | **MCP** | Anthropic 提出，2025 年事实标准 |
| 备选框架 | LangChain4j | 知识储备 |

---

## 仓库结构

```
java-ai-journey/
├── README.md                  # 本文件
├── docs/                      # 学习计划与复盘
│   ├── 2026-06.md            # 6 月详细周计划
│   └── ...                   # 后续按月追加
├── rag-v0/                    # 项目 1：内部知识助手
│   ├── README.md
│   ├── docker-compose.yml    # 一键启动依赖
│   ├── src/                  # 后端代码
│   └── web/                  # 简易前端
├── snippets/                  # 学习过程中的代码片段
└── notes/                     # 学习笔记（按主题）
```

---

## 给同样在路上的你

如果你也是：
- 30+ 的 Java 工程师
- 想转型 AI 但不想丢掉工程经验
- 焦虑但不知道从哪开始

可以一起：
- ⭐ **Star** 这个仓库，跟着每周更新
- 💬 **Issue** 区交流学习心得
- 📮 **关注掘金**，获取最新博客

> **35 岁的程序员，不是要变成新人；而是要让 10 年的 Java 经验 + AI 新能力组合在一起，变成市场上稀缺的"裁判型架构师"。**

---

## 更新日志

- **2026-05-27** · 仓库初始化，制定 12 个月学习路线图
- ...

---

## License

MIT

---

<sub>这个仓库不会有"完结篇"。学习是一辈子的事，但每个季度都有阶段性交付。</sub>
