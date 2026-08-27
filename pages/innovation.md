## [Shervin's Portfolio](https://shervinkhazaeli.github.io) / Technical Innovation

Designing and shipping production GenAI and agentic systems across the full stack — from RAG pipelines and LLM-as-judge evaluation to multi-agent orchestration. Pioneered novel validation methodologies including the tri-agent dialectic framework and Evaluation-Driven Development (EDD), advancing both the reliability and the architectural range of AI systems in production.

**Production GenAI Applications:**
- **RAG Knowledge Retrieval** — retrieval-augmented system for structured internal decision support, grounded strictly in retrieved content
- **AI PR Review Agent** — autonomous code analysis agent reviewing pull requests and generating structured remediation, compressing review cycles from days to hours
- **Competitive Intelligence Platform** — multi-agent system combining web retrieval, tool use, and structured LLM outputs for automated market analysis

**Agentic Architecture Patterns:**
- **Prompt Chaining** — water quality analysis pipeline
- **Parallelization** — treatment plant monitoring across concurrent agents
- **Orchestrator-Worker** — drought management with dynamic task dispatch
- **Evaluator-Optimizer** — treatment process optimization with feedback loops

**Validation & Evaluation Frameworks:**
- **Tri-Agent Dialectic** — prosecutor / defender / adjudicator architecture for ML feature validation and data-leakage detection using adversarial prompting and structured output contracts
- **Evaluation-Driven Development (EDD)** — every agent shipped with a weighted eval rubric, labeled reference dataset (30%+ adversarial cases), and an LLM-as-judge runner gating readiness
- **Multi-Provider LLM Integration** — Anthropic Claude, Google Gemini, OpenAI across production systems

**Development Methodology:**
- **SEAL 6** — collaborative knowledge-sharing platform shaping the agentic AI product roadmap
- **AI-Assisted Development** — integrated AI agents into the development workflow; achieved Google MLOps maturity (experimentation-operations symmetry)

---

### Independent Projects

Self-directed projects built to explore agent architectures, LLM providers, and modern AI stacks.

**AI Governance & Readiness Assessment Pipeline** — *Prototype*

A 5-node sequential multi-agent pipeline that turns a conversational intake into a cited, phased AI-governance roadmap. One agent is deliberately adversarial — independently cross-checking the plan against a regulatory corpus before a report ships. Provider-agnostic LLM abstraction with model-per-node routing and retry/circuit-breaker resilience. Includes programmatic branded PDF report generation and bilingual (EN/FR) delivery.

*Stack: Node.js/Express · PostgreSQL (Neon) · Render*

**Vertical-Agnostic AI Concierge Platform** — *Prototype*

NFC/QR-triggered retrieval-augmented conversation scoped to the user's physical context — no app download required. Single-agent with strict grounding (answers only retrieved content), architected vertical-agnostic so only the system prompt, landing-page skin, and knowledge base change per deployment. Includes a B2B operator analytics dashboard and responsible-AI guardrails (prompt-injection-hardened, audit-ready session logs).

*Stack: Next.js 15 · Supabase (pgvector) · Anthropic API (Claude Sonnet) · Vercel*

**Graph-Intelligence Agentic AI Platform & Visualization Demo** — *Prototype (companion pieces)*

Five domain-specialist agents (network health, work orders, risk prioritization, capital planning, leak detection) plus an orchestrator that decomposes compound questions, dispatches specialists in parallel, and synthesizes a cited answer. Built under EDD: every agent shipped with a weighted eval rubric, adversarial test cases, and an LLM-as-judge runner gating readiness. The companion visualization demo adds a force-directed graph with four dynamic clustering modes and a per-asset AI risk-scoring endpoint reading full graph context.

*Stack: Neo4j · Supabase · React/Vite · Express.js · Python FastAPI · Google Gemini (via ADK) · Render + Vercel*

**Spec-Driven Agentic Development Framework** — *In Development · Personal tooling, intended for open-source release*

A reusable engineering harness for AI-assisted software development — a spec-driven pipeline (work-breakdown → spec + test stubs → quality gate → implementation → adversarial review → cross-spec compatibility check). Five Claude Code skills implement the pipeline stages, including parallel adversarial post-implementation review and drift detection that diffs the living spec against the actual codebase using a compiled knowledge graph. Twelve technology-specific engineering standards playbooks ensure implementing agents produce consistent, convention-compliant code regardless of stack.

*Stack: Claude Code · Internal tooling*
