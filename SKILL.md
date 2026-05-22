---
name: virtual-company-team
description: 虚拟公司团队协作技能，模拟真实公司的产品开发流程。包括：甲方（客户/需求方）、产品经理（需求分析+PRD）、项目经理（进度管理）、编程人员（开发实现）、测试人员（质量保障）、运维人员（部署+监控）。使用场景：用户要求创建团队、开发产品、项目管理、竞品分析、市场调研、PRD撰写、敏捷开发、代码审查、测试驱动、CI/CD部署等。
---

# 🏢 虚拟公司团队技能

> 一个由AI驱动的虚拟公司团队，模拟真实公司的产品开发流程。

## 👥 团队角色与职责

### 1. 甲方/客户 (Client)
- 提出业务需求和目标
- 确认功能范围和优先级
- 验收最终成果
- 提供预算和时间要求

### 2. 产品经理 (Product Manager)
**核心职责**：把需求变成可执行的方案
- 用户调研与需求分析
- 竞品分析（功能/体验/定价）
- 编写PRD文档（产品需求文档）
- 功能优先级排序（MVP定义）
- 用户画像与使用场景
- 产品路线图规划
- 数据分析与监控
- 用户反馈收集与管理

**AI 辅助能力**：
- AI 辅助竞品分析（Claude/GPT-4o）
- AI 生成用户画像模板
- AI 辅助 PRD 文档起草
- AI 生成问卷和访谈提纲

**协作接口**：
- ↔ 甲方：需求确认与反馈
- ↔ UI/UX：信息架构与设计评审
- ↔ 开发组长：技术可行性评估
- ↔ 项目经理：排期计划
- ↔ 数据工程师：埋点与数据分析需求

**输出物**：
- PRD文档
- 用户画像
- 功能清单（Feature List）
- 优先级矩阵（Kano/RICE）
- 产品路线图
- 用户研究报告

### 3. 项目经理 (Project Manager)
**核心职责**：确保项目按时按质交付
- 制定项目计划和里程碑
- 任务分解（WBS工作分解结构）
- 进度跟踪与风险管理
- Sprint计划与回顾
- 资源协调与沟通
- 质量把控
- 跨团队协调
- 风险预警与应对

**AI 辅助能力**：
- AI 辅助任务拆分与估时
- AI 生成进度报告
- AI 辅助风险识别
- AI 辅助会议纪要整理

**协作接口**：
- ↔ 全团队：进度协调
- ↔ 甲方：汇报与确认
- ↔ 产品经理：需求变更评估
- ↔ 开发组长：技术风险识别
- ↔ 测试工程师：质量把控

**输出物**：
- 项目计划（Project Plan）
- Sprint计划
- 进度报告（Weekly Report）
- 风险管理清单
- 燃尽图/看板
- 会议纪要

### 4. 开发组长 (Tech Lead)
**核心职责**：技术方案设计与架构决策
- 技术选型与架构设计
- 数据库设计
- API接口定义
- 代码规范制定
- 核心模块开发
- 代码审查（Code Review）
- 技术难题攻关
- 技术债务管理
- 性能优化

**AI 辅助能力**：
- AI 辅助架构设计与评审
- AI 代码审查（初步）
- AI 生成技术文档
- AI 辅助性能分析

**协作接口**：
- ↔ 技术架构师：企业架构对齐
- ↔ 全栈开发：代码规范指导
- ↔ AI/ML 工程师：AI 集成方案
- ↔ 安全工程师：安全架构
- ↔ 运维工程师：部署架构

**输出物**：
- 技术方案文档
- 数据库ER图
- API接口文档
- 架构图
- 代码规范文档
- 架构决策记录（ADR）

### 5. 全栈开发 (Full-Stack Developer)
**核心职责**：功能实现
- 后端API开发
- 前端界面开发
- 数据库实现
- 业务逻辑实现
- 第三方服务集成
- 单元测试编写
- API 文档维护
- Git 代码管理

**AI 辅助能力**：
- AI 代码补全（GitHub Copilot X）
- AI 代码生成（Cursor/Amazon Q）
- AI 自动生成单元测试
- AI 代码重构建议

**协作接口**：
- ↔ 开发组长：代码审查与规范
- ↔ UI/UX：设计实现
- ↔ 测试工程师：Bug 修复
- ↔ AI/ML 工程师：AI 功能集成

**输出物**：
- 功能代码
- 单元测试
- API 实现
- 部署脚本

### 6. 测试工程师 (QA Engineer)
**核心职责**：保障产品质量
- 测试计划制定
- 测试用例编写
- 功能测试
- 集成测试
- 性能测试（压测）
- Bug追踪与管理
- 测试报告输出
- 自动化测试开发
- 回归测试

**AI 辅助能力**：
- AI 自动生成测试用例
- AI 辅助 Bug 分类与定位
- AI 性能测试分析
- AI 测试报告生成

**协作接口**：
- ↔ 全栈开发：Bug 反馈
- ↔ 开发组长：测试覆盖率
- ↔ 项目经理：测试进度
- ↔ 运维工程师：测试环境

**输出物**：
- 测试用例
- 测试报告
- Bug列表
- 测试覆盖率报告
- 自动化测试脚本

### 7. 运维工程师 (DevOps Engineer)
**核心职责**：部署与运维
- 生产环境部署
- CI/CD流水线搭建
- Docker容器化
- 监控告警配置（Prometheus/Grafana）
- 日志系统
- 备份策略
- 运维文档编写
- 应急响应
- 容量规划

**AI 辅助能力**：
- AI 异常检测与告警
- AI 辅助故障诊断
- AI 辅助容量预测
- AI 自动化运维脚本生成

**协作接口**：
- ↔ 开发组长：部署架构
- ↔ 全栈开发：CI/CD 集成
- ↔ 安全工程师：安全配置
- ↔ 项目经理：部署计划

**输出物**：
- Dockerfile/docker-compose.yml
- 部署文档
- 运维手册
- 监控仪表盘
- 应急响应手册
- 容量规划报告

### 8. UI/UX 设计师 (Designer)
**核心职责**：用户体验设计与研究
- 用户研究与调研（问卷、访谈、可用性测试）
- 信息架构设计（IA）
- 交互设计（User Flow, Wireframe）
- 视觉设计（UI Design）
- 原型制作与验证
- 设计系统建立与维护
- 用户测试（Usability Testing）
- 响应式设计与无障碍设计

**AI 辅助能力**：
- AI 辅助用户研究分析
- AI 生成设计建议
- AI 用户体验评估
- AI 辅助无障碍合规检查

**协作接口**：
- ↔ 产品经理：需求与设计对齐
- ↔ 全栈开发：设计实现
- ↔ 测试工程师：可用性测试

**输出物**：
- 用户研究报告
- 信息架构图（IA）
- 线框图（Wireframe）
- 高保真设计稿
- 交互原型
- 设计系统（Design System）
- 样式指南（Style Guide）

**工具推荐**：
- Figma / Sketch / Adobe XD
- Miro / FigJam
- Principle / Framer
- Hotjar / FullStory

### 9. AI/ML 工程师 (AI Engineer)
**核心职责**：AI 能力研发与集成
- AI 模型选型与评估
- 模型训练与微调（Fine-tuning）
- RAG 系统搭建
- AI Agent 开发
- Prompt Engineering
- 向量数据库集成
- AI 应用性能优化
- 模型部署与服务化
- AI 伦理与合规

**AI 辅助能力**：
- AI 自动调参与优化
- AI 模型评估与比较
- AI 生成测试数据
- AI 辅助性能监控

**协作接口**：
- ↔ 开发组长：AI 集成方案
- ↔ 全栈开发：AI API 调用
- ↔ 数据工程师：训练数据管道
- ↔ 安全工程师：AI 安全评估

**输出物**：
- AI 技术方案
- 模型训练报告
- RAG 系统架构
- Prompt 库与模板
- AI API 接口文档
- 模型性能评估报告

**技术栈**：
- LangChain / LlamaIndex
- OpenAI / Anthropic Claude API
- Ollama / vLLM
- Hugging Face Transformers
- Vector DB (Qdrant/Pinecone/pgvector)

### 10. 数据工程师 (Data Engineer)
**核心职责**：数据平台与管道建设
- 数据仓库设计与实现
- ETL/ELT 管道开发
- 数据湖架构
- 实时数据处理
- 数据质量监控
- 数据治理
- BI 报表开发
- A/B 测试平台

**输出物**：
- 数据架构图
- 数据字典
- ETL/ELT 管道代码
- 数据质量报告
- BI 仪表盘

**技术栈**：
- Apache Airflow / Dagster
- dbt / Snowflake
- Apache Kafka / Flink
- Databricks / Spark
- Looker / Metabase

### 11. 安全工程师 (Security Engineer)
**核心职责**：安全防护与合规
- 安全架构设计
- 渗透测试
- 代码安全审计
- 安全监控与响应
- 合规审计（GDPR/ISO27001）
- 安全培训
- 漏洞管理
- 威胁建模

**输出物**：
- 安全评估报告
- 威胁建模文档
- 安全策略文档
- 渗透测试报告
- 合规检查清单
- 安全事件响应计划

**工具推荐**：
- SonarQube / Snyk
- OWASP ZAP / Burp Suite
- HashiCorp Vault
- CrowdStrike / Falco

### 12. 技术架构师 (Solutions Architect)
**核心职责**：企业级架构规划
- 企业架构设计
- 微服务架构规划
- 系统可靠性设计（SRE）
- 性能优化策略
- 成本优化分析
- 技术标准制定
- 架构评审主持
- 技术债务管理

**输出物**：
- 企业架构图
- 技术路线图
- 架构决策记录（ADR）
- 技术标准文档
- POC 原型
- 性能基准报告

### 13. 技术写作者 (Tech Writer / DevRel)
**核心职责**：技术文档与社区运营
- API 文档编写
- 用户手册制作
- 开发文档维护
- 教程与最佳实践
- 开发者关系运营
- 技术博客撰写
- 社区活动组织
- 开源项目管理

**输出物**：
- API 文档
- 开发者门户
- 用户指南
- 教程与案例
- 技术博客
- 开源 README
- changelog

---

## 📋 团队协作流程 (AI 增强版)

### 阶段零：项目启动（Kickoff）
```
【项目启动会议】
时间: YYYY-MM-DD HH:mm
参与: [甲方, 产品经理, 项目经理, 开发组长, UI/UX, AI/ML工程师]
议题: 项目启动与目标对齐

[甲方]: <描述业务需求与目标>
[产品经理]: <产品愿景与成功指标>
[开发组长]: <初步技术方案>
[UI/UX]: <用户体验初步设想>
[AI/ML工程师]: <AI能力建议>
[项目经理]: <项目里程碑>

结论: 项目正式启动
行动项:
- @产品经理: 输出PRD文档（AI辅助竞品分析）
- @UI/UX: 输出设计调研报告
- @开发组长: 输出技术方案
- @AI/ML工程师: 输出AI方案建议
- @项目经理: 输出项目计划与Sprint安排
```

### 阶段一：需求对齐（Sprint 0）
```
【需求评审会议】
时间: YYYY-MM-DD HH:mm
参与: [甲方, 产品经理, UI/UX, 开发组长]
议题: 需求确认与方案评审

[甲方]: <确认业务需求>
[产品经理]: <展示PRD文档与优先级>
[UI/UX]: <展示用户研究与设计方案>
[开发组长]: <评估技术可行性>

结论: 需求确认，设计冻结
行动项:
- @产品经理: 更新PRD（如有变更）
- @UI/UX: 输出最终设计稿
- @开发组长: 输出详细技术方案
```

### 阶段二：方案设计（Sprint 0.5）
1. 产品经理输出PRD → 甲方确认
2. UI/UX输出设计稿 → 评审通过
3. 开发组长输出技术方案 → 团队评审
4. AI/ML工程师输出AI方案（如需要）
5. 项目经理制定Sprint计划 → 分解任务

### 阶段三：迭代开发（Sprint 1~N）
**会议安排**：
- **每日站会**（Daily Standup, 15min）
  ```
  【站会】{date}
  
  [全栈开发]: 
  - 昨日完成: {done}
  - 今日计划: {today}
  - AI辅助: {使用了哪些AI工具}
  - 阻塞问题: {blockers}
  
  [UI/UX]: 
  - 设计进度: {progress}
  - 设计评审: {reviews}
  
  [测试]:
  - 测试进度: {progress}
  - 发现Bug: {bugs}
  
  [项目经理]:
  - 进度评估: {assessment}
  ```

- **Sprint评审**（Sprint Review, 1-2h）
  - 展示完成的功能
  - 甲方验收
  - 收集反馈
  - 下一Sprint规划

- **Sprint回顾**（Retrospective, 1h）
  - 做得好
  - 需要改进
  - AI工具使用效果
  - 下次Sprint改进计划

- **设计评审**（Design Review）
  ```
  【设计评审】
  参与: [UI/UX, 产品经理, 全栈开发]
  议题: 设计稿评审
  
  [UI/UX]: <展示设计方案>
  [全栈开发]: <评估实现可行性>
  [产品经理]: <评估用户体验>
  
  结论: 设计通过 / 需要修改
  ```

- **架构评审**（Architecture Review）
  ```
  【架构评审】
  参与: [开发组长, 技术架构师, 全栈开发, AI/ML工程师]
  议题: 技术方案评审
  
  [开发组长]: <展示架构设计>
  [AI/ML工程师]: <AI集成方案>
  [全栈开发]: <技术挑战>
  
  结论: 架构通过 / 需要优化
  ```

- **代码审查**：AI初审 → 开发组长复核
- **持续集成**：自动化测试 + 构建

### 阶段四：测试验证
- 测试工程师编写测试用例（AI辅助生成）
- 功能测试 + 集成测试
- 性能测试（AI辅助分析）
- 安全测试（安全工程师参与）
- AI功能专项测试（如需要）
- 可用性测试（UI/UX参与）
- 输出测试报告

### 阶段五：部署上线
- 运维工程师负责部署（GitOps自动化）
- 蓝绿部署或灰度发布
- 监控与日志确认（AI异常检测）
- 数据质量验证（如需要）
- 甲方验收
- 上线报告

### 阶段六：持续改进
- 用户反馈收集
- 数据分析
- AI模型优化（如需要）
- 产品迭代规划

---

## 📝 PRD文档模板

```markdown
# 产品需求文档 (PRD)

## 1. 背景与目标
- **业务背景**: 
- **核心目标**: 
- **成功指标**: (KPIs)

## 2. 用户分析
- **目标用户**: 
- **用户画像**: 
- **使用场景**: 

## 3. 功能需求

### 3.1 核心功能 (MVP)
| 功能 | 描述 | 优先级 | 负责人 |
|------|------|--------|--------|
| ... | ... | P0 | ... |

### 3.2 扩展功能
| 功能 | 描述 | 优先级 | 负责人 |
|------|------|--------|--------|
| ... | ... | P1 | ... |

### 3.3 功能详细描述
...

## 4. 非功能需求
- **性能**: 响应时间<XXms
- **安全**: 认证/授权/加密
- **兼容性**: 浏览器/系统

## 5. 排期计划
| 阶段 | 任务 | 开始 | 结束 | 负责人 |
|------|------|------|------|--------|
| Sprint 1 | ... | ... | ... | ... |

## 6. 风险评估
| 风险 | 影响 | 概率 | 应对措施 |
|------|------|------|----------|
| ... | ... | ... | ... |
```

---

## 📊 Sprint计划模板

```markdown
# Sprint N (YYYY-MM-DD ~ YYYY-MM-DD)

## Sprint目标
...

## 任务看板
| 待开发 | 开发中 | 已完成 |
|--------|--------|--------|
| [ ] 任务1 | [ ] 任务3 | [x] 任务4 |
| [ ] 任务2 | ... | |

## 阻塞问题
| 问题 | 负责人 | 状态 | 解决时间 |
|------|--------|------|----------|
| ... | ... | 进行中 | ... |

## Sprint回顾
- 做得好:
- 需要改进:
- 下次Sprint改进:
```

---

## 🛠 技术栈参考 (2026)

### 后端
| 语言/框架 | 适用场景 |
|-----------|----------|
| Java (Spring Boot 4.x) | 企业级应用 |
| Python (FastAPI 1.0+/Django 6.x) | 快速开发/API |
| Node.js (NestJS 12.x) | 企业级Node.js应用 |
| Go (Gin/Go-Zero) | 高性能微服务 |
| Rust (Axum) | 极致性能/系统级应用 |
| TypeScript (Hono) | 边缘计算/全栈API |

### 前端
| 框架 | 适用场景 |
|------|----------|
| React 20.x + Next.js 16.x | Web应用 |
| Vue 4.x + Nuxt 5.x | Web应用 |
| Svelte 5.x + SvelteKit | 高性能Web应用 |
| Taro 4.x | 小程序/多端统一 |
| Flutter 5.x | 原生移动应用 |
| Solid.js | 高性能响应式应用 |

### AI/LLM 集成
| 技术 | 用途 |
|------|------|
| LangChain 2.x | LLM应用开发 |
| LlamaIndex | RAG系统 |
| OpenAI API/Anthropic API | 大模型调用 |
| Ollama | 本地模型部署 |
| Vercel AI SDK | AI应用快速开发 |

### 数据库
| 类型 | 适用场景 |
|------|----------|
| PostgreSQL 17.x + pgvector | 关系型/向量数据库 |
| MySQL 9.x | 关系型/事务 |
| MongoDB 8.x | 文档/灵活Schema |
| Redis 8.x | 缓存/队列/会话 |
| ClickHouse 25.x | 实时分析 |
| Qdrant/Pinecone | 向量搜索 |
| DuckDB | 嵌入式分析数据库 |

### 基础设施 & DevOps
| 技术 | 用途 |
|------|------|
| Docker + BuildKit | 容器化构建 |
| Kubernetes 1.30+ | 容器编排 |
| GitHub Actions / GitLab CI | CI/CD |
| Prometheus 3.x + Grafana 12.x | 可观测性 |
| Loki + Tempo | 日志/追踪 |
| Terraform 2.x / Pulumi | 基础设施即代码 |
| Nix | 可复现构建 |

### 边缘与 Serverless
| 技术 | 用途 |
|------|------|
| Cloudflare Workers / Vercel Edge Functions | 边缘计算 |
| AWS Lambda / Serverless Framework | Serverless |
| Deno Deploy | 轻量级部署 |

---

## 📈 代码质量标准 (2026)

### 提交规范 (Conventional Commits)
```
<type>(<scope>): <描述>
[optional body]
[optional footer]
```
**Type**:
- `feat`: 新功能
- `fix`: Bug修复
- `docs`: 文档
- `style`: 代码格式
- `refactor`: 重构
- `test`: 测试
- `chore`: 构建/工具
- `ai`: AI 辅助开发相关

### 分支策略 (GitHub Flow)
```
main          ← 生产环境 (可部署)
  ↑ squash merge
feature/xxx   ← 功能开发分支
```

### 代码质量工具
| 工具 | 用途 |
|------|------|
| Biome / ESLint 9.x | JavaScript/TypeScript 代码检查 |
| Prettier | 代码格式化 |
| Ruff | Python 代码检查 |
| SonarQube | 代码质量分析 |
| Snyk / Dependabot | 安全漏洞扫描 |

### AI 辅助开发
| 工具 | 用途 |
|------|------|
| GitHub Copilot X | 代码补全与聊天 |
| Cursor / Windsurf | AI 原生编辑器 |
| Claude / GPT-4o | 代码审查与架构设计 |
| Amazon Q / CodeWhisperer | 企业级 AI 编程助手 |

### PR规范
每个PR必须包含：
- 需求关联（Issue #XXX）
- 改动说明
- 测试结果
- 截图（UI改动）
- AI 辅助开发记录（如使用）

---

## 📁 推荐项目结构 (2026)

### 单仓库 (Monorepo) 结构
```
project/
├── apps/                    # 应用程序
│   ├── web/                 # Web 应用 (Next.js/Nuxt)
│   ├── mobile/              # 移动应用 (Flutter/Taro)
│   └── api/                 # 后端 API
├── packages/                # 共享包
│   ├── ui/                  # 共享 UI 组件库
│   ├── shared/              # 共享工具/类型
│   └── database/            # 数据库层
├── infra/                   # 基础设施
│   ├── terraform/           # IaC 配置
│   └── k8s/                 # Kubernetes 配置
├── docs/                    # 文档
├── tools/                   # 开发工具
├── .github/                 # GitHub Actions
├── package.json             # Monorepo 配置 (pnpm/turborepo)
├── README.md
└── .gitignore
```

### 全栈应用结构 (Next.js 示例)
```
web-app/
├── src/
│   ├── app/                 # App Router (Next.js 16)
│   │   ├── api/             # API Routes
│   │   ├── (auth)/          # 路由组
│   │   └── layout.tsx
│   ├── components/          # React 组件
│   ├── lib/                 # 工具函数
│   ├── hooks/               # React Hooks
│   ├── styles/              # 样式
│   └── types/               # TypeScript 类型
├── prisma/                  # ORM 配置
├── public/                  # 静态资源
├── next.config.js
├── tailwind.config.ts
└── tsconfig.json
```

### 后端 API 结构 (NestJS 示例)
```
api/
├── src/
│   ├── modules/             # 功能模块
│   │   ├── user/
│   │   └── product/
│   ├── common/              # 共享代码
│   │   ├── guards/
│   │   ├── interceptors/
│   │   └── decorators/
│   ├── config/              # 配置
│   └── main.ts
├── test/
├── prisma/
├── docker-compose.yml
└── nest-cli.json
```

---

## 🎯 使用指南

当用户要求「做项目」「开发产品」「创建团队」时：

1. **读取此Skill** → 了解团队角色和流程
2. **启动团队会议** → 角色扮演讨论
3. **输出规划文档** → PRD + 技术方案 + 计划
4. **迭代开发** → 按Sprint执行，充分利用 AI 辅助工具
5. **持续交付** → 测试 → 部署 → 上线

## 🌟 2026 新增最佳实践

### AI 驱动开发
- **架构设计**：使用 Claude/GPT-4o 进行架构评审
- **代码生成**：利用 Copilot/Amazon Q 加速开发
- **测试生成**：AI 自动生成单元测试和集成测试
- **代码审查**：AI 先进行初审，再人工复核

### 快速原型
- **RAG 系统**：快速构建知识问答系统
- **AI Agent**：利用 LangChain 构建智能代理
- **Vector DB**：使用 pgvector/Qdrant 实现语义搜索

### DevOps 现代化
- **可观测性优先**：Metrics, Logs, Traces 三位一体
- **GitOps**：ArgoCD 自动化部署
- **安全左移**：Snyk/Dependabot 持续安全扫描

---

*最后更新: 2026-05-22*