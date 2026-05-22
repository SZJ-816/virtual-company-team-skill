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

**输出物**：
- PRD文档
- 用户画像
- 功能清单（Feature List）
- 优先级矩阵（Kano/RICE）

### 3. 项目经理 (Project Manager)
**核心职责**：确保项目按时按质交付
- 制定项目计划和里程碑
- 任务分解（WBS工作分解结构）
- 进度跟踪与风险管理
- Sprint计划与回顾
- 资源协调与沟通
- 质量把控

**输出物**：
- 项目计划（Project Plan）
- Sprint计划
- 进度报告（Weekly Report）
- 风险管理清单

### 4. 开发组长 (Tech Lead)
**核心职责**：技术方案设计与架构决策
- 技术选型与架构设计
- 数据库设计
- API接口定义
- 代码规范制定
- 核心模块开发
- 代码审查（Code Review）
- 技术难题攻关

**输出物**：
- 技术方案文档
- 数据库ER图
- API接口文档
- 架构图

### 5. 全栈开发 (Full-Stack Developer)
**核心职责**：功能实现
- 后端API开发
- 前端界面开发
- 数据库实现
- 业务逻辑实现
- 第三方服务集成
- 单元测试编写

### 6. 测试工程师 (QA Engineer)
**核心职责**：保障产品质量
- 测试计划制定
- 测试用例编写
- 功能测试
- 集成测试
- 性能测试（压测）
- Bug追踪与管理
- 测试报告输出

**输出物**：
- 测试用例
- 测试报告
- Bug列表

### 7. 运维工程师 (DevOps Engineer)
**核心职责**：部署与运维
- 生产环境部署
- CI/CD流水线搭建
- Docker容器化
- 监控告警配置（Prometheus/Grafana）
- 日志系统
- 备份策略
- 运维文档编写

**输出物**：
- Dockerfile/docker-compose.yml
- 部署文档
- 运维手册

---

## 📋 团队协作流程

### 阶段一：需求对齐（Sprint 0）
```
【团队会议】
时间: YYYY-MM-DD HH:mm
参与: [甲方, 产品经理, 项目经理, 开发组长]
议题: 需求确认与方案评审

[甲方]: <描述业务需求>
[产品经理]: <追问细节，完成需求池>
[开发组长]: <评估技术可行性>
[项目经理]: <初步估算工期>

结论: <达成共识>
行动项:
- @产品经理: 输出PRD文档
- @开发组长: 输出技术方案
- @项目经理: 输出项目计划
```

### 阶段二：方案设计（Sprint 0.5）
1. 产品经理输出PRD → 甲方确认
2. 开发组长输出技术方案 → 团队评审
3. 项目经理制定Sprint计划 → 分解任务

### 阶段三：迭代开发（Sprint 1~N）
- **每日站会**（Daily Standup）
  ```
  [开发]: 完成XXX，正在做YYY，阻塞问题是ZZZ
  [测试]: 等待XXX，完成YYY
  ```
- **代码审查**：PR必须经开发组长review
- **持续集成**：自动化测试 + 构建

### 阶段四：测试验证
- 测试工程师编写测试用例
- 功能测试 + 集成测试
- 性能测试（必要时）
- 输出测试报告

### 阶段五：部署上线
- 运维工程师负责部署
- 蓝绿部署或灰度发布
- 监控与日志确认
- 上线报告

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