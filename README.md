```
╔═══════════════════════════════════════════════════════════════════╗
║                      KARUN REDDY K (KK)                          ║
║            Senior Full-Stack Engineer | AI/LLM Expert            ║
║                  14+ Years | React • Next.js • Node              ║
╚═══════════════════════════════════════════════════════════════════╝
```

---

## 👋 Welcome

I'm a **full-stack engineer** obsessed with building scalable, high-performance web applications. My expertise spans modern React/Next.js architectures, LLM orchestration, and creating thoughtful user experiences that just *work*.

Currently focused on **AI-powered workflows** and **real-time streaming architectures** — bringing intelligent features to production without the complexity.

---

## 🎯 What I Do

| Craft | Expertise |
|-------|-----------|
| **Frontend Mastery** | React 19, Next.js 16+, TypeScript, Tailwind CSS, Accessibility (WCAG) |
| **AI Integration** | LLM Orchestration (Claude, Groq, OpenAI), MCP Tool Calling, Agent Loops |
| **Real-Time Systems** | Server-Sent Events (SSE), Streaming APIs, Live Data Pipelines |
| **Backend & Data** | Node.js, Express, API Design, REST/GraphQL, Firebase, AWS |
| **Quality First** | Jest, React Testing Library, Type Safety, Performance Optimization |

---

## ⭐ Flagship Project: Incident Intelligence Platform

### 🚀 AI-Powered Incident Triage with Real-Time Agent Orchestration

This is my **showcase project** demonstrating production-grade LLM integration, multi-server orchestration, and real-time streaming architectures.

```
═══════════════════════════════════════════════════════════════════
                    WHAT IT DOES
═══════════════════════════════════════════════════════════════════

User describes incident → AI gathers metrics → Analyzes deployments
                    ↓
              Correlates data → Identifies root cause
                    ↓
    Recommends actions with evidence & confidence scores
```

### 🛠️ Technology Stack

```
🔧 Frontend Architecture
├── Next.js 16 App Router
├── React 19 with TypeScript
├── Tailwind CSS styling
├── Server-Sent Events (SSE) real-time streaming
└── RBAC-aware UI (viewer/developer/admin roles)

🤖 AI & LLM Orchestration
├── Groq LLM (llama-3.3-70b via OpenAI API)
├── Model Context Protocol (MCP) - multi-server coordination
├── Agentic loops with tool calling
├── Structured JSON output extraction
└── Prompt engineering for complex reasoning

🔌 Backend Infrastructure
├── Next.js API Routes (Node.js runtime)
├── MCP servers spawned as subprocesses
├── Real-time event streaming to browser
├── RBAC enforcement (viewer/developer/admin)
└── Audit logging for compliance

📊 Data & Tools
├── Metrics MCP Server (latency, error rates, service health)
├── Engineering MCP Server (deployments, PRs, incidents)
├── Mock data (fully self-contained, no external APIs)
└── Structured audit trail (JSON logging)
```

### 🎯 Key Features That Show My Skills

#### 1. **Real-Time UI with Streaming**
- Server-Sent Events (SSE) for live tool-call visibility
- React state management for incoming events
- Thinking messages → tool execution → results displayed live
- Timeline component showing investigation progression
- Performance optimized for smooth updates

#### 2. **LLM Agent Orchestration**
- Agentic loop: LLM decides which tools to call and when
- Multi-turn conversation with context preservation
- Tool routing to appropriate MCP servers
- Error handling and fallback strategies
- Structured output parsing from LLM responses

#### 3. **Multi-Server Tool Coordination (MCP)**
- Metrics MCP Server: `get_latency()`, `get_error_rate()`, `get_service_metrics()`
- Engineering MCP Server: `get_recent_deployments()`, `get_recent_prs()`, `get_incident_ticket()`
- JSON-RPC communication over stdio
- Clean separation of concerns
- Easy to extend with new tool servers

#### 4. **Security & RBAC**
- Role-based access control: viewer, developer, admin
- Permission matrix enforcement
- Audit logging of all investigations
- Sensitive data excluded from commits
- Demo-ready without exposing internals

#### 5. **Production Patterns**
- Type-safe end-to-end (TypeScript everywhere)
- Proper error handling and user feedback
- Loading states and skeleton screens
- Accessibility considerations (WCAG)
- Clean component architecture

### 💡 Why This Project Matters

This isn't a toy demo — it demonstrates **real-world patterns**:

✅ How to integrate LLMs into production applications  
✅ Building responsive UIs for long-running agents  
✅ Coordinating multiple AI tools (MCP servers)  
✅ Streaming data from server to client efficiently  
✅ RBAC + audit logging for enterprise compliance  
✅ Structured outputs from unstructured LLM responses  
✅ Type safety across the entire stack  

### 🔗 Links

**Repository:** [github.com/carunreddy05/incident-intelligence-platform](https://github.com/carunreddy05/incident-intelligence-platform)

**Key Files to Review:**
- [`src/lib/agent.ts`](https://github.com/carunreddy05/incident-intelligence-platform/blob/main/src/lib/agent.ts) — Agentic loop orchestration
- [`src/app/api/investigate/route.ts`](https://github.com/carunreddy05/incident-intelligence-platform/blob/main/src/app/api/investigate/route.ts) — SSE streaming endpoint
- [`src/app/incident/page.tsx`](https://github.com/carunreddy05/incident-intelligence-platform/blob/main/src/app/incident/page.tsx) — Real-time UI with event handling
- [`mcp-servers/metrics/index.ts`](https://github.com/carunreddy05/incident-intelligence-platform/tree/main/mcp-servers) — Tool definitions

**Read the Full Story:** Check the [README](https://github.com/carunreddy05/incident-intelligence-platform#-architecture) for architecture deep-dives and design tradeoffs.

---

## 💼 Other Notable Projects

### 💪 Gym Entry Tracker
**High-Performance Workout Tracking with Accessibility-First Design**

> *Mobile-first responsive app, Firebase integration, WCAG compliant*

**Highlights:**
- 📱 Mobile-first responsive design
- 🗓️ Calendar-based workout views
- 🔒 Firebase auth + Firestore persistence
- ⚡ Performance-optimized for mobile networks
- ♿ WCAG accessibility best practices

**Live:** [gymentrytracker.web.app](https://gymentrytracker.web.app) • **Code:** [GitHub](https://github.com/carunreddy05/workout-tracker)

---

### 🔐 Smart Vault
**Secure Data Management Platform**

**Live:** [asksmartvault.web.app](https://asksmartvault.web.app) • **Code:** [GitHub](https://github.com/carunreddy05)

---

## 🛠️ Tech Toolbox

### Frontend Fundamentals
<table>
<tr>
<td align="center" width="80px">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40" />
<br>React 19
</td>
<td align="center" width="80px">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="40" />
<br>Next.js
</td>
<td align="center" width="80px">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" />
<br>TypeScript
</td>
<td align="center" width="80px">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg" width="40" />
<br>Tailwind
</td>
</tr>
</table>

### State & Data
<table>
<tr>
<td align="center" width="80px">
Redux
</td>
<td align="center" width="80px">
Zustand
</td>
<td align="center" width="80px">
React Query
</td>
<td align="center" width="80px">
GraphQL
</td>
</tr>
</table>

### AI & LLM Expertise
<table>
<tr>
<td align="center" width="80px">
Claude
</td>
<td align="center" width="80px">
Groq
</td>
<td align="center" width="80px">
OpenAI
</td>
<td align="center" width="80px">
MCP
</td>
</tr>
</table>

### Backend & Cloud
<table>
<tr>
<td align="center" width="80px">
Node.js
</td>
<td align="center" width="80px">
Express
</td>
<td align="center" width="80px">
Firebase
</td>
<td align="center" width="80px">
AWS
</td>
</tr>
</table>

### Quality & Testing
<table>
<tr>
<td align="center" width="80px">
Jest
</td>
<td align="center" width="80px">
React Testing Library
</td>
<td align="center" width="80px">
Docker
</td>
<td align="center" width="80px">
Git
</td>
</tr>
</table>

---

## 🎓 Engineering Philosophy

> **Build with intent. Ship with confidence.**

```
├─ 🎯 AI-Ready Architecture
│  └─ Design systems that integrate seamlessly with LLMs
│
├─ ⚡ Real-Time First  
│  └─ Leverage streaming & event-driven patterns
│
├─ 📖 Simple Code
│  └─ Readable > Clever
│
├─ ♿ Accessibility & Performance
│  └─ Not optional, not later — now
│
├─ 🤝 Strong Contracts
│  └─ Type-safe APIs (LLM + backend)
│
└─ 🎨 Thoughtful UX
   └─ User needs drive decisions
```

---

## 🔮 Currently Exploring

| Area | Focus |
|------|-------|
| 🤖 **LLM Patterns** | Multi-turn conversations, RAG, Agent safety & optimization |
| 🛠️ **Advanced Prompting** | Structured outputs, Chain-of-thought reasoning, Few-shot learning |
| 📡 **MCP Ecosystems** | Building scalable tool networks, Producer-consumer patterns |
| ⚛️ **React Innovations** | Server Components, Streaming, Advanced Suspense patterns |
| 📊 **Performance** | Core Web Vitals, Profiling, Real-world optimization |
| 🔐 **AI Safety** | Guardrails, Token budgets, Agent circuit breakers |

---

## 📞 Let's Connect

<table>
<tr>
<td align="center">
<strong>GitHub</strong><br>
<a href="https://github.com/carunreddy05">
<img src="https://img.shields.io/badge/carunreddy05-181717?style=flat-square&logo=github" alt="GitHub" />
</a>
</td>
<td align="center">
<strong>Featured Project</strong><br>
<a href="https://github.com/carunreddy05/incident-intelligence-platform">
<img src="https://img.shields.io/badge/Incident%20Platform-Live%20Repo-blue?style=flat-square" alt="Incident Platform" />
</a>
</td>
<td align="center">
<strong>LinkedIn</strong><br>
<a href="https://www.linkedin.com/in/karun-katepally-74a7b345/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin" alt="LinkedIn" />
</a>
</td>
</tr>
</table>

---

## 📊 A Peek Into My Work

```
Frontend Architecture
├── Component Design    → Reusable, composable, type-safe
├── State Management    → Redux, Zustand, React Query patterns
├── Performance         → Code splitting, lazy loading, memoization
└── Accessibility       → WCAG compliant, screen-reader optimized

AI Integration
├── LLM Orchestration   → Multi-turn agent loops, tool calling
├── Streaming          → Real-time completions, SSE pipelines  
├── Structured Output  → JSON schema validation, result extraction
└── Production Safety  → Token budgets, circuit breakers, monitoring

Full-Stack Delivery
├── API Design         → Type-safe contracts (REST/GraphQL)
├── Database           → Firebase, SQL, proper schema design
├── Deployment         → Docker, AWS, Firebase hosting
└── Monitoring         → Logging, error tracking, performance metrics
```

---

## 🚀 Ready to Build Something Great?

I'm passionate about solving complex problems with **simple, elegant solutions**. Whether it's building AI-powered features, optimizing performance, or architecting next-gen systems — let's collaborate.

<div align="center">

**[View My Work](https://github.com/carunreddy05) • [Explore Incident Platform](https://github.com/carunreddy05/incident-intelligence-platform) • [Get In Touch](#-lets-connect)**

*Making the web faster, smarter, and more accessible — one commit at a time.* ✨

</div>

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=carunreddy05&style=flat-square&color=blue)

</div>
