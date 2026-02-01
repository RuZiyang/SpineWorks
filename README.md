<div align="center">

# 🕸️ Spineworks

### *Your AI-Powered Software Development Ecosystem*

**From Idea to Production — Orchestrated by Intelligent Agents**

[English](#english) | [中文](#中文)

---

[![Python 3.13+](https://img.shields.io/badge/python-3.13+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

</div>

---

<a name="english"></a>

## 🌟 What is Spineworks?

**Spineworks** is a revolutionary AI-powered software development platform that transforms how you build software. Imagine having a team of 23+ specialized AI agents working together — from brainstorming your idea to deploying production-ready code.

### 🎯 The Vision

Stop writing code alone. Start orchestrating an AI development team.

Spineworks combines:
- 🧠 **Personal Think Tank** — 5 perspective agents that deeply analyze your ideas
- 🏢 **Organizational Agents** — 18 specialized agents that execute your project
- 🤝 **Always-On Secretary** — Your AI assistant that monitors, coordinates, and keeps you informed

---

## ✨ Key Features

### 🚀 Dual-Entry Architecture

**Choose Your Starting Point:**

```bash
# Option 1: Deep Thinking Mode
spineworks think
→ Brainstorm with 5 perspective agents
→ Generate comprehensive requirement cards
→ Seamlessly handoff to execution team

# Option 2: Fast Execution Mode  
spineworks start --direct
→ Jump straight into project execution
→ PM Agent asks clarifying questions
→ Can consult Think Tank anytime
```

### 🧠 Personal Think Tank (5 Perspective Agents)

Your AI brainstorming team that analyzes ideas from multiple angles:

| Agent | Focus | Output |
|-------|-------|--------|
| 🎯 **Goal Focus** | What do you really want? | Core objectives, success criteria |
| 🗺️ **Path Planning** | How to get there? | Roadmaps, milestones, alternatives |
| ⚠️ **Risk Prediction** | What could go wrong? | Risk analysis, mitigation strategies |
| 🔧 **Resource Integration** | What do you need? | Tech stack, team, tools, budget |
| 🔄 **Optimization** | How to improve? | MVP scope, iteration roadmap |

**Features:**
- ⚡ **30-60 second** quick analysis mode
- 💬 Deep dialogue mode for complex projects
- 📊 Generates standardized **Requirement Cards**
- 👁️ **Continuous monitoring** of project execution

---

### 🏢 Organizational Agents (18 Specialized Agents)

Your AI development team that executes projects end-to-end:

#### 📋 Requirements Phase
- **PM Agent** — Requirements analysis, task breakdown, acceptance criteria
- **Coordination Agent** — Scheduling, progress monitoring, conflict resolution
- **Prompt Engineer Agent** — Optimizes all agent prompts for quality

#### 🎨 Design Phase
- **Tech Lead Agent** — Architecture design, tech stack selection
- **Architecture Review Agent** — Independent architecture evaluation
- **UI/UX Design Agent** — Prototypes, interaction design, visual specs

#### 💻 Development Phase
- **Frontend Dev Agent** — React, Vue, Angular implementations
- **Backend Dev Agent** — APIs, databases, business logic
- **Fullstack Dev Agent** — End-to-end feature development

#### 🛡️ Quality Assurance Phase
- **Code Review Agent** — Code quality, standards, bug detection
- **Security Agent** — Vulnerability scanning, security hardening
- **Performance Agent** — Performance analysis, optimization
- **QA Agent** — Test case generation, automated testing

#### 🚀 Deployment Phase
- **Ops Agent** — Deployment scripts, environment configuration
- **Doc Agent** — API docs, user manuals, deployment guides

#### 📈 Continuous Improvement
- **Compliance Agent** — License compliance, patent checks
- **Product Growth Agent** — User analytics, growth strategies
- **Retro Agent** — Project retrospectives, process optimization

---

### 🤝 Always-On Secretary Agent

Your AI project manager that never sleeps:

```
User: "Hey, the login module has a bug"
Secretary: "Got it. I see the issue in authentication flow. 
           Notifying Backend Dev Agent and Security Agent..."

User: "What's the current progress?"
Secretary: "Frontend: 75% complete, Backend: 60% complete.
           Code Review found 3 issues, all resolved.
           ETA: 2 days to MVP."
```

**Capabilities:**
- 🎧 **Always listening** — Interrupt anytime with concerns
- 🧭 **Context-aware** — Understands which module you're referring to
- 📊 **Progress tracking** — Regular status updates
- 🔄 **Coordination** — Routes issues to the right agents
- 💬 **Natural conversation** — Talk like you would to a human PM

---

## 🔄 How It Works

### The Spineworks Workflow

```
┌─────────────────────────────────────────────────────────┐
│                    👤 You (The User)                     │
└─────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│              🤝 Secretary Agent (Always On)              │
│         Your AI PM — Monitors, Coordinates, Reports      │
└─────────────────────────────────────────────────────────┘
                            │
              ┌─────────────┴─────────────┐
              ▼                           ▼
┌──────────────────────────┐  ┌──────────────────────────┐
│  🧠 Personal Think Tank   │  │  🏢 Organizational Team   │
│                          │  │                          │
│  5 Perspective Agents    │◄─┤  18 Specialized Agents   │
│  • Goal Focus            │  │  • PM, Tech Lead         │
│  • Path Planning         │  │  • Frontend, Backend     │
│  • Risk Prediction       │  │  • Code Review, QA       │
│  • Resource Integration  │  │  • Security, Ops         │
│  • Optimization          │  │  • Doc, Compliance       │
│                          │  │                          │
│  📋 Requirement Cards    │──►│  💻 Production Code      │
│  👁️ Continuous Monitoring│  │  🛡️ Quality Assurance    │
└──────────────────────────┘  └──────────────────────────┘
```

### Bidirectional Collaboration

**Not a one-way pipeline — it's a living ecosystem:**

- 🔄 **Org Agents ↔ Think Tank**: PM Agent can ask Think Tank for clarification
- 👁️ **Think Tank → Org Agents**: Continuous monitoring, proactive alerts
- 🤝 **Secretary ↔ Everyone**: Coordinates all agents, keeps you informed
- ⚡ **Parallel Execution**: Multiple agents work simultaneously
- 🛡️ **Real-time Quality Control**: Quality agents monitor as code is written

---

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/spineworks.git
cd spineworks

# Install dependencies
pip install -e .

# Configure your LLM provider
spineworks config setup
```

### Your First Project

#### Option 1: Start with Deep Thinking

```bash
# Launch Think Tank
spineworks think

# The 5 perspective agents will analyze your idea
# Generate a comprehensive requirement card
# Then ask if you want to start execution
```

#### Option 2: Jump Straight to Execution

```bash
# Start project directly
spineworks start --direct

# PM Agent will ask clarifying questions
# Can consult Think Tank anytime during execution
```

### Monitor Your Project

```bash
# Check progress anytime
spineworks status

# View detailed agent activities
spineworks monitor --live

# Export project deliverables
spineworks export --output ./my-project
```

---

## 💡 Use Cases

### 🎯 For Solo Developers
- Brainstorm ideas with AI think tank
- Get architecture recommendations
- Generate production-ready code
- Automated testing and deployment

### 🏢 For Small Teams
- Augment your team with AI specialists
- Accelerate development cycles
- Maintain code quality standards
- Scale without hiring

### 🚀 For Startups
- Rapid MVP development
- Iterate based on AI insights
- Built-in security and compliance
- Focus on product, not infrastructure

---

## 🏗️ Architecture Highlights

### Dual-Layer Design

**Layer 1: Personal Think Tank**
- Purpose: Transform vague ideas into clear requirements
- Agents: 5 perspective agents
- Output: Standardized requirement cards
- Mode: Continuous monitoring

**Layer 2: Organizational Agents**
- Purpose: Execute projects end-to-end
- Agents: 18 specialized agents
- Output: Production-ready deliverables
- Mode: Parallel execution with quality gates

### Key Innovations

1. **Bidirectional Communication**
   - Agents can consult each other
   - Think Tank monitors execution
   - Org agents can ask for clarification

2. **Always-On Secretary**
   - Persistent monitoring
   - Interrupt-driven updates
   - Context-aware coordination

3. **Parallel Execution**
   - Multiple agents work simultaneously
   - 3.3x speedup on average
   - Graceful degradation on failures

4. **Quality-First**
   - Real-time code review
   - Security scanning
   - Performance monitoring
   - Automated testing

---

## 🛠️ Technology Stack

- **Language**: Python 3.13+
- **LLM Support**: OpenAI, Anthropic, Google, OpenAI-compatible APIs
- **Testing**: pytest, Hypothesis (property-based testing)
- **CLI**: Rich, Click
- **Storage**: JSON-based requirement cards, SQLite memory
- **Async**: asyncio for parallel agent execution

---

## 📚 Documentation

- [Installation Guide](docs/installation.md)
- [User Guide](docs/user-guide.md)
- [Architecture Overview](docs/architecture.md)
- [Agent Reference](docs/agents.md)
- [API Documentation](docs/api.md)
- [Contributing](CONTRIBUTING.md)

---

## 🤝 Contributing

We welcome contributions! Whether it's:
- 🐛 Bug reports
- 💡 Feature requests
- 📝 Documentation improvements
- 🔧 Code contributions

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Star History

If you find Spineworks useful, please consider giving it a star! ⭐

---

<div align="center">

**Built with ❤️ by developers, for developers**

[Report Bug](https://github.com/yourusername/spineworks/issues) · [Request Feature](https://github.com/yourusername/spineworks/issues) · [Documentation](https://spineworks.dev)

</div>

---
---

<a name="中文"></a>

<div align="center">

# 🕸️ Spineworks

### *AI 驱动的软件开发生态系统*

**从想法到生产 — 由智能 Agent 编排**

</div>

---

## 🌟 什么是 Spineworks？

**Spineworks** 是一个革命性的 AI 驱动软件开发平台，彻底改变你构建软件的方式。想象一下，拥有一个由 23+ 个专业 AI Agent 组成的团队 — 从头脑风暴到部署生产代码，全程协作。

### 🎯 愿景

不再孤军奋战写代码，开始编排你的 AI 开发团队。

Spineworks 结合了：
- 🧠 **个人智囊团队** — 5 个视角 Agent 深度分析你的想法
- 🏢 **组织级 Agent** — 18 个专业 Agent 执行你的项目
- 🤝 **常驻秘书** — 你的 AI 助手，监控、协调并随时汇报

---

## ✨ 核心特性

### 🚀 双入口架构

**选择你的起点：**

```bash
# 选项 1：深度思考模式
spineworks think
→ 与 5 个视角 Agent 头脑风暴
→ 生成全面的需求卡片
→ 无缝移交给执行团队

# 选项 2：快速执行模式
spineworks start --direct
→ 直接进入项目执行
→ PM Agent 提出澄清问题
→ 随时可咨询智囊团队
```

### 🧠 个人智囊团队（5 个视角 Agent）

你的 AI 头脑风暴团队，从多个角度分析想法：

| Agent | 关注点 | 输出 |
|-------|-------|------|
| 🎯 **目标聚焦** | 你真正想要什么？ | 核心目标、成功标准 |
| 🗺️ **路径规划** | 如何实现？ | 路线图、里程碑、备选方案 |
| ⚠️ **风险预测** | 可能出什么问题？ | 风险分析、缓解策略 |
| 🔧 **资源整合** | 需要什么资源？ | 技术栈、团队、工具、预算 |
| 🔄 **优化迭代** | 如何改进？ | MVP 范围、迭代路线图 |

**功能特性：**
- ⚡ **30-60 秒**快速分析模式
- 💬 复杂项目的深度对话模式
- 📊 生成标准化**需求卡片**
- 👁️ **持续监控**项目执行

---

### 🏢 组织级 Agent（18 个专业 Agent）

你的 AI 开发团队，端到端执行项目：

#### 📋 需求阶段
- **PM Agent** — 需求分析、任务拆解、验收标准
- **Coordination Agent** — 排期调度、进度监控、冲突解决
- **Prompt Engineer Agent** — 优化所有 Agent 的提示词

#### 🎨 设计阶段
- **Tech Lead Agent** — 架构设计、技术选型
- **Architecture Review Agent** — 独立架构评审
- **UI/UX Design Agent** — 原型设计、交互设计、视觉规范

#### 💻 开发阶段
- **Frontend Dev Agent** — React、Vue、Angular 实现
- **Backend Dev Agent** — API、数据库、业务逻辑
- **Fullstack Dev Agent** — 端到端功能开发

#### 🛡️ 质量保障阶段
- **Code Review Agent** — 代码质量、规范、bug 检测
- **Security Agent** — 漏洞扫描、安全加固
- **Performance Agent** — 性能分析、优化
- **QA Agent** — 测试用例生成、自动化测试

#### 🚀 部署阶段
- **Ops Agent** — 部署脚本、环境配置
- **Doc Agent** — API 文档、用户手册、部署指南

#### 📈 持续改进
- **Compliance Agent** — 许可证合规、专利检查
- **Product Growth Agent** — 用户分析、增长策略
- **Retro Agent** — 项目复盘、流程优化

---

### 🤝 常驻秘书 Agent

你的 AI 项目经理，永不休息：

```
用户："嘿，登录模块有个 bug"
秘书："收到。我看到认证流程的问题了。
      正在通知 Backend Dev Agent 和 Security Agent..."

用户："当前进度怎么样？"
秘书："前端：75% 完成，后端：60% 完成。
      Code Review 发现 3 个问题，已全部解决。
      预计：2 天后完成 MVP。"
```

**能力：**
- 🎧 **始终在线** — 随时打断并提出问题
- 🧭 **上下文感知** — 理解你指的是哪个模块
- 📊 **进度跟踪** — 定期状态更新
- 🔄 **协调调度** — 将问题路由到正确的 Agent
- 💬 **自然对话** — 像跟人类 PM 一样交流

---

## 🔄 工作原理

### Spineworks 工作流

```
┌─────────────────────────────────────────────────────────┐
│                    👤 你（用户）                          │
└─────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│              🤝 秘书 Agent（常驻在线）                    │
│         你的 AI PM — 监控、协调、汇报                     │
└─────────────────────────────────────────────────────────┘
                            │
              ┌─────────────┴─────────────┐
              ▼                           ▼
┌──────────────────────────┐  ┌──────────────────────────┐
│  🧠 个人智囊团队          │  │  🏢 组织级团队            │
│                          │  │                          │
│  5 个视角 Agent          │◄─┤  18 个专业 Agent         │
│  • 目标聚焦              │  │  • PM、Tech Lead         │
│  • 路径规划              │  │  • 前端、后端            │
│  • 风险预测              │  │  • Code Review、QA       │
│  • 资源整合              │  │  • Security、Ops         │
│  • 优化迭代              │  │  • Doc、Compliance       │
│                          │  │                          │
│  📋 需求卡片             │──►│  💻 生产代码             │
│  👁️ 持续监控             │  │  🛡️ 质量保障             │
└──────────────────────────┘  └──────────────────────────┘
```

### 双向协作

**不是单向流水线 — 而是活的生态系统：**

- 🔄 **组织 Agent ↔ 智囊团队**：PM Agent 可以向智囊团队请求澄清
- 👁️ **智囊团队 → 组织 Agent**：持续监控，主动告警
- 🤝 **秘书 ↔ 所有人**：协调所有 Agent，随时汇报
- ⚡ **并行执行**：多个 Agent 同时工作
- 🛡️ **实时质量控制**：质量 Agent 在代码编写时监控

---

## 🚀 快速开始

### 安装

```bash
# 克隆仓库
git clone https://github.com/yourusername/spineworks.git
cd spineworks

# 安装依赖
pip install -e .

# 配置 LLM 提供商
spineworks config setup
```

### 你的第一个项目

#### 选项 1：从深度思考开始

```bash
# 启动智囊团队
spineworks think

# 5 个视角 Agent 将分析你的想法
# 生成全面的需求卡片
# 然后询问是否开始执行
```

#### 选项 2：直接开始执行

```bash
# 直接启动项目
spineworks start --direct

# PM Agent 会提出澄清问题
# 执行过程中随时可咨询智囊团队
```

### 监控你的项目

```bash
# 随时检查进度
spineworks status

# 查看详细的 Agent 活动
spineworks monitor --live

# 导出项目交付物
spineworks export --output ./my-project
```

---

## 💡 使用场景

### 🎯 独立开发者
- 与 AI 智囊团队头脑风暴
- 获取架构建议
- 生成生产就绪代码
- 自动化测试和部署

### 🏢 小型团队
- 用 AI 专家增强团队
- 加速开发周期
- 维护代码质量标准
- 无需招聘即可扩展

### 🚀 创业公司
- 快速 MVP 开发
- 基于 AI 洞察迭代
- 内置安全和合规
- 专注产品，而非基础设施

---

## 🏗️ 架构亮点

### 双层设计

**第一层：个人智囊团队**
- 目的：将模糊想法转化为清晰需求
- Agent：5 个视角 Agent
- 输出：标准化需求卡片
- 模式：持续监控

**第二层：组织级 Agent**
- 目的：端到端执行项目
- Agent：18 个专业 Agent
- 输出：生产就绪交付物
- 模式：并行执行 + 质量门禁

### 关键创新

1. **双向通信**
   - Agent 之间可以互相咨询
   - 智囊团队监控执行
   - 组织 Agent 可以请求澄清

2. **常驻秘书**
   - 持久监控
   - 中断驱动更新
   - 上下文感知协调

3. **并行执行**
   - 多个 Agent 同时工作
   - 平均 3.3 倍加速
   - 失败时优雅降级

4. **质量优先**
   - 实时代码审查
   - 安全扫描
   - 性能监控
   - 自动化测试

---

## 🛠️ 技术栈

- **语言**：Python 3.13+
- **LLM 支持**：OpenAI、Anthropic、Google、OpenAI 兼容 API
- **测试**：pytest、Hypothesis（基于属性的测试）
- **CLI**：Rich、Click
- **存储**：基于 JSON 的需求卡片、SQLite 内存
- **异步**：asyncio 用于并行 Agent 执行

---

## 📚 文档

- [安装指南](docs/installation.md)
- [用户指南](docs/user-guide.md)
- [架构概览](docs/architecture.md)
- [Agent 参考](docs/agents.md)
- [API 文档](docs/api.md)
- [贡献指南](CONTRIBUTING.md)

---

## 🤝 贡献

我们欢迎贡献！无论是：
- 🐛 Bug 报告
- 💡 功能请求
- 📝 文档改进
- 🔧 代码贡献

查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解指南。

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

---

## 🌟 Star 历史

如果你觉得 Spineworks 有用，请考虑给它一个 star！⭐

---

<div align="center">

**由开发者构建，为开发者服务 ❤️**

[报告 Bug](https://github.com/yourusername/spineworks/issues) · [请求功能](https://github.com/yourusername/spineworks/issues) · [文档](https://spineworks.dev)

</div>
