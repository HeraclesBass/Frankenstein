# 🧪 Frankenstein

> "It's alive!" - A mad scientist's laboratory for experiments and knowledge assembly

**Broadcasting from:** Falkenstein, Germany 🇩🇪 | **Powered by:** Renewable Energy ⚡ | **Running on:** Hercules Platform

## What is Frankenstein?

Frankenstein is a dual-purpose repository that serves as:

1. **Experimental Laboratory** - A safe space for mad science coding experiments, proof-of-concepts, and testing new technologies
2. **Knowledge Repository** - An organized collection of scattered learnings, technical documentation, and personal notes assembled into one cohesive system

Like its namesake, this repository brings together disparate parts to create something greater than the sum of its components.

### ⚡ The Origin Story

Just as Mary Shelley's Dr. Frankenstein conducted his experiments in Germany, this modern laboratory operates from **Falkenstein, Germany** - home to some of Europe's most advanced data centers. The Hercules platform that powers this repository harnesses German engineering precision and renewable energy to bring experiments to life. With 125GB of RAM, 12 CPU threads, and 77+ days of uninterrupted uptime, this is where ideas become reality.

**The Laboratory Stats:**
- **Location:** Hetzner Data Center, Falkenstein, Germany
- **Compute:** Intel i7-8700 (6 cores, 12 threads)
- **Memory:** 125GB RAM
- **Storage:** 906GB RAID array
- **Containers:** 58 microservices running simultaneously
- **Agents:** 48 specialized AI agents ready to assist
- **Uptime:** 77+ days of continuous operation

### 🤖 The AI-Augmented Development Environment

This isn't just a server - it's a **production AI development platform** running real applications with autonomous agent orchestration:

**The Intelligence Stack:**
- **Claude Sonnet 4.5** - 200K token context window (can hold entire projects in memory)
- **Claude Code CLI v2.0.35** - Autonomous code execution and agent coordination
- **48 Specialized AI Agents** - Dynamic discovery across 15+ domains (security, backend, frontend, DevOps, etc.)
- **Agent Registry** - Living system that evolved from 44→51 agents with 113 version snapshots

**Active Production Infrastructure:**
- **58 Running Microservices** - Live applications serving traffic on herakles.dev
- **~10-12 Development Projects** - Picture Organizer, Holy Sh!t, Quits.ai, Sextant, Portfolio Platform, etc.
- **Full Observability Stack** - Prometheus + Grafana + exporters monitoring everything
- **Container Orchestration** - 64 Docker images, health checks, automated deployment
- **Multi-Database Architecture** - PostgreSQL, MongoDB, Redis, pgvector (AI embeddings)

**The 2025 Capability Shift:**
What used to require coordinating multiple specialists (backend dev, frontend dev, DevOps engineer, security analyst) can now be orchestrated through AI agents working in parallel. This became accessible to everyone when Claude Code CLI launched publicly in 2025.

**⚡ How It Works - The Lightning Laboratory:**

> **"The creature drew its first breath as lightning struck—not once, but ten times simultaneously."**

This isn't AI cosplaying as developers. This is **computational parallelism** at massive scale—the modern equivalent of Dr. Frankenstein's lightning storm, channeled through silicon and code.

**The Model Arsenal (Three Lightning Bolts):**
- **Claude Sonnet 4.5** (Primary Intelligence) - 77.2% on SWE-bench, 63 tokens/sec, 1.80s first response
- **Claude Haiku 4.5** (Rapid Executor) - 73.3% on SWE-bench, 2x faster, 1/3 cost—built for parallel swarms
- **Claude Opus 4.1** (The Validator) - Slow, expensive, catches 40% more bugs than automated tests

**Multi-Agent Orchestration Architecture:**
```
You (Mad Scientist) + Main Claude (Orchestrator)
              ↓
       Task Queue (Work Distribution)
              ↓
    ┌─────────┬─────────┬─────────┬───────────┐
    │Agent 1  │Agent 2  │Agent 3  │...Agent 10│
    │200K ctx │200K ctx │200K ctx │200K ctx   │
    │Sonnet4.5│Haiku4.5 │Haiku4.5 │Sonnet4.5  │
    └─────────┴─────────┴─────────┴───────────┘
         ↓         ↓         ↓         ↓
    Synthesis Layer (Merge conflicts, integrate)
         ↓
    Opus 4.1 Final Review (Quality gate)
```

**The Power of 10 Parallel Instances:**
- **2,000,000 tokens active** - 10 agents × 200K context each
- **630 tokens/second combined** - 10 Sonnet instances at 63 tok/s
- **Work chunking** - Can use 10 instances of the SAME agent to split massive tasks
- **Custom protocols** - Each agent gets specific instructions, checkpoints, handoff rules
- **Zero collisions** - Task queue ensures agents never step on each other

**Real Example - Refactoring a 50-file Authentication System:**
```
❌ Traditional (ChatGPT): 
   - One 128K context window
   - Manual copy/paste for each file
   - Time: 2-3 hours of back-and-forth
   
✅ Claude Code Orchestration:
   - 10 Haiku agents, 5 files each
   - Parallel execution with checkpoints
   - 1 Sonnet synthesis agent merges results
   - 1 Opus validator catches edge cases
   - Time: 18 minutes end-to-end
   - Cost: $0.40 (vs $12 in developer time)
```

**The Technical Edge:**
- **Beats GPT-5 on coding:** 77.2% vs 74.5% on SWE-bench Verified
- **Haiku swarm economics:** 1/3 cost of Sonnet, runs parallel for massive tasks
- **Opus quality gate:** Catches logic errors, async bugs, missing edge cases
- **Autonomous handoffs:** Agents pass work through checkpoints without human intervention

Read the deep dive: [`docs/research/20251107-ai-augmented-development-infrastructure.md`](/docs/research/20251107-ai-augmented-development-infrastructure.md)

---

## 📁 Repository Structure

```
Frankenstein/
├── experiments/          # Mad science coding experiments
│   ├── prototypes/      # Working prototypes and MVPs
│   ├── poc/             # Proof-of-concept implementations
│   └── sandbox/         # Quick tests and throwaway code
│
├── docs/                # Knowledge base and documentation
│   ├── guides/          # How-to guides and tutorials
│   ├── notes/           # Personal notes and learnings
│   └── research/        # Research findings and explorations
│
└── templates/           # Reusable templates for experiments
```

---

## 🔬 Experiments Philosophy

**Guidelines for the laboratory:**

- **Fail Fast, Learn Faster** - Experiments are meant to break things
- **Document the Journey** - Record what worked, what didn't, and why
- **No Judgment Zone** - All ideas are welcome, no matter how wild
- **Keep It Isolated** - Each experiment should be self-contained
- **Version Everything** - Git tracks our mad science progress

**Experiment Naming Convention:**
- `YYYYMMDD-experiment-name` - Date prefix for chronological tracking
- Example: `20251107-llm-streaming-poc`

---

## 📚 Documentation Philosophy

**Knowledge Assembly Principles:**

- **Capture Everything** - If you learned it, document it
- **Link Liberally** - Connect related concepts and experiments
- **Keep It Practical** - Focus on actionable insights
- **Evolve Continuously** - Update as understanding grows
- **Make It Searchable** - Use clear titles and keywords

---

## 🚀 Quick Start

### Starting a New Experiment

1. Choose the appropriate directory (`prototypes/`, `poc/`, or `sandbox/`)
2. Create a dated directory: `mkdir experiments/poc/20251107-my-experiment`
3. Add a README.md explaining the experiment's goal
4. Code away!
5. Document results in the experiment's README

### Adding Documentation

1. Choose the category (`guides/`, `notes/`, or `research/`)
2. Create a markdown file with a descriptive name
3. Follow the documentation template (see `templates/doc-template.md`)
4. Link to related experiments or other docs

---

## 🧬 Experiment Categories

### Prototypes
Full-featured implementations that could become real projects. These should be relatively polished and functional.

### POC (Proof of Concept)
Quick implementations to test if an idea is feasible. Focus on core functionality only.

### Sandbox
Throwaway code for learning and testing. No quality expectations - just exploration.

---

## 📖 Documentation Categories

### Guides
Step-by-step tutorials and how-to documentation. Practical and actionable.

### Notes
Personal learnings, insights, and observations. Stream-of-consciousness welcome.

### Research
Deep dives into technologies, patterns, or concepts. More structured analysis.

---

## 🔗 Integration with Main Projects

Successful experiments may graduate to:
- Production projects in the Hercules platform
- Standalone repositories
- Integration into existing services

Document the graduation path in the experiment's README.

---

## 🛠️ Tools & Technologies

This is a polyglot playground. Any technology is welcome:
- Languages: Python, JavaScript/Node.js, Go, Rust, etc.
- Frameworks: Whatever fits the experiment
- Databases: PostgreSQL, MongoDB, Redis, SQLite, etc.
- Tools: Docker, APIs, CLIs, notebooks, etc.

---

## 📊 Tracking Progress

Use GitHub Issues for:
- Experiment ideas to try
- Documentation topics to write
- Questions to research
- Connections to make between concepts

Use GitHub Projects for:
- Organizing related experiments
- Tracking learning goals
- Planning documentation sprints

---

## 🤝 Contributing (to yourself)

Some guidelines for future you:
- Always commit with descriptive messages
- Tag experiments with relevant labels
- Cross-reference related work
- Don't delete failed experiments - they're learning opportunities
- Review and refactor documentation regularly

---

## 📜 License

This is a personal repository. Do whatever you want with it.

---

## 🧠 Remember

> "Learn from the creations of others, but never stop creating your own."

Frankenstein is your laboratory. Experiment boldly, document thoroughly, and never stop learning.

**Last Updated:** 2025-11-07
