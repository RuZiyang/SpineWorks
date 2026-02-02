# 🐉 SpineWorks - 智能多代理软件开发系统
# 🐉 SpineWorks - Intelligent Multi-Agent Software Development System

<div align="center">

**项目吉祥物：中国龙 🐉 | Project Mascot: Chinese Dragon 🐉**

*象征智慧、力量与创新 | Symbolizing Wisdom, Power, and Innovation*

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**将创意转化为生产就绪的软件 | Transform Ideas into Production-Ready Software**

</div>

---

## 📖 Table of Contents | 目录

### English Documentation
- [Vision & Philosophy](#-vision--philosophy)
- [Personal Think Tank](#-personal-think-tank)
- [Organizational Agent Cluster](#-organizational-agent-cluster)
- [Secretary Agent](#-secretary-agent)
- [Dynamic Agent Generation System](#-dynamic-agent-generation-system)
- [Complete Workflow Examples](#-complete-workflow-examples)
- [File Upload & Analysis](#-file-upload--analysis)
- [Quick Start](#-quick-start)

### 中文文档
- [愿景与理念](#-愿景与理念)
- [个人智囊团](#-个人智囊团)
- [组织代理集群](#-组织代理集群)
- [秘书代理](#-秘书代理)
- [动态代理生成系统](#-动态代理生成系统)
- [完整工作流示例](#-完整工作流示例)
- [文件上传与分析](#-文件上传与分析)
- [快速开始](#-快速开始)

---

# ENGLISH DOCUMENTATION

## 🌟 Vision & Philosophy

SpineWorks is not just another AI coding assistant. It's a **complete intelligent development ecosystem** that mirrors how human teams work: with specialized experts, deep analysis, continuous monitoring, and adaptive collaboration.

### The Dragon Philosophy 🐉

Like the Chinese Dragon - a symbol of wisdom, power, and adaptability - SpineWorks embodies:

- **Wisdom**: Deep analytical thinking through the Think Tank system
- **Power**: 50+ specialized agents working in harmony
- **Adaptability**: Dynamic agent generation for any scenario
- **Vision**: Continuous monitoring and goal alignment
- **Collaboration**: Seamless communication between all agents

### Core Innovation


**Three-Layer Architecture**:

1. **Core Agents (Preset)**: Meta Coordinator, Agent Factory, File Analyzer - always available
2. **Scene Coordinators (Dynamic)**: PM Agent, Research Coordinator, Chief Editor - generated based on task type
3. **Specialized Workers (Dynamic)**: Task-specific agents generated on-demand with user confirmation

**What Makes SpineWorks Different**:

- **Beyond Fixed Agents**: Not limited to 27+ preset agents - generates specialized agents for any scenario
- **User Confirmation Flow**: System proposes agent team → User reviews → User customizes → System executes
- **File Upload Capability**: Upload documents, books, research papers for AI analysis
- **Agent Clusters**: Collaborative teams for research, writing, and complex analysis
- **Continuous Monitoring**: Think Tank agents monitor execution and alert on deviations

---

## 🧠 Personal Think Tank

The Think Tank is your **personal advisory board** - five specialized perspective agents that analyze your project from every angle before execution begins.

### The Five Perspectives

#### 1. 🎯 Goal Focus Agent

**Role**: The Clarity Expert

**What It Does**:
- Clarifies core objectives and success criteria
- Identifies stakeholder needs and expectations
- Defines measurable success metrics
- Monitors for goal drift during execution

**Example Analysis**:
```
Project: "Build a task management app"

Goal Focus Analysis:
✓ Core Goal: Enable teams to collaborate on tasks efficiently
✓ Success Criteria:
  - Users can create/assign/complete tasks in < 3 clicks
  - Real-time updates across all devices
  - 99.9% uptime
✓ Stakeholders: End users, team managers, mobile developers
✓ Key Metrics: User engagement, task completion rate, response time
```

**Continuous Monitoring**:
- Subscribes to `task_started`, `feature_added` events
- Alerts if new features don't align with core goals
- Suggests refocusing when scope creeps


#### 2. 🗺️ Path Planning Agent

**Role**: The Strategist

**What It Does**:
- Designs execution roadmap with clear milestones
- Maps dependencies between tasks
- Estimates timelines and resource needs
- Tracks milestone progress during execution

**Example Analysis**:
```
Project: "Build a task management app"

Path Planning Analysis:
✓ Milestone 1: Authentication System (3 days)
  - User registration/login
  - JWT token management
  - Password reset flow
  Dependencies: None

✓ Milestone 2: Task CRUD API (4 days)
  - Task model and database
  - REST API endpoints
  - Authorization logic
  Dependencies: M1 (auth required)

✓ Milestone 3: Real-time Updates (3 days)
  - WebSocket integration
  - Event broadcasting
  - Client synchronization
  Dependencies: M2 (tasks must exist)

✓ Milestone 4: Mobile App (5 days)
  - React Native setup
  - UI components
  - API integration
  Dependencies: M2, M3
```

**Continuous Monitoring**:
- Tracks milestone completion
- Alerts on delays or blockers
- Suggests timeline adjustments


#### 3. ⚠️ Risk Prediction Agent

**Role**: The Guardian

**What It Does**:
- Identifies technical, resource, and business risks
- Assesses risk probability and impact
- Designs mitigation strategies
- Monitors for risk materialization during execution

**Example Analysis**:
```
Project: "Build a task management app"

Risk Prediction Analysis:
⚠️ HIGH RISK: Real-time synchronization complexity
  - Probability: 70%
  - Impact: Could delay M3 by 2-3 days
  - Mitigation: Use proven library (Socket.io), prototype early
  - Contingency: Fall back to polling if WebSocket fails

⚠️ MEDIUM RISK: Mobile app platform differences
  - Probability: 50%
  - Impact: iOS/Android inconsistencies
  - Mitigation: Use React Native Paper for consistent UI
  - Contingency: Platform-specific code where needed

⚠️ LOW RISK: Database scalability
  - Probability: 20%
  - Impact: Performance issues with > 10K users
  - Mitigation: Index optimization, caching strategy
  - Contingency: Database sharding if needed
```

**Continuous Monitoring**:
- Watches for risk indicators
- Alerts when risks materialize
- Suggests immediate mitigation actions


#### 4. 🔧 Resource Integration Agent

**Role**: The Architect

**What It Does**:
- Assesses technology stack and tools
- Evaluates team skills and gaps
- Plans infrastructure requirements
- Monitors resource consumption during execution

**Example Analysis**:
```
Project: "Build a task management app"

Resource Integration Analysis:
✓ Backend Stack:
  - Framework: FastAPI (async, high performance)
  - Database: PostgreSQL (ACID compliance, JSON support)
  - Cache: Redis (real-time data, session management)
  - Auth: JWT + bcrypt (industry standard)

✓ Frontend Stack:
  - Mobile: React Native (cross-platform, single codebase)
  - State: Redux Toolkit (predictable state management)
  - UI: React Native Paper (Material Design)

✓ Infrastructure:
  - Hosting: AWS (EC2 for API, RDS for database)
  - WebSocket: AWS API Gateway WebSocket
  - CDN: CloudFront (static assets)
  - CI/CD: GitHub Actions

✓ Team Skills Required:
  - Python/FastAPI: ✓ Available
  - React Native: ⚠️ Learning needed (2 days)
  - WebSocket: ⚠️ Learning needed (1 day)
  - AWS: ✓ Available
```

**Continuous Monitoring**:
- Tracks resource usage
- Alerts on shortages or bottlenecks
- Suggests optimizations


#### 5. 🔄 Optimization Iteration Agent

**Role**: The Perfectionist

**What It Does**:
- Analyzes trade-offs and alternatives
- Identifies optimization opportunities
- Suggests continuous improvements
- Monitors code quality and performance

**Example Analysis**:
```
Project: "Build a task management app"

Optimization Analysis:
🔄 Architecture Trade-offs:
  Option A: Monolithic API
    Pros: Simple deployment, easier debugging
    Cons: Harder to scale individual components
  
  Option B: Microservices
    Pros: Independent scaling, technology flexibility
    Cons: Complex deployment, network overhead
  
  Recommendation: Start monolithic, extract services later

🔄 Database Optimization:
  - Use database indexes on user_id, task_id, created_at
  - Implement query result caching for frequent reads
  - Use connection pooling (max 20 connections)

🔄 Performance Targets:
  - API response time: < 200ms (p95)
  - WebSocket latency: < 50ms
  - Mobile app startup: < 2 seconds

🔄 Code Quality:
  - Test coverage: > 80%
  - Code complexity: < 10 cyclomatic complexity
  - Documentation: All public APIs documented
```

**Continuous Monitoring**:
- Analyzes code commits for quality
- Suggests refactoring opportunities
- Alerts on performance degradation


### Think Tank Workflow

```
User Input: "Build a task management app with real-time collaboration"
    │
    ▼
┌─────────────────────────────────────────────────────────────┐
│ Think Tank Orchestrator                                     │
│ Coordinates all 5 perspective agents                        │
└─────────────────────────────────────────────────────────────┘
    │
    ├──────────────────┬──────────────────┬──────────────────┐
    ▼                  ▼                  ▼                  ▼
Goal Focus      Path Planning      Risk Prediction    Resource Integ.
    │                  │                  │                  │
    ▼                  ▼                  ▼                  ▼
Clarify goals    Design roadmap    Identify risks    Assess resources
    │                  │                  │                  │
    └──────────────────┴──────────────────┴──────────────────┘
                            │
                            ▼
                  Optimization Iteration
                  (Synthesize all perspectives)
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│ Requirement Card Generation                                 │
│ • Complete project specification                            │
│ • All 5 perspectives integrated                             │
│ • Ready for execution                                       │
└─────────────────────────────────────────────────────────────┘
```

---

## 🤖 Organizational Agent Cluster

SpineWorks includes 50+ specialized agents organized into categories. The system dynamically selects the right agents based on your project needs.

### Core Agents (Always Active)


#### 1. Secretary Agent - The Coordinator 🎯

**Always Active | Central Hub**

**Core Responsibilities**:
- **User Interaction**: Terminal interface, menu system, input collection
- **Progress Tracking**: Monitor all agents, calculate ETA, send updates
- **Interrupt Handling**: Process user interrupts with safe-point strategy
- **Alert Routing**: Route alerts by severity (critical/warning/info)
- **Context Management**: Track active agents, tasks, blockers
- **Reflow Management**: Handle quality issues and rework requests

**Key Features**:
- Interrupt handling with safe-point strategy (pause at safe moments)
- Progress updates every 30 minutes (configurable)
- Alert routing: Critical alerts pause execution, warnings logged
- Context awareness: Knows what every agent is doing

**Example Interaction**:
```
🤝 Secretary: Starting project analysis...
🤝 Secretary: Think Tank analysis complete. 5 perspectives analyzed.
🤝 Secretary: Assembling agent team... 8 agents selected.
🤝 Secretary: [Progress] PM Agent: Requirements analysis (30% complete)
🤝 Secretary: [Alert] Risk Prediction: WebSocket complexity detected
🤝 Secretary: [Progress] Tech Lead: Architecture design (60% complete)
🤝 Secretary: Project complete! All deliverables ready.
```

#### 2. PM Agent - The Project Manager 📋

**Always Active | Requirements & Planning**

**Core Responsibilities**:
- Requirements analysis and clarification
- Task breakdown and prioritization
- Milestone planning and tracking
- Progress control and reporting
- Think Tank consultation when needed

**Capabilities**:
- Asks clarifying questions to understand requirements
- Breaks down complex projects into manageable tasks
- Creates detailed project plans with timelines
- Monitors progress and adjusts plans as needed
- Consults Think Tank agents for deep analysis


#### 3. Orchestration Decider - The Team Builder 🎭

**Always Active | Dynamic Agent Selection**

**Core Responsibilities**:
- Extract project profile from requirements
- Select optimal agent team based on project characteristics
- Resolve agent dependencies automatically
- Present team to user for confirmation
- Manage agent lifecycle

**Selection Algorithm**:
```
1. Analyze requirement card
   ├─→ Project size: tiny/small/medium/large
   ├─→ Domains: backend/frontend/data/cloud
   └─→ Attributes: security/performance/compliance

2. Match agents by criteria
   ├─→ Required agents (always needed)
   ├─→ Domain-matched agents (backend → Backend Dev)
   ├─→ Attribute-matched agents (security → Security Agent)
   └─→ Dependency resolution (Tech Lead → Backend Dev)

3. Present to user
   ├─→ Show selected team
   ├─→ Allow customization (add/remove)
   └─→ Confirm and proceed
```

**Example Selection**:
```
Project: E-commerce platform with payment
Profile: Medium size, Backend + Frontend + Cloud, Security-sensitive

Selected Team:
✓ Core: Secretary, PM, Orchestration Decider
✓ Think Tank: All 5 perspective agents (Think Tank mode)
✓ Execution: Tech Lead, Backend Dev, Frontend Dev, Ops
✓ Quality: Security Agent (auto-enabled for payment)

User can add: QA Agent, Performance Test Agent
User can remove: Frontend Dev (if backend-only MVP)
```


### Execution Agents (Development)

#### 4. Tech Lead Agent - The Architect 🏗️

**Conditional | Architecture & Design**

**When Activated**: Projects with backend, frontend, or complex architecture

**Core Responsibilities**:
- System architecture design
- Technology stack selection
- Architecture review and validation
- Technical decision making
- Design pattern recommendations

**Capabilities**:
- Designs scalable, maintainable architectures
- Selects appropriate technologies for requirements
- Reviews code for architectural compliance
- Makes trade-off decisions (performance vs simplicity)
- Consults Risk Prediction Agent for architecture risks

**Example Output**:
```
Architecture Design: Task Management App

System Architecture:
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Mobile    │────▶│   API       │────▶│  Database   │
│   Client    │◀────│  Gateway    │◀────│ PostgreSQL  │
└─────────────┘     └─────────────┘     └─────────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │  WebSocket  │
                    │   Server    │
                    └─────────────┘

Technology Stack:
- API: FastAPI (async, high performance)
- Database: PostgreSQL + Redis cache
- WebSocket: Socket.io
- Mobile: React Native
- Deployment: Docker + AWS ECS

Design Patterns:
- Repository pattern for data access
- Service layer for business logic
- Event-driven for real-time updates
- JWT for stateless authentication
```


#### 5. Backend Dev Agent - The Builder 💻

**Conditional | Backend Implementation**

**When Activated**: Projects with backend/API requirements

**Core Responsibilities**:
- API endpoint development
- Database schema design
- Business logic implementation
- Integration with external services
- Backend testing

**Capabilities**:
- Implements RESTful APIs with proper HTTP methods
- Designs normalized database schemas
- Writes clean, maintainable business logic
- Integrates third-party APIs (payment, email, etc.)
- Writes unit and integration tests
- **Scalable**: Can run multiple instances for large projects (Phase 4.1)

**Example Output**:
```python
# Task Management API Implementation

# models.py
class Task(Base):
    __tablename__ = "tasks"
    
    id = Column(UUID, primary_key=True, default=uuid4)
    title = Column(String(200), nullable=False)
    description = Column(Text)
    status = Column(Enum(TaskStatus), default=TaskStatus.TODO)
    user_id = Column(UUID, ForeignKey("users.id"))
    created_at = Column(DateTime, default=datetime.utcnow)
    
    user = relationship("User", back_populates="tasks")

# api.py
@router.post("/tasks", response_model=TaskResponse)
async def create_task(
    task: TaskCreate,
    current_user: User = Depends(get_current_user),
    db: Session = Depends(get_db)
):
    """Create a new task for the current user."""
    new_task = Task(**task.dict(), user_id=current_user.id)
    db.add(new_task)
    db.commit()
    
    # Broadcast real-time event
    await websocket_manager.broadcast({
        "type": "task_created",
        "task": TaskResponse.from_orm(new_task).dict()
    })
    
    return new_task
```


#### 6. Frontend Dev Agent - The UI Expert 🎨

**Conditional | Frontend Implementation**

**When Activated**: Projects with web/mobile UI requirements

**Status**: Planned for Phase 6

**Core Responsibilities**:
- UI/UX implementation
- Client-side logic and state management
- Responsive design
- API integration
- Frontend testing

**Capabilities**:
- Implements modern, responsive UIs
- Manages complex application state
- Integrates with backend APIs
- Handles real-time updates (WebSocket)
- Writes component and E2E tests
- **Scalable**: Can run multiple instances by page/module

#### 7. Data Dev Agent - The Data Engineer 📊

**Conditional | Data Processing**

**When Activated**: Projects with ETL, analytics, or data warehouse needs

**Status**: Planned for Phase 6

**Core Responsibilities**:
- ETL pipeline development
- Data modeling and schema design
- Analytics and reporting
- Data warehouse setup
- Data quality assurance

**Capabilities**:
- Builds scalable data pipelines
- Designs star/snowflake schemas
- Implements data transformations
- Creates analytics dashboards
- Ensures data quality and consistency
- **Scalable**: Can run multiple instances by table/pipeline


#### 8. Ops Agent - The Deployer 🚀

**Conditional | Deployment & Operations**

**When Activated**: Projects requiring deployment configuration

**Core Responsibilities**:
- Environment configuration
- Deployment script creation
- CI/CD pipeline setup
- Infrastructure as code
- Monitoring and logging setup

**Capabilities**:
- Creates Docker containers and docker-compose files
- Writes deployment scripts for various platforms
- Sets up GitHub Actions / GitLab CI pipelines
- Configures environment variables and secrets
- Sets up basic monitoring and logging

**Example Output**:
```yaml
# docker-compose.yml
version: '3.8'

services:
  api:
    build: ./backend
    ports:
      - "8000:8000"
    environment:
      - DATABASE_URL=postgresql://user:pass@db:5432/taskdb
      - REDIS_URL=redis://redis:6379
    depends_on:
      - db
      - redis
  
  db:
    image: postgres:15
    volumes:
      - postgres_data:/var/lib/postgresql/data
    environment:
      - POSTGRES_DB=taskdb
      - POSTGRES_USER=user
      - POSTGRES_PASSWORD=pass
  
  redis:
    image: redis:7-alpine
    ports:
      - "6379:6379"

volumes:
  postgres_data:
```


### Quality Agents (QA & Security)

#### 9. Code Review Agent - The Quality Guardian 🔍

**Conditional | Code Quality**

**When Activated**: Quality-first projects or user request

**Status**: Phase 4.1 (Next)

**Core Responsibilities**:
- Code quality analysis
- Best practices enforcement
- Maintainability assessment
- Refactoring suggestions
- Code smell detection

**Capabilities**:
- Analyzes code for PEP8/ESLint compliance
- Calculates cyclomatic complexity
- Detects code smells (long methods, god classes)
- Suggests refactoring opportunities
- Scores code on maintainability index

**Example Analysis**:
```
Code Review Report: Task API

Overall Score: 85/100 (Good)

✓ Strengths:
  - Clear function names and documentation
  - Proper error handling
  - Good test coverage (82%)

⚠️ Issues Found:
  1. High Complexity (Priority: Medium)
     File: api/tasks.py, Function: create_task_with_validation
     Cyclomatic Complexity: 12 (threshold: 10)
     Recommendation: Extract validation logic to separate function

  2. Code Duplication (Priority: Low)
     Files: api/tasks.py, api/projects.py
     Lines: 45-60 (authentication logic)
     Recommendation: Create shared auth decorator

  3. Missing Type Hints (Priority: Low)
     File: utils/helpers.py
     Functions: 3 functions missing return type hints
     Recommendation: Add type hints for better IDE support
```


#### 10. Security Agent - The Guardian 🛡️

**Conditional | Security Analysis**

**When Activated**: Security-sensitive projects (auth, payment, PII)

**Status**: Phase 4.1 (Next)

**Core Responsibilities**:
- Vulnerability scanning
- Security best practices enforcement
- Compliance checking
- Dependency vulnerability analysis
- Sensitive data detection

**Capabilities**:
- Scans for OWASP Top 10 vulnerabilities
- Detects hardcoded secrets and credentials
- Analyzes dependencies for known vulnerabilities
- Checks for SQL injection, XSS, CSRF risks
- Validates authentication and authorization logic

**Example Analysis**:
```
Security Scan Report: Task API

Overall Security Score: 78/100 (Needs Improvement)

🚨 CRITICAL Issues (Must Fix):
  1. Hardcoded Secret Key
     File: config.py, Line: 15
     Issue: JWT secret key hardcoded in source
     Risk: Token forgery, unauthorized access
     Fix: Move to environment variable

  2. SQL Injection Risk
     File: api/search.py, Line: 42
     Issue: Raw SQL query with user input
     Risk: Database compromise
     Fix: Use parameterized queries or ORM

⚠️ HIGH Issues (Should Fix):
  1. Missing Rate Limiting
     Endpoints: /api/login, /api/register
     Risk: Brute force attacks
     Fix: Implement rate limiting (10 req/min)

  2. Weak Password Policy
     File: auth/validators.py
     Issue: Minimum 6 characters, no complexity
     Fix: Require 8+ chars, mixed case, numbers

✓ PASSED Checks:
  - HTTPS enforced
  - CORS properly configured
  - Password hashing (bcrypt)
  - JWT expiration set
```


#### 11. QA Agent - The Tester 🧪

**Conditional | Testing & Quality Assurance**

**When Activated**: Quality-first projects or user request

**Status**: Phase 4.1 (Next)

**Core Responsibilities**:
- Test case generation
- Automated testing
- Coverage analysis
- Regression testing
- Test maintenance

**Capabilities**:
- Generates unit, integration, and E2E tests
- Achieves high test coverage (>80%)
- Runs automated test suites
- Identifies untested code paths
- Maintains test quality over time

#### 12. Performance Test Agent - The Optimizer ⚡

**Conditional | Performance Testing**

**When Activated**: High-concurrency or performance-critical projects

**Status**: Phase 4.1 (Next)

**Core Responsibilities**:
- Load testing
- Bottleneck identification
- Performance optimization
- Scalability testing
- Performance monitoring

**Capabilities**:
- Simulates high user loads
- Identifies performance bottlenecks
- Suggests optimization strategies
- Tests horizontal/vertical scaling
- Validates performance targets


### Enhancement Agents (Optional)

#### 13. Compliance Agent - The Auditor 📜

**Optional | Regulatory Compliance**

**When Activated**: Finance, healthcare, or compliance-required projects

**Status**: Phase 5 (Future)

**Capabilities**:
- GDPR compliance checking
- HIPAA compliance validation
- SOC2 audit preparation
- Compliance documentation
- Audit trail generation

#### 14. Cost Calculator Agent - The Economist 💰

**Optional | Cost Management**

**When Activated**: Cloud projects or cost-tracking needs

**Status**: Phase 5 (Future)

**Capabilities**:
- Cloud resource cost estimation
- Cost optimization recommendations
- Budget tracking and alerts
- ROI analysis
- Cost breakdown by service

#### 15. Docs Automation Agent - The Writer 📝

**Optional | Documentation**

**When Activated**: Projects requiring comprehensive documentation

**Status**: Phase 5 (Future)

**Capabilities**:
- API documentation generation
- User guide creation
- Technical writing
- Diagram generation
- Documentation maintenance


#### 16. I18n/L10n Agent - The Translator 🌍

**Optional | Internationalization**

**When Activated**: Multi-language projects

**Status**: Phase 5 (Future)

**Capabilities**:
- Multi-language support setup
- Translation management
- Cultural adaptation
- Locale handling
- RTL language support

#### 17. Monitoring Agent - The Observer 👁️

**Optional | Observability**

**When Activated**: Production deployments

**Status**: Phase 5 (Future)

**Capabilities**:
- Metrics collection setup
- Logging infrastructure
- Alerting configuration
- Dashboard creation
- Performance monitoring

### Complete Agent Catalog

**Total: 50+ Agents** across all categories:

| Category | Count | Examples |
|----------|-------|----------|
| **Core** | 3 | Secretary, PM, Orchestration Decider |
| **Think Tank** | 5 | Goal Focus, Path Planning, Risk Prediction, Resource Integration, Optimization |
| **Execution** | 15+ | Tech Lead, Backend Dev, Frontend Dev, Mobile Dev, Data Dev, Ops, etc. |
| **Quality** | 10+ | Code Review, Security, QA, Performance Test, Compatibility Test, etc. |
| **Enhancement** | 15+ | Compliance, Cost Calculator, Docs, I18n, Monitoring, etc. |
| **Dynamic** | ∞ | Generated on-demand for specific scenarios |

---


## 👔 Secretary Agent

The Secretary Agent is the **always-on coordinator** - your single point of contact with the entire SpineWorks system.

### Core Capabilities

#### 1. User Interaction 💬

**Terminal Interface**:
- Beautiful Rich-based CLI with colors and formatting
- Interactive menus for mode selection
- Progress bars and status updates
- Real-time agent activity display

**Communication Style**:
- Clear, concise updates
- Emoji indicators for different message types
- Structured output for complex information
- User-friendly error messages

**Example Interaction**:
```
🤝 Secretary: Welcome to SpineWorks! How can I help you today?

Choose your entry mode:
1. 🧠 Think Tank Mode - Deep analysis before execution
2. ⚡ Direct Execution - Quick start with PM Agent
3. 📋 Resume Project - Continue existing project

Your choice: 1

🤝 Secretary: Excellent! Think Tank mode selected.
🤝 Secretary: Please describe your project...

User: Build a real-time chat application

🤝 Secretary: Got it! Starting Think Tank analysis...
🤝 Secretary: [1/5] Goal Focus Agent analyzing objectives...
🤝 Secretary: [2/5] Path Planning Agent designing roadmap...
🤝 Secretary: [3/5] Risk Prediction Agent identifying risks...
🤝 Secretary: [4/5] Resource Integration Agent assessing stack...
🤝 Secretary: [5/5] Optimization Agent refining solution...
🤝 Secretary: ✓ Think Tank analysis complete!
```


#### 2. Progress Tracking 📊

**Real-Time Monitoring**:
- Tracks all active agents and their tasks
- Calculates estimated time to completion
- Sends periodic progress updates (default: 30 minutes)
- Identifies blockers and bottlenecks

**Progress Update Format**:
```
🤝 Secretary: [Progress Update - 30 minutes elapsed]

Active Agents:
✓ PM Agent: Requirements analysis (100% complete)
⏳ Tech Lead Agent: Architecture design (60% complete)
⏳ Backend Dev Agent: API implementation (30% complete)
⏸️ Ops Agent: Waiting for backend completion

Milestones:
✓ M1: Requirements (Complete)
⏳ M2: Architecture (In Progress - 60%)
⏸️ M3: Implementation (Not Started)
⏸️ M4: Deployment (Not Started)

Estimated Time Remaining: 2.5 hours

Blockers: None
Risks: None materialized
```

#### 3. Interrupt Handling ⏸️

**Safe-Point Strategy**:

When you interrupt during execution, the Secretary:

1. **Immediate Acknowledgment** (< 1 second)
   ```
   🤝 Secretary: Got it! Processing your request...
   ```

2. **Parse Intent**
   - What does the user want?
   - How urgent is it?

3. **Signal Agents**
   - Publish `interrupt_requested` event
   - Wait for agents to reach safe points
   - Safe points: after LLM call, after file write, after commit

4. **Execute Action**
   - Answer questions
   - Adjust parameters
   - Change direction

5. **Resume**
   - Agents continue from safe point


**Example Interrupt**:
```
[Backend Dev Agent is writing code...]

User: Wait! Can we use MongoDB instead of PostgreSQL?

🤝 Secretary: Got it! Pausing agents at safe point...
🤝 Secretary: ✓ All agents paused safely

🤝 Secretary: You want to switch from PostgreSQL to MongoDB.
🤝 Secretary: This affects:
  - Database schema design
  - ORM choice (SQLAlchemy → Motor)
  - Query patterns

🤝 Secretary: Consulting Tech Lead Agent...

🤝 Tech Lead: MongoDB is suitable for this use case.
🤝 Tech Lead: Trade-offs:
  ✓ Pros: Flexible schema, horizontal scaling
  ⚠️ Cons: No ACID transactions, learning curve

🤝 Secretary: Shall I proceed with MongoDB? (yes/no)

User: yes

🤝 Secretary: ✓ Updating architecture to use MongoDB
🤝 Secretary: ✓ Resuming execution with new direction
```

#### 4. Alert Routing 🚨

**Severity Levels**:

| Severity | Action | Example |
|----------|--------|---------|
| **CRITICAL** | Pause + Immediate notification | Goal drift >50%, security vulnerability |
| **WARNING** | Log + Next update | Minor goal drift, resource warning |
| **INFO** | Log only | Optimization suggestion |

**Example Critical Alert**:
```
🚨 CRITICAL ALERT from Risk Prediction Agent

Issue: WebSocket implementation complexity exceeds estimate
Impact: Milestone 3 may be delayed by 2-3 days
Recommendation: Consider using Socket.io library instead of custom implementation

Options:
1. Continue with custom implementation (higher risk)
2. Switch to Socket.io (recommended, lower risk)
3. Consult with Tech Lead for alternatives

Your choice: 2

🤝 Secretary: ✓ Switching to Socket.io
🤝 Secretary: ✓ Updating architecture and timeline
🤝 Secretary: ✓ Resuming execution
```

---


## 🎭 Dynamic Agent Generation System

SpineWorks goes beyond fixed agents - it can **generate specialized agents on-demand** for any scenario.

### Three-Layer Architecture

```
┌─────────────────────────────────────────────────────────────┐
│ LAYER 1: Core Agents (Preset - Always Available)           │
├─────────────────────────────────────────────────────────────┤
│ • Meta Coordinator: Orchestrates entire system              │
│ • Agent Factory: Generates new agents dynamically           │
│ • File Analyzer: Processes uploaded documents               │
│ • Secretary Agent: User interface and coordination          │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│ LAYER 2: Scene Coordinators (Dynamic - Task-Based)         │
├─────────────────────────────────────────────────────────────┤
│ Software Development → PM Agent                             │
│ Research Analysis → Research Coordinator                    │
│ Content Creation → Chief Editor                             │
│ Business Analysis → Business Analyst                        │
│ Data Science → Data Science Lead                            │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│ LAYER 3: Specialized Workers (Dynamic - On-Demand)         │
├─────────────────────────────────────────────────────────────┤
│ Generated based on specific task requirements               │
│ • Literature Reviewer (for research)                        │
│ • Content Writer (for writing)                              │
│ • Data Analyst (for analysis)                               │
│ • Domain Expert (for specialized knowledge)                 │
│ • ... and more as needed                                    │
└─────────────────────────────────────────────────────────────┘
```

### User Confirmation Flow

```
User Request
    │
    ▼
Meta Coordinator analyzes task type
    │
    ▼
Agent Factory proposes team
    │
    ├─→ Scene Coordinator: Research Coordinator
    ├─→ Workers: Literature Reviewer, Data Analyst, Report Writer
    └─→ Support: File Analyzer, Citation Manager
    │
    ▼
Present to User
    │
    ├─→ "I recommend these agents for your research task:"
    ├─→ Show agent descriptions and roles
    └─→ "Would you like to add or remove any agents?"
    │
    ▼
User Customization
    │
    ├─→ User adds: Domain Expert (Biology)
    ├─→ User removes: Report Writer (will write manually)
    └─→ User confirms team
    │
    ▼
Generate and Execute
```


### Scenario Examples

#### Scenario 1: Software Development

**Task**: "Build a REST API for task management"

**Proposed Team**:
- **Scene Coordinator**: PM Agent
- **Workers**: Tech Lead, Backend Dev, Ops Agent
- **Support**: Code Review Agent, Security Agent

**User Confirmation**:
```
🤝 Secretary: I recommend this team for your software project:

Scene Coordinator:
✓ PM Agent - Requirements analysis and project management

Execution Agents:
✓ Tech Lead Agent - Architecture design
✓ Backend Dev Agent - API implementation
✓ Ops Agent - Deployment configuration

Quality Agents:
✓ Code Review Agent - Code quality assurance
✓ Security Agent - Security scanning (auto-enabled for APIs)

Would you like to add or remove any agents?
Options:
1. Add QA Agent (automated testing)
2. Add Performance Test Agent (load testing)
3. Remove Security Agent (if not needed)
4. Proceed with current team

Your choice: 1

🤝 Secretary: ✓ Added QA Agent to the team
🤝 Secretary: Final team: 7 agents
🤝 Secretary: Estimated cost: $2.50 (based on LLM usage)
🤝 Secretary: Proceed? (yes/no): yes
```


#### Scenario 2: Research Analysis

**Task**: "Analyze recent papers on quantum computing applications"

**Proposed Team**:
- **Scene Coordinator**: Research Coordinator (dynamically generated)
- **Workers**: Literature Reviewer, Data Analyst, Summary Writer (all generated)
- **Support**: File Analyzer, Citation Manager (generated)

**User Confirmation**:
```
🤝 Secretary: I recommend this team for your research task:

Scene Coordinator:
✓ Research Coordinator (NEW) - Orchestrates research workflow

Research Agents:
✓ Literature Reviewer (NEW) - Analyzes papers and extracts insights
✓ Data Analyst (NEW) - Processes research data and trends
✓ Summary Writer (NEW) - Creates comprehensive summaries

Support Agents:
✓ File Analyzer - Processes uploaded PDF papers
✓ Citation Manager (NEW) - Manages references and citations

Would you like to add or remove any agents?
Options:
1. Add Domain Expert (Quantum Physics)
2. Add Visualization Agent (create charts/graphs)
3. Remove Summary Writer (manual writing)
4. Proceed with current team

Your choice: 1

🤝 Secretary: ✓ Added Domain Expert (Quantum Physics) to the team
🤝 Secretary: This agent will provide specialized knowledge on quantum computing
🤝 Secretary: Final team: 7 agents (5 dynamically generated)
🤝 Secretary: Proceed? (yes/no): yes
```


#### Scenario 3: Content Creation

**Task**: "Write a comprehensive guide on machine learning for beginners"

**Proposed Team**:
- **Scene Coordinator**: Chief Editor (dynamically generated)
- **Workers**: Content Writer, Technical Reviewer, SEO Specialist (all generated)
- **Support**: Outline Generator, Fact Checker (generated)

**User Confirmation**:
```
🤝 Secretary: I recommend this team for your writing project:

Scene Coordinator:
✓ Chief Editor (NEW) - Oversees content creation and quality

Writing Agents:
✓ Content Writer (NEW) - Writes engaging, clear content
✓ Technical Reviewer (NEW) - Ensures technical accuracy
✓ SEO Specialist (NEW) - Optimizes for search engines

Support Agents:
✓ Outline Generator (NEW) - Creates structured outlines
✓ Fact Checker (NEW) - Verifies claims and statistics

Would you like to add or remove any agents?
Options:
1. Add Illustrator Agent (create diagrams)
2. Add Code Example Generator (for ML examples)
3. Remove SEO Specialist (not needed)
4. Proceed with current team

Your choice: 2

🤝 Secretary: ✓ Added Code Example Generator to the team
🤝 Secretary: This agent will create Python code examples for ML concepts
🤝 Secretary: Final team: 7 agents (all dynamically generated)
🤝 Secretary: Proceed? (yes/no): yes
```

### Agent Template System

Dynamic agents are generated from templates:

```python
# Agent Template
{
    "agent_type": "Literature Reviewer",
    "category": "research",
    "capabilities": [
        "Read and analyze academic papers",
        "Extract key findings and methodologies",
        "Identify research gaps",
        "Compare multiple papers",
        "Generate literature review summaries"
    ],
    "llm_prompt_template": """
        You are a Literature Reviewer agent specializing in {domain}.
        Your role is to analyze academic papers and extract insights.
        
        For each paper, you should:
        1. Summarize the main contribution
        2. Identify the methodology used
        3. Extract key findings
        4. Note limitations
        5. Suggest connections to other papers
    """,
    "input_types": ["pdf", "text", "url"],
    "output_types": ["summary", "analysis", "comparison"]
}
```

---


## 📂 File Upload & Analysis

SpineWorks supports uploading documents for AI analysis - perfect for analyzing books, research papers, reports, and more.

### Supported File Types

- **Documents**: PDF, DOCX, TXT, MD
- **Spreadsheets**: XLSX, CSV
- **Code**: PY, JS, TS, JAVA, etc.
- **Data**: JSON, XML, YAML
- **Images**: PNG, JPG (OCR support)

### Upload Workflow

```
User uploads file(s)
    │
    ▼
File Analyzer Agent processes files
    │
    ├─→ Extract text content
    ├─→ Identify structure (chapters, sections)
    ├─→ Extract metadata (author, date, etc.)
    └─→ Create searchable index
    │
    ▼
Meta Coordinator determines task type
    │
    ├─→ Book analysis → Chief Editor + Content Analyst
    ├─→ Research paper → Research Coordinator + Literature Reviewer
    ├─→ Code review → Tech Lead + Code Review Agent
    └─→ Data analysis → Data Science Lead + Data Analyst
    │
    ▼
Propose agent team to user
    │
    ▼
Execute analysis with agent cluster
```

### Example: Book Analysis

**Task**: "Analyze this book on software architecture"

**Upload**: `clean-architecture.pdf` (400 pages)

**Workflow**:
```
🤝 Secretary: File uploaded: clean-architecture.pdf (400 pages)
🤝 Secretary: File Analyzer processing...
🤝 Secretary: ✓ Extracted 15 chapters, 87 sections
🤝 Secretary: ✓ Identified key concepts: SOLID, Clean Architecture, Dependency Rule

🤝 Secretary: This appears to be a technical book on software architecture.
🤝 Secretary: I recommend this team for analysis:

Scene Coordinator:
✓ Technical Book Analyst (NEW) - Coordinates book analysis

Analysis Agents:
✓ Chapter Summarizer (NEW) - Summarizes each chapter
✓ Concept Extractor (NEW) - Identifies key concepts and patterns
✓ Code Example Analyzer (NEW) - Analyzes code examples
✓ Practical Application Agent (NEW) - Suggests real-world applications

Would you like to add or remove any agents? (yes/no): no

🤝 Secretary: ✓ Starting analysis with 5 agents...
🤝 Secretary: [Progress] Chapter Summarizer: Processing chapters 1-5 (33%)
🤝 Secretary: [Progress] Concept Extractor: Identified 23 key concepts
🤝 Secretary: [Progress] Code Example Analyzer: Analyzed 15 code examples
🤝 Secretary: ✓ Analysis complete!

Deliverables:
✓ Complete book summary (5 pages)
✓ Key concepts glossary (23 concepts)
✓ Code examples analysis (15 examples)
✓ Practical application guide (10 scenarios)
✓ Mind map of concepts (visual diagram)
```


### Example: Research Paper Analysis

**Task**: "Analyze these 10 papers on transformer models"

**Upload**: 10 PDF files

**Workflow**:
```
🤝 Secretary: Files uploaded: 10 research papers
🤝 Secretary: File Analyzer processing...
🤝 Secretary: ✓ Total pages: 127
🤝 Secretary: ✓ Identified common themes: attention mechanism, BERT, GPT

🤝 Secretary: I recommend this team for research analysis:

Scene Coordinator:
✓ Research Coordinator (NEW) - Orchestrates multi-paper analysis

Research Agents:
✓ Literature Reviewer (NEW) - Analyzes each paper
✓ Trend Analyzer (NEW) - Identifies trends across papers
✓ Methodology Comparator (NEW) - Compares research methods
✓ Citation Network Builder (NEW) - Maps paper relationships

Support Agents:
✓ File Analyzer - Processes PDFs
✓ Visualization Agent (NEW) - Creates charts and graphs

Would you like to add Domain Expert (NLP)? (yes/no): yes

🤝 Secretary: ✓ Added Domain Expert (NLP) to the team
🤝 Secretary: ✓ Starting analysis with 8 agents...

[Analysis in progress...]

🤝 Secretary: ✓ Analysis complete!

Deliverables:
✓ Individual paper summaries (10 papers)
✓ Comparative analysis report
✓ Trend analysis: Evolution of transformer architectures
✓ Methodology comparison matrix
✓ Citation network diagram
✓ Research gaps and future directions
```

---


## 🔄 Complete Workflow Examples

### Workflow 1: Software Development (Think Tank Mode)

```
User: "Build an e-commerce platform with payment integration"
    │
    ▼
🤝 Secretary: Think Tank mode selected
    │
    ▼
Think Tank Analysis (5 perspectives)
    │
    ├─→ 🎯 Goal Focus: B2C platform, secure payments, scalable
    ├─→ 🗺️ Path Planning: 6 milestones, 4 weeks timeline
    ├─→ ⚠️ Risk Prediction: Payment security, PCI compliance
    ├─→ 🔧 Resource Integration: React, FastAPI, Stripe, AWS
    └─→ 🔄 Optimization: Microservices vs monolith analysis
    │
    ▼
Requirement Card Generated
    │
    ▼
Orchestration Decider: Extract project profile
    │
    ├─→ Size: Medium
    ├─→ Domains: Backend, Frontend, Cloud
    └─→ Attributes: security_sensitive, high_concurrency
    │
    ▼
Propose Agent Team
    │
    ├─→ Core: Secretary, PM, Orchestration Decider
    ├─→ Think Tank: All 5 perspective agents (monitoring)
    ├─→ Execution: Tech Lead, Backend Dev, Frontend Dev, Ops
    └─→ Quality: Security Agent (auto-enabled for payment)
    │
    ▼
User Confirmation
    │
    ├─→ User adds: QA Agent, Performance Test Agent
    └─→ User confirms: 13 agents total
    │
    ▼
Execution Pipeline
    │
    ├─→ PM Agent: Break down requirements
    ├─→ Tech Lead: Design architecture
    ├─→ Backend Dev: Implement API + payment integration
    ├─→ Frontend Dev: Build UI components
    ├─→ Security Agent: Scan for vulnerabilities
    ├─→ QA Agent: Generate and run tests
    ├─→ Performance Test: Load testing
    └─→ Ops Agent: Create deployment scripts
    │
    ▼
Continuous Monitoring (Think Tank)
    │
    ├─→ Goal Focus: Monitors goal alignment
    ├─→ Risk Prediction: Watches for risk materialization
    └─→ Resource Integration: Tracks resource usage
    │
    ▼
Deliverables
    │
    ├─→ Complete source code (backend + frontend)
    ├─→ Database schema and migrations
    ├─→ Stripe payment integration
    ├─→ Security scan report
    ├─→ Test suite (80%+ coverage)
    ├─→ Performance test results
    ├─→ Docker deployment configuration
    ├─→ CI/CD pipeline (GitHub Actions)
    └─→ Complete documentation
```


### Workflow 2: Research Analysis (Direct Mode)

```
User: "Analyze recent trends in AI safety research"
    │
    ▼
🤝 Secretary: Direct execution mode
    │
    ▼
Meta Coordinator: Identify task type → Research
    │
    ▼
Agent Factory: Generate research team
    │
    ├─→ Scene Coordinator: Research Coordinator (NEW)
    ├─→ Workers: Literature Reviewer, Trend Analyzer (NEW)
    └─→ Support: File Analyzer, Citation Manager (NEW)
    │
    ▼
User Confirmation
    │
    ├─→ User adds: Domain Expert (AI Safety)
    └─→ User confirms: 6 agents (5 dynamically generated)
    │
    ▼
Research Coordinator: Plan research workflow
    │
    ├─→ Phase 1: Literature search and collection
    ├─→ Phase 2: Paper analysis and summarization
    ├─→ Phase 3: Trend identification
    └─→ Phase 4: Report generation
    │
    ▼
Execution
    │
    ├─→ Literature Reviewer: Analyze 50 papers
    ├─→ Trend Analyzer: Identify 5 major trends
    ├─→ Domain Expert: Provide specialized insights
    └─→ Citation Manager: Build reference network
    │
    ▼
Deliverables
    │
    ├─→ Comprehensive literature review (20 pages)
    ├─→ Trend analysis report with visualizations
    ├─→ Key findings and insights
    ├─→ Research gaps and future directions
    └─→ Citation network diagram
```


### Workflow 3: Content Creation (Agent Cluster)

```
User: "Write a comprehensive guide on cloud architecture (10,000 words)"
    │
    ▼
🤝 Secretary: Large writing project detected
    │
    ▼
Meta Coordinator: Identify task type → Content Creation
    │
    ▼
Agent Factory: Generate writing team
    │
    ├─→ Scene Coordinator: Chief Editor (NEW)
    ├─→ Writers: 3x Content Writer (NEW) - parallel writing
    ├─→ Support: Outline Generator, Technical Reviewer (NEW)
    └─→ Quality: Fact Checker, SEO Specialist (NEW)
    │
    ▼
User Confirmation
    │
    ├─→ User adds: Code Example Generator, Illustrator
    └─→ User confirms: 10 agents (agent cluster)
    │
    ▼
Chief Editor: Plan content structure
    │
    ├─→ Chapter 1: Introduction to Cloud (Writer 1)
    ├─→ Chapter 2: Core Services (Writer 2)
    ├─→ Chapter 3: Architecture Patterns (Writer 3)
    ├─→ Chapter 4: Best Practices (Writer 1)
    └─→ Chapter 5: Case Studies (Writer 2)
    │
    ▼
Parallel Execution (Agent Cluster)
    │
    ├─→ Writer 1: Chapters 1, 4 (3,000 words)
    ├─→ Writer 2: Chapters 2, 5 (3,500 words)
    ├─→ Writer 3: Chapter 3 (3,500 words)
    ├─→ Code Example Generator: 20 code examples
    ├─→ Illustrator: 15 diagrams
    └─→ Technical Reviewer: Verify accuracy
    │
    ▼
Chief Editor: Integrate and polish
    │
    ├─→ Merge all chapters
    ├─→ Ensure consistent style
    ├─→ Add transitions
    └─→ Final review
    │
    ▼
Quality Checks
    │
    ├─→ Fact Checker: Verify all claims
    ├─→ SEO Specialist: Optimize for search
    └─→ Technical Reviewer: Final accuracy check
    │
    ▼
Deliverables
    │
    ├─→ Complete guide (10,000 words)
    ├─→ 20 code examples
    ├─→ 15 architecture diagrams
    ├─→ SEO-optimized content
    └─→ Fact-checked and reviewed
```

---


## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/spineworks.git
cd spineworks

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install SpineWorks
pip install -e .
```

### Configuration

Create `~/.spineworks/config.yaml`:

```yaml
# LLM Configuration
llm:
  provider: "anthropic"  # or "openai", "google"
  model: "claude-3-5-sonnet-20241022"
  api_key: "your-api-key-here"
  temperature: 0.7
  max_tokens: 4096

# Default entry mode
default_entry_mode: "ask"  # Options: ask, think, direct

# Secretary settings
secretary:
  progress_update_interval: 1800  # 30 minutes
  interrupt_strategy: "safe_point"

# Dynamic agent generation
dynamic_agents:
  enabled: true
  user_confirmation_required: true
  max_agents_per_task: 20
```

### Basic Usage

#### Option 1: Think Tank Mode (Recommended)

```bash
spineworks think "Build a REST API for task management"
```

#### Option 2: Direct Execution

```bash
spineworks start --direct "Create a Python CLI tool"
```

#### Option 3: Interactive Mode

```bash
spineworks
```

#### Option 4: File Upload & Analysis

```bash
spineworks analyze --file research-paper.pdf
```

---


# 中文文档

## 🌟 愿景与理念

SpineWorks 不仅仅是另一个 AI 编码助手。它是一个**完整的智能开发生态系统**，模仿人类团队的工作方式：拥有专业专家、深度分析、持续监控和自适应协作。

### 龙的哲学 🐉

像中国龙一样 - 智慧、力量和适应性的象征 - SpineWorks 体现了：

- **智慧**：通过智囊团系统进行深度分析思考
- **力量**：50+ 专业代理和谐协作
- **适应性**：为任何场景动态生成代理
- **远见**：持续监控和目标对齐
- **协作**：所有代理之间无缝通信

### 核心创新

**三层架构**：

1. **核心代理（预设）**：元协调器、代理工厂、文件分析器 - 始终可用
2. **场景协调器（动态）**：PM 代理、研究协调器、主编 - 根据任务类型生成
3. **专业工作者（动态）**：根据需求动态生成的任务特定代理，需用户确认

**SpineWorks 的与众不同之处**：

- **超越固定代理**：不限于 27+ 预设代理 - 为任何场景生成专业代理
- **用户确认流程**：系统提议代理团队 → 用户审查 → 用户定制 → 系统执行
- **文件上传能力**：上传文档、书籍、研究论文供 AI 分析
- **代理集群**：用于研究、写作和复杂分析的协作团队
- **持续监控**：智囊团代理监控执行并在偏差时发出警报

---


## 🧠 个人智囊团

智囊团是您的**个人顾问委员会** - 五个专业视角代理，在执行开始前从各个角度分析您的项目。

### 五个视角

#### 1. 🎯 目标聚焦代理

**角色**：清晰度专家

**功能**：
- 明确核心目标和成功标准
- 识别利益相关者需求和期望
- 定义可衡量的成功指标
- 在执行期间监控目标偏移

**示例分析**：
```
项目："构建任务管理应用"

目标聚焦分析：
✓ 核心目标：使团队能够高效协作完成任务
✓ 成功标准：
  - 用户可以在 < 3 次点击内创建/分配/完成任务
  - 所有设备实时更新
  - 99.9% 正常运行时间
✓ 利益相关者：最终用户、团队经理、移动开发者
✓ 关键指标：用户参与度、任务完成率、响应时间
```

**持续监控**：
- 订阅 `task_started`、`feature_added` 事件
- 如果新功能与核心目标不一致则发出警报
- 在范围蔓延时建议重新聚焦

#### 2. 🗺️ 路径规划代理

**角色**：战略家

**功能**：
- 设计具有明确里程碑的执行路线图
- 映射任务之间的依赖关系
- 估算时间线和资源需求
- 在执行期间跟踪里程碑进度

**示例分析**：
```
项目："构建任务管理应用"

路径规划分析：
✓ 里程碑 1：认证系统（3 天）
  - 用户注册/登录
  - JWT 令牌管理
  - 密码重置流程
  依赖：无

✓ 里程碑 2：任务 CRUD API（4 天）
  - 任务模型和数据库
  - REST API 端点
  - 授权逻辑
  依赖：M1（需要认证）

✓ 里程碑 3：实时更新（3 天）
  - WebSocket 集成
  - 事件广播
  - 客户端同步
  依赖：M2（任务必须存在）

✓ 里程碑 4：移动应用（5 天）
  - React Native 设置
  - UI 组件
  - API 集成
  依赖：M2、M3
```


#### 3. ⚠️ 风险预测代理

**角色**：守护者

**功能**：
- 识别技术、资源和业务风险
- 评估风险概率和影响
- 设计缓解策略
- 在执行期间监控风险实现

**示例分析**：
```
项目："构建任务管理应用"

风险预测分析：
⚠️ 高风险：实时同步复杂性
  - 概率：70%
  - 影响：可能延迟 M3 2-3 天
  - 缓解：使用成熟库（Socket.io），早期原型
  - 应急：如果 WebSocket 失败则回退到轮询

⚠️ 中等风险：移动应用平台差异
  - 概率：50%
  - 影响：iOS/Android 不一致
  - 缓解：使用 React Native Paper 实现一致的 UI
  - 应急：必要时使用平台特定代码

⚠️ 低风险：数据库可扩展性
  - 概率：20%
  - 影响：> 10K 用户时性能问题
  - 缓解：索引优化、缓存策略
  - 应急：必要时数据库分片
```

#### 4. 🔧 资源整合代理

**角色**：架构师

**功能**：
- 评估技术栈和工具
- 评估团队技能和差距
- 规划基础设施需求
- 在执行期间监控资源消耗

**示例分析**：
```
项目："构建任务管理应用"

资源整合分析：
✓ 后端技术栈：
  - 框架：FastAPI（异步、高性能）
  - 数据库：PostgreSQL（ACID 合规、JSON 支持）
  - 缓存：Redis（实时数据、会话管理）
  - 认证：JWT + bcrypt（行业标准）

✓ 前端技术栈：
  - 移动：React Native（跨平台、单一代码库）
  - 状态：Redux Toolkit（可预测的状态管理）
  - UI：React Native Paper（Material Design）

✓ 基础设施：
  - 托管：AWS（API 用 EC2，数据库用 RDS）
  - WebSocket：AWS API Gateway WebSocket
  - CDN：CloudFront（静态资源）
  - CI/CD：GitHub Actions

✓ 所需团队技能：
  - Python/FastAPI：✓ 可用
  - React Native：⚠️ 需要学习（2 天）
  - WebSocket：⚠️ 需要学习（1 天）
  - AWS：✓ 可用
```


#### 5. 🔄 优化迭代代理

**角色**：完美主义者

**功能**：
- 分析权衡和替代方案
- 识别优化机会
- 建议持续改进
- 监控代码质量和性能

**示例分析**：
```
项目："构建任务管理应用"

优化分析：
🔄 架构权衡：
  选项 A：单体 API
    优点：简单部署、更容易调试
    缺点：更难扩展单个组件
  
  选项 B：微服务
    优点：独立扩展、技术灵活性
    缺点：复杂部署、网络开销
  
  建议：从单体开始，稍后提取服务

🔄 数据库优化：
  - 在 user_id、task_id、created_at 上使用数据库索引
  - 为频繁读取实现查询结果缓存
  - 使用连接池（最多 20 个连接）

🔄 性能目标：
  - API 响应时间：< 200ms（p95）
  - WebSocket 延迟：< 50ms
  - 移动应用启动：< 2 秒

🔄 代码质量：
  - 测试覆盖率：> 80%
  - 代码复杂度：< 10 圈复杂度
  - 文档：所有公共 API 已文档化
```

---


## 🤖 组织代理集群

SpineWorks 包含 50+ 个专业代理，分为多个类别。系统根据您的项目需求动态选择合适的代理。

### 核心代理（始终激活）

#### 1. 秘书代理 - 协调者 🎯

**始终激活 | 中央枢纽**

**核心职责**：
- **用户交互**：终端界面、菜单系统、输入收集
- **进度跟踪**：监控所有代理、计算 ETA、发送更新
- **中断处理**：使用安全点策略处理用户中断
- **警报路由**：按严重性路由警报（严重/警告/信息）
- **上下文管理**：跟踪活动代理、任务、阻塞
- **回流管理**：处理质量问题和返工请求

**关键特性**：
- 使用安全点策略的中断处理（在安全时刻暂停）
- 每 30 分钟进度更新（可配置）
- 警报路由：严重警报暂停执行，警告记录
- 上下文感知：知道每个代理在做什么

#### 2. PM 代理 - 项目经理 📋

**始终激活 | 需求与规划**

**核心职责**：
- 需求分析和澄清
- 任务分解和优先级排序
- 里程碑规划和跟踪
- 进度控制和报告
- 必要时咨询智囊团

**能力**：
- 提出澄清问题以理解需求
- 将复杂项目分解为可管理的任务
- 创建详细的项目计划和时间线
- 监控进度并根据需要调整计划
- 咨询智囊团代理进行深度分析


#### 3. 编排决策器 - 团队构建者 🎭

**始终激活 | 动态代理选择**

**核心职责**：
- 从需求中提取项目配置文件
- 根据项目特征选择最优代理团队
- 自动解析代理依赖关系
- 向用户展示团队以供确认
- 管理代理生命周期

**选择算法**：
```
1. 分析需求卡片
   ├─→ 项目规模：微型/小型/中型/大型
   ├─→ 领域：后端/前端/数据/云
   └─→ 属性：安全/性能/合规

2. 按标准匹配代理
   ├─→ 必需代理（始终需要）
   ├─→ 领域匹配代理（后端 → 后端开发）
   ├─→ 属性匹配代理（安全 → 安全代理）
   └─→ 依赖解析（技术负责人 → 后端开发）

3. 向用户展示
   ├─→ 显示选定的团队
   ├─→ 允许定制（添加/删除）
   └─→ 确认并继续
```

### 执行代理（开发）

#### 4. 技术负责人代理 - 架构师 🏗️

**条件激活 | 架构与设计**

**激活时机**：具有后端、前端或复杂架构的项目

**核心职责**：
- 系统架构设计
- 技术栈选择
- 架构审查和验证
- 技术决策制定
- 设计模式推荐

#### 5. 后端开发代理 - 构建者 💻

**条件激活 | 后端实现**

**激活时机**：具有后端/API 需求的项目

**核心职责**：
- API 端点开发
- 数据库模式设计
- 业务逻辑实现
- 与外部服务集成
- 后端测试

**能力**：
- 使用适当的 HTTP 方法实现 RESTful API
- 设计规范化的数据库模式
- 编写清晰、可维护的业务逻辑
- 集成第三方 API（支付、电子邮件等）
- 编写单元和集成测试
- **可扩展**：可以为大型项目运行多个实例（Phase 4.1）


### 质量代理（QA 与安全）

#### 6. 代码审查代理 - 质量守护者 🔍

**条件激活 | 代码质量**

**激活时机**：质量优先项目或用户请求

**状态**：Phase 4.1（下一阶段）

**核心职责**：
- 代码质量分析
- 最佳实践执行
- 可维护性评估
- 重构建议
- 代码异味检测

#### 7. 安全代理 - 守护者 🛡️

**条件激活 | 安全分析**

**激活时机**：安全敏感项目（认证、支付、PII）

**状态**：Phase 4.1（下一阶段）

**核心职责**：
- 漏洞扫描
- 安全最佳实践执行
- 合规检查
- 依赖漏洞分析
- 敏感数据检测

**能力**：
- 扫描 OWASP Top 10 漏洞
- 检测硬编码的密钥和凭据
- 分析依赖项的已知漏洞
- 检查 SQL 注入、XSS、CSRF 风险
- 验证认证和授权逻辑

### 增强代理（可选）

#### 8. 合规代理 - 审计员 📜

**可选 | 监管合规**

**激活时机**：金融、医疗或需要合规的项目

**状态**：Phase 5（未来）

**能力**：
- GDPR 合规检查
- HIPAA 合规验证
- SOC2 审计准备
- 合规文档
- 审计跟踪生成

#### 9. 成本计算代理 - 经济学家 💰

**可选 | 成本管理**

**激活时机**：云项目或成本跟踪需求

**状态**：Phase 5（未来）

**能力**：
- 云资源成本估算
- 成本优化建议
- 预算跟踪和警报
- ROI 分析
- 按服务的成本分解


### 完整代理目录

**总计：50+ 代理**，涵盖所有类别：

| 类别 | 数量 | 示例 |
|------|------|------|
| **核心** | 3 | 秘书、PM、编排决策器 |
| **智囊团** | 5 | 目标聚焦、路径规划、风险预测、资源整合、优化 |
| **执行** | 15+ | 技术负责人、后端开发、前端开发、移动开发、数据开发、运维等 |
| **质量** | 10+ | 代码审查、安全、QA、性能测试、兼容性测试等 |
| **增强** | 15+ | 合规、成本计算、文档、国际化、监控等 |
| **动态** | ∞ | 根据特定场景按需生成 |

---

## 🎭 动态代理生成系统

SpineWorks 超越了固定代理 - 它可以**根据需求动态生成专业代理**，适用于任何场景。

### 三层架构

```
┌─────────────────────────────────────────────────────────────┐
│ 第 1 层：核心代理（预设 - 始终可用）                        │
├─────────────────────────────────────────────────────────────┤
│ • 元协调器：编排整个系统                                    │
│ • 代理工厂：动态生成新代理                                  │
│ • 文件分析器：处理上传的文档                                │
│ • 秘书代理：用户界面和协调                                  │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│ 第 2 层：场景协调器（动态 - 基于任务）                     │
├─────────────────────────────────────────────────────────────┤
│ 软件开发 → PM 代理                                          │
│ 研究分析 → 研究协调器                                       │
│ 内容创作 → 主编                                             │
│ 业务分析 → 业务分析师                                       │
│ 数据科学 → 数据科学负责人                                   │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│ 第 3 层：专业工作者（动态 - 按需）                         │
├─────────────────────────────────────────────────────────────┤
│ 根据特定任务需求生成                                        │
│ • 文献审查员（用于研究）                                    │
│ • 内容作者（用于写作）                                      │
│ • 数据分析师（用于分析）                                    │
│ • 领域专家（用于专业知识）                                  │
│ • ... 根据需要更多                                          │
└─────────────────────────────────────────────────────────────┘
```

### 用户确认流程

```
用户请求
    │
    ▼
元协调器分析任务类型
    │
    ▼
代理工厂提议团队
    │
    ├─→ 场景协调器：研究协调器
    ├─→ 工作者：文献审查员、数据分析师、报告撰写员
    └─→ 支持：文件分析器、引用管理器
    │
    ▼
向用户展示
    │
    ├─→ "我为您的研究任务推荐这些代理："
    ├─→ 显示代理描述和角色
    └─→ "您想添加或删除任何代理吗？"
    │
    ▼
用户定制
    │
    ├─→ 用户添加：领域专家（生物学）
    ├─→ 用户删除：报告撰写员（将手动编写）
    └─→ 用户确认团队
    │
    ▼
生成并执行
```

---


## 📂 文件上传与分析

SpineWorks 支持上传文档进行 AI 分析 - 非常适合分析书籍、研究论文、报告等。

### 支持的文件类型

- **文档**：PDF、DOCX、TXT、MD
- **电子表格**：XLSX、CSV
- **代码**：PY、JS、TS、JAVA 等
- **数据**：JSON、XML、YAML
- **图像**：PNG、JPG（OCR 支持）

### 上传工作流

```
用户上传文件
    │
    ▼
文件分析器代理处理文件
    │
    ├─→ 提取文本内容
    ├─→ 识别结构（章节、部分）
    ├─→ 提取元数据（作者、日期等）
    └─→ 创建可搜索索引
    │
    ▼
元协调器确定任务类型
    │
    ├─→ 书籍分析 → 主编 + 内容分析师
    ├─→ 研究论文 → 研究协调器 + 文献审查员
    ├─→ 代码审查 → 技术负责人 + 代码审查代理
    └─→ 数据分析 → 数据科学负责人 + 数据分析师
    │
    ▼
向用户提议代理团队
    │
    ▼
使用代理集群执行分析
```

### 示例：书籍分析

**任务**："分析这本关于软件架构的书"

**上传**：`clean-architecture.pdf`（400 页）

**工作流**：
```
🤝 秘书：文件已上传：clean-architecture.pdf（400 页）
🤝 秘书：文件分析器处理中...
🤝 秘书：✓ 提取了 15 章、87 节
🤝 秘书：✓ 识别的关键概念：SOLID、Clean Architecture、依赖规则

🤝 秘书：这似乎是一本关于软件架构的技术书籍。
🤝 秘书：我为分析推荐这个团队：

场景协调器：
✓ 技术书籍分析师（新）- 协调书籍分析

分析代理：
✓ 章节总结器（新）- 总结每一章
✓ 概念提取器（新）- 识别关键概念和模式
✓ 代码示例分析器（新）- 分析代码示例
✓ 实际应用代理（新）- 建议实际应用

您想添加或删除任何代理吗？（是/否）：否

🤝 秘书：✓ 使用 5 个代理开始分析...
🤝 秘书：[进度] 章节总结器：处理章节 1-5（33%）
🤝 秘书：[进度] 概念提取器：识别了 23 个关键概念
🤝 秘书：[进度] 代码示例分析器：分析了 15 个代码示例
🤝 秘书：✓ 分析完成！

交付物：
✓ 完整书籍摘要（5 页）
✓ 关键概念词汇表（23 个概念）
✓ 代码示例分析（15 个示例）
✓ 实际应用指南（10 个场景）
✓ 概念思维导图（可视化图表）
```

---


## 🔄 完整工作流示例

### 工作流 1：软件开发（智囊团模式）

```
用户："构建一个带支付集成的电商平台"
    │
    ▼
🤝 秘书：选择了智囊团模式
    │
    ▼
智囊团分析（5 个视角）
    │
    ├─→ 🎯 目标聚焦：B2C 平台、安全支付、可扩展
    ├─→ 🗺️ 路径规划：6 个里程碑、4 周时间线
    ├─→ ⚠️ 风险预测：支付安全、PCI 合规
    ├─→ 🔧 资源整合：React、FastAPI、Stripe、AWS
    └─→ 🔄 优化：微服务 vs 单体分析
    │
    ▼
生成需求卡片
    │
    ▼
编排决策器：提取项目配置文件
    │
    ├─→ 规模：中型
    ├─→ 领域：后端、前端、云
    └─→ 属性：安全敏感、高并发
    │
    ▼
提议代理团队
    │
    ├─→ 核心：秘书、PM、编排决策器
    ├─→ 智囊团：全部 5 个视角代理（监控）
    ├─→ 执行：技术负责人、后端开发、前端开发、运维
    └─→ 质量：安全代理（API 自动启用）
    │
    ▼
用户确认
    │
    ├─→ 用户添加：QA 代理、性能测试代理
    └─→ 用户确认：总共 13 个代理
    │
    ▼
执行管道
    │
    ├─→ PM 代理：分解需求
    ├─→ 技术负责人：设计架构
    ├─→ 后端开发：实现 API + 支付集成
    ├─→ 前端开发：构建 UI 组件
    ├─→ 安全代理：扫描漏洞
    ├─→ QA 代理：生成并运行测试
    ├─→ 性能测试：负载测试
    └─→ 运维代理：创建部署脚本
    │
    ▼
持续监控（智囊团）
    │
    ├─→ 目标聚焦：监控目标对齐
    ├─→ 风险预测：监视风险实现
    └─→ 资源整合：跟踪资源使用
    │
    ▼
交付物
    │
    ├─→ 完整源代码（后端 + 前端）
    ├─→ 数据库模式和迁移
    ├─→ Stripe 支付集成
    ├─→ 安全扫描报告
    ├─→ 测试套件（80%+ 覆盖率）
    ├─→ 性能测试结果
    ├─→ Docker 部署配置
    ├─→ CI/CD 管道（GitHub Actions）
    └─→ 完整文档
```

---


### 工作流 2：研究分析（直接模式）

```
用户："分析 AI 安全研究的最新趋势"
    │
    ▼
🤝 秘书：直接执行模式
    │
    ▼
元协调器：识别任务类型 → 研究
    │
    ▼
代理工厂：生成研究团队
    │
    ├─→ 场景协调器：研究协调器（新）
    ├─→ 工作者：文献审查员、趋势分析师（新）
    └─→ 支持：文件分析器、引用管理器（新）
    │
    ▼
用户确认
    │
    ├─→ 用户添加：领域专家（AI 安全）
    └─→ 用户确认：6 个代理（5 个动态生成）
    │
    ▼
研究协调器：规划研究工作流
    │
    ├─→ 阶段 1：文献搜索和收集
    ├─→ 阶段 2：论文分析和总结
    ├─→ 阶段 3：趋势识别
    └─→ 阶段 4：报告生成
    │
    ▼
执行
    │
    ├─→ 文献审查员：分析 50 篇论文
    ├─→ 趋势分析师：识别 5 个主要趋势
    ├─→ 领域专家：提供专业见解
    └─→ 引用管理器：构建引用网络
    │
    ▼
交付物
    │
    ├─→ 综合文献综述（20 页）
    ├─→ 带可视化的趋势分析报告
    ├─→ 关键发现和见解
    ├─→ 研究空白和未来方向
    └─→ 引用网络图
```

---


### 工作流 3：内容创作（代理集群）

```
用户："撰写一份关于云架构的综合指南（10,000 字）"
    │
    ▼
🤝 秘书：检测到大型写作项目
    │
    ▼
元协调器：识别任务类型 → 内容创作
    │
    ▼
代理工厂：生成写作团队
    │
    ├─→ 场景协调器：主编（新）
    ├─→ 作者：3x 内容作者（新）- 并行写作
    ├─→ 支持：大纲生成器、技术审查员（新）
    └─→ 质量：事实核查员、SEO 专家（新）
    │
    ▼
用户确认
    │
    ├─→ 用户添加：代码示例生成器、插图师
    └─→ 用户确认：10 个代理（代理集群）
    │
    ▼
主编：规划内容结构
    │
    ├─→ 第 1 章：云简介（作者 1）
    ├─→ 第 2 章：核心服务（作者 2）
    ├─→ 第 3 章：架构模式（作者 3）
    ├─→ 第 4 章：最佳实践（作者 1）
    └─→ 第 5 章：案例研究（作者 2）
    │
    ▼
并行执行（代理集群）
    │
    ├─→ 作者 1：第 1、4 章（3,000 字）
    ├─→ 作者 2：第 2、5 章（3,500 字）
    ├─→ 作者 3：第 3 章（3,500 字）
    ├─→ 代码示例生成器：20 个代码示例
    ├─→ 插图师：15 个图表
    └─→ 技术审查员：验证准确性
    │
    ▼
主编：整合和润色
    │
    ├─→ 合并所有章节
    ├─→ 确保一致的风格
    ├─→ 添加过渡
    └─→ 最终审查
    │
    ▼
质量检查
    │
    ├─→ 事实核查员：验证所有声明
    ├─→ SEO 专家：优化搜索
    └─→ 技术审查员：最终准确性检查
    │
    ▼
交付物
    │
    ├─→ 完整指南（10,000 字）
    ├─→ 20 个代码示例
    ├─→ 15 个架构图
    ├─→ SEO 优化内容
    └─→ 事实核查和审查
```

---


## 🚀 快速开始

### 安装

```bash
# 克隆仓库
git clone https://github.com/yourusername/spineworks.git
cd spineworks

# 创建虚拟环境
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 安装依赖
pip install -r requirements.txt

# 安装 SpineWorks
pip install -e .
```

### 配置

创建 `~/.spineworks/config.yaml`：

```yaml
# LLM 配置
llm:
  provider: "anthropic"  # 或 "openai", "google"
  model: "claude-3-5-sonnet-20241022"
  api_key: "your-api-key-here"
  temperature: 0.7
  max_tokens: 4096

# 默认入口模式
default_entry_mode: "ask"  # 选项：ask, think, direct

# 秘书设置
secretary:
  progress_update_interval: 1800  # 30 分钟
  interrupt_strategy: "safe_point"

# 动态代理生成
dynamic_agents:
  enabled: true
  user_confirmation_required: true
  max_agents_per_task: 20
```

### 基本用法

#### 选项 1：智囊团模式（推荐）

```bash
spineworks think "构建任务管理的 REST API"
```

#### 选项 2：直接执行

```bash
spineworks start --direct "创建 Python CLI 工具"
```

#### 选项 3：交互模式

```bash
spineworks
```

#### 选项 4：文件上传与分析

```bash
spineworks analyze --file research-paper.pdf
```

---


## 🌐 系统架构

### 高层架构

```
┌─────────────────────────────────────────────────────────────┐
│                      用户界面层                              │
│  CLI（Rich）| 交互式提示 | Web UI（Phase 6）               │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│                  秘书代理（协调器）                          │
│  中断处理 | 进度跟踪 | 上下文管理 | 警报路由                │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│                   代理消息总线                               │
│  发布/订阅 | 查询/响应 | 优先级队列 | 消息历史              │
└─────────────────────────────────────────────────────────────┘
              │                                    │
              ▼                                    ▼
┌──────────────────────────┐        ┌──────────────────────────┐
│   个人智囊团             │◄──────►│  组织代理                │
│   （分析模式）           │        │  （执行模式）            │
│                          │        │                          │
│  • 5 个视角代理          │        │  • PM 代理               │
│  • 持续监控              │        │  • 技术负责人            │
│  • 警报生成              │        │  • 开发代理              │
│  • 专业知识提供          │        │  • 运维代理              │
└──────────────────────────┘        └──────────────────────────┘
              │                                    │
              └────────────────┬───────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│              代理注册表与编排                                │
│  27+ 代理定义 | 项目配置文件提取 | 动态团队组建             │
└─────────────────────────────────────────────────────────────┘
              │
              ▼
┌─────────────────────────────────────────────────────────────┐
│                    基础设施层                                │
│  内存系统 | 日志系统 | 配置管理 | LLM 适配器               │
└─────────────────────────────────────────────────────────────┘
```

---

## 📊 性能指标

### 消息总线基准测试

| 指标 | 目标 | 实际 | 状态 |
|------|------|------|------|
| 消息发布延迟 | < 10ms | 0.40ms | ✅ 超越 |
| 消息传递延迟 | < 100ms | ~100ms | ✅ 达到 |
| 查询/响应往返 | < 500ms | 209ms | ✅ 超越 |
| 吞吐量 | > 1000 msg/min | 196,861 msg/min | ✅ 超越 |

### 测试覆盖

- **总测试数**：1430
- **通过率**：96.5%（1380 通过）
- **测试类型**：单元、基于属性、集成、性能、E2E
- **执行时间**：< 20 秒（核心测试）

---


## 🗺️ 开发路线图

### ✅ Phase 1：基础（已完成）
- 核心代理框架
- 基本编排
- CLI 界面
- 内存系统

### ✅ Phase 2：智囊团（已完成）
- 5 维度分析
- 需求卡片生成
- 对话管理
- 状态机

### ✅ Phase 3：增强分析（已完成）
- 视角代理实现
- 需求卡片存储
- 快速分析模式
- 模式选择器

### ✅ Phase 4.0：核心架构（已完成）
- ✅ 代理消息总线
- ✅ 代理注册表
- ✅ 编排决策器
- ✅ 常驻秘书
- ✅ 双向通信
- ✅ 持续监控
- ✅ 双入口 UX
- ✅ 文档与交付

### 📅 Phase 4.1：质量保证（计划中）
- 代码审查代理
- 安全代理
- QA 代理
- 性能测试代理
- 多实例支持

### 📅 Phase 5：增强（未来）
- 合规代理
- 成本计算器
- 文档自动化
- 国际化/本地化支持
- 监控代理
- **动态代理生成系统**
- **文件上传与分析**
- **代理集群协作**

### 📅 Phase 6：规模化与完善（未来）
- 分布式消息总线
- Web UI 仪表板
- 高级 NLP
- 语音输入
- 多用户支持

---


## 🎯 核心特性总结

### 个人智囊团 🧠
- **5 个视角代理**：目标聚焦、路径规划、风险预测、资源整合、优化迭代
- **深度分析**：在执行前从各个角度分析项目
- **持续监控**：在执行期间监控目标对齐和风险
- **专业咨询**：执行代理可以查询智囊团获取专业知识

### 组织代理集群 🤖
- **50+ 专业代理**：涵盖开发、质量、增强等所有方面
- **动态选择**：根据项目特征自动选择最优团队
- **用户确认**：系统提议团队，用户可以定制
- **可扩展**：某些代理支持多实例并行执行

### 秘书代理 👔
- **始终在线**：您与整个系统的单一联系点
- **进度跟踪**：实时监控所有代理和任务
- **中断处理**：安全点策略，不会丢失工作
- **警报路由**：按严重性智能路由警报

### 动态代理生成 🎭
- **三层架构**：核心代理 + 场景协调器 + 专业工作者
- **任意场景**：软件开发、研究分析、内容创作等
- **用户确认**：系统提议，用户定制，然后执行
- **无限可能**：可以为任何任务生成专业代理

### 文件上传与分析 📂
- **多种格式**：PDF、DOCX、代码、数据等
- **智能处理**：自动提取内容、结构和元数据
- **代理集群**：多个代理协作分析大型文档
- **丰富交付物**：摘要、分析、可视化等

---

## 🤝 贡献

我们欢迎贡献！请查看我们的[贡献指南](CONTRIBUTING.md)了解详情。

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

---

## 📞 联系方式

- **问题**：[GitHub Issues](https://github.com/yourusername/spineworks/issues)
- **讨论**：[GitHub Discussions](https://github.com/yourusername/spineworks/discussions)
- **邮箱**：your.email@example.com

---

<div align="center">

**🐉 由 Jackdaw 用 ❤️ 构建 🐉**

**像龙一样智慧、强大、适应性强 | Wise, Powerful, and Adaptive like the Dragon**

[⭐ 在 GitHub 上给我们星标](https://github.com/yourusername/spineworks) | [🐛 报告 Bug](https://github.com/yourusername/spineworks/issues) | [💡 请求功能](https://github.com/yourusername/spineworks/issues)

</div>
