# Hercules Platform Capabilities & System Inventory

**Category:** Note  
**Date Created:** 2025-11-07  
**Last Updated:** 2025-11-07  
**Tags:** #system #infrastructure #capabilities #inventory

---

## Overview

Comprehensive snapshot of the Hercules development platform's hardware, software, services, and capabilities as of November 2025.

> **⚡ The Lore:** This server lives in Falkenstein, Germany - home to some of Europe's most efficient data centers. Like Dr. Frankenstein's laboratory, our modern "creation chamber" harnesses German engineering precision to bring experiments to life. The Hercules platform runs on renewable energy in a state-of-the-art facility, balancing raw computing power with environmental responsibility.

---

## Hardware Specifications

### Compute
- **CPU:** Intel Core i7-8700 @ 3.20GHz
  - 6 cores, 12 threads (hyperthreading enabled)
  - Base: 3.20GHz | Turbo: Up to 4.60GHz
  - Architecture: x86_64
- **Current Load:** ~9.5 average (moderate-high utilization ~80%)
- **Uptime:** 77 days, 8 hours (rock solid stability)

### Memory
- **Total RAM:** 125 GB
- **Available:** 98 GB (78% free)
- **Used:** 27 GB
- **Swap:** 31 GB total (11 GB used, 20 GB free)
- **Status:** Excellent headroom for experiments

### Storage
- **Filesystem:** /dev/md2 (RAID array)
- **Capacity:** 906 GB
- **Used:** 433 GB (51%)
- **Available:** 427 GB
- **Status:** Healthy, plenty of space

### Operating System
- **OS:** Debian GNU/Linux (Bookworm)
- **Kernel:** 6.1.0-37-amd64
- **Type:** SMP PREEMPT_DYNAMIC

### Physical Location
- **Data Center:** Falkenstein, Germany 🇩🇪
- **Region:** Europe (EU)
- **Provider:** Hetzner (renowned for German engineering efficiency)
- **Energy:** Renewable energy-powered facility
- **Compliance:** GDPR-compliant infrastructure
- **Latency Considerations:**
  - Excellent for European users (~10-30ms)
  - Good for US East Coast (~80-100ms)
  - Moderate for US West Coast (~150-170ms)
  - Higher for Asia-Pacific (~200-300ms)

**Why Falkenstein?**
- Superior price-to-performance ratio
- Robust network infrastructure (multiple Tier 1 uplinks)
- Low latency to major European cities
- Strong data protection regulations
- Green energy commitment
- Excellent uptime SLAs (as evidenced by our 77-day streak)

---

## Software Stack

### Development Languages & Runtimes
- **Node.js:** Installed at `/usr/bin/node`
- **Python:** 3.11.2 (`/usr/bin/python3`)
- **Go:** 1.21.0 (`/usr/local/go/bin/go`)
- **Rust:** Installed (command available)

### Core Infrastructure
- **Docker:** 20.10.24+dfsg1
  - 58 running containers
  - 78 images available
  - Orchestrating entire platform
- **Git:** Available for version control
- **Nginx:** External (reverse proxy for services)
- **GitHub CLI:** Authenticated and configured

### MCP (Model Context Protocol) Integrations
Connected external services via MCP servers:
- **Gmail** - Email operations (`@gongrzhe/server-gmail-autoauth-mcp`)
- **GitHub** - Repository management (SSE)
- **Sentry** - Error tracking (HTTP)
- **Socket** - Dependency security scoring (HTTP)
- **Hugging Face** - ML models, datasets, papers (HTTP)
- **Linear** - Issue tracking (SSE)
- **Vercel** - Deployment platform (HTTP)

---

## Service Portfolio

### Active Docker Containers (58 running)

**Portfolio Apps (8091-8099 range):**
- **8091** - WiFi Designer (`wifi.herakles.dev`)
- **8092** - Hercules Viz - Flask visualization (`viz.herakles.dev`)
- **8093** - H1 Expert Showcase (`h1.herakles.dev`)
- **8094** - Holy Sh!t - Satirical wellness app (`spicy.herakles.dev`, `holy.herakles.dev`)
- **8095** - Agents Manifest - Next.js (`agents.herakles.dev`)
- **8097** - Moody Time Machine (`moodytimemachine.herakles.dev`)
- **8098** - Keymakers Console (`keymakers.herakles.dev`)

**Development Services:**
- **8081** - HAL Frontend (healthy)
- **8102** - Sextant WiFi Nav Dev (healthy)
- **8104** - Medical Evidence App (healthy)
- **8107** - Portfolio Command Center (healthy)
- **8115/5173** - Quits.ai (healthy, dual ports)
- **8197/5274** - Quits.ai Dev (healthy, dual ports)

**Observability Stack:**
- **3000** - Grafana (Poop Tracker)
- **9091** - Prometheus
- **9100** - Node Exporter
- **9124** - Redis Exporter (Platform)
- **9126** - Redis Exporter (Picture Dev)
- **9216** - MongoDB Exporter
- **Nginx Exporter** - Running

**Infrastructure:**
- **9200** - Container Control API (healthy)

### Health Status
- **Healthy Containers:** Majority showing (healthy) status
- **Monitoring Coverage:** Comprehensive observability
- **Uptime:** All core services stable

---

## Agent Ecosystem

### Statistics
- **Total Agents:** 51
- **Active Agents:** 48
- **Deprecated:** 3
- **Platform:** Hercules v1.0
- **Last Updated:** 2025-11-06

### Agent Categories & Capabilities

**Development & Architecture (13 agents):**
- `general-purpose` - Research & multi-step tasks
- `frontend-specialist` - React/Next.js/Vue
- `backend-architect` - API design & server architecture
- `database-engineer` - PostgreSQL, MongoDB, Redis
- `mobile-dev-expert` - Mobile development
- `App-Design` - UI/UX design
- `ci-cd-architect` - Deployment automation
- `testing-engineer` - Unit/integration/E2E tests
- `performance-optimizer` - Performance tuning
- `refactoring-consultant` - Technical debt & modernization
- `migration-strategist` - Architecture evolution
- `real-time-engineer` - WebSockets, SSE, pub/sub
- `app-deployment-manager` - Deployment orchestration

**Security (6 agents):**
- `security-engineer` - OWASP Top 10, rate limiting
- `H1-Agent` - HackerOne program management
- `h1-hunter-agent` - Vulnerability discovery
- `h1-recon-agent` - Target reconnaissance
- `h1-validator-agent` - Finding validation
- `h1-strategy-advisor` - Bug bounty strategy
- `h1-reporter-agent` - Professional report creation
- `re-master-agent` - Reverse engineering (5-level framework)
- `data-privacy-engineer` - GDPR, encryption, compliance

**AI & Integration (4 agents):**
- `ai-integration-specialist` - LLM APIs, RAG, embeddings
- `AI-Engineer` - Career strategy & skill development
- `MCP-Expert` - MCP architecture & troubleshooting
- `Excel-AI` - Financial modeling & data ops

**Platform Management (10 agents):**
- `micro-manager` - 44-service Hercules orchestration
- `system-apps-manager` - Service diagnostics & deployment
- `container-manager` - Docker container control API
- `monitoring-specialist` - Logging, metrics, alerting
- `nginx-manager` - Nginx site configuration
- `meta-agent` - Agent ecosystem management
- `agent-architect` - New agent creation
- `agent-optimizer` - Agent ecosystem optimization
- `skills-manager` - Claude Code skills lifecycle
- `claude-code-config` - Settings & customization

**Project-Specific (9 agents):**
- `portfolio-platform-manager` - Portfolio platform at `/home/hercules/portfolio-platform/`
- `photo-manager` - Picture Organizer app context
- `album-pm` - Picture Organizer project management
- `holy-shit-dev` - Holy Sh!t app specialist
- `hestias-hearth-dev` - Couples calendar app
- `sextant-dev-specialist` - Sextant WiFi nav app
- `quits-builder` - Behavioral intervention system
- `mold-manager` - Legal case package builder
- `Reality-Check` - Life decisions validation

**Specialized Tools (6 agents):**
- `code-reviewer` - Code review automation
- `A-Z-Prompt` - Prompt engineering specialist
- `Prompt-Refinement` - Chain of Reasoning optimization
- `Salary-Battle` - Salary negotiation
- `technical-pm` - Technical project management
- `recall-agent` - Context recall & memory

---

## Key System Locations

### Configuration & Registry
- **Agent Registry:** `~/.agent-registry/agents.json`
- **PORT_REGISTRY:** `/home/hercules/system-apps-config/PORT_REGISTRY.json`
- **SITE_REGISTRY:** `/home/hercules/system-apps-config/SITE_REGISTRY.json` (when deployed)
- **MCP Config:** `~/.config/.mcp.json`
- **CLAUDE.md:** `/home/hercules/CLAUDE.md`

### Management Scripts
- **Deploy:** `/home/hercules/deploy.sh`
- **Secrets Manager:** `/home/hercules/scripts/secrets-manager.sh`
- **Observability CLI:** `/home/hercules/scripts/observability-cli/`
  - `observability-coverage.sh` - Coverage analysis
  - `observability-status.sh` - System status
  - `query-logs.sh` - Log querying
  - `check-metrics.sh` - Metrics checking

### Project Directories
- **Portfolio Platform:** `/home/hercules/portfolio-platform/`
- **Claude Configs:** `/home/hercules/claude-configs/`
- **Claude History:** `/home/hercules/claude-history-explorer/`
- **Container Control:** `/home/hercules/container-control-api/`
- **Agent Registry:** `/home/hercules/.agent-registry/`
- **Frankenstein Lab:** `/home/hercules/Frankenstein/` (this repo!)

---

## Observability & Monitoring

### Monitoring Stack Components
- **Grafana** - Visualization dashboards (port 3000)
- **Prometheus** - Metrics collection (port 9091)
- **Exporters:**
  - Node Exporter - System metrics
  - Redis Exporters - Redis monitoring (2 instances)
  - MongoDB Exporter - Database monitoring
  - Nginx Exporter - Web server metrics

### Observability Tools
- **Coverage Analysis** - Track instrumentation status
- **Log Querying** - Centralized log search
- **Metrics Checking** - Service health validation
- **Health Monitoring** - Container status tracking

---

## Network & Domains

### Subdomains (herakles.dev)
Active subdomains serving portfolio applications:
- `wifi.herakles.dev` - WiFi Designer
- `viz.herakles.dev` - Hercules Visualization
- `h1.herakles.dev` - H1 Expert Showcase
- `spicy.herakles.dev` / `holy.herakles.dev` - Holy Sh!t app
- `agents.herakles.dev` - Agents Manifest
- `moodytimemachine.herakles.dev` - Moody Time Machine
- `keymakers.herakles.dev` - Keymakers Console

### Port Allocation Strategy
- **8080-8090:** System/infrastructure services
- **8091-8099:** Portfolio applications
- **8100+:** Development & experimental services
- **9000+:** Monitoring & metrics exporters

---

## Development Capabilities

### What We Can Build
1. **Full-Stack Web Applications**
   - Frontend: React, Next.js, Vue
   - Backend: Node.js, Python (Flask), Go
   - Databases: PostgreSQL, MongoDB, Redis, SQLite

2. **Real-Time Systems**
   - WebSockets, Server-Sent Events
   - Pub/Sub patterns, live updates
   - Collaborative features

3. **AI/ML Integration**
   - LLM APIs (OpenAI, Anthropic, Gemini)
   - RAG systems, embeddings
   - Vector databases, semantic search

4. **Mobile Applications**
   - Android development support
   - Mobile-optimized web apps

5. **DevOps & Infrastructure**
   - Docker containerization
   - CI/CD pipelines
   - Nginx configuration
   - Hot reload development

6. **Security Tools**
   - Bug bounty research
   - Vulnerability analysis
   - Security auditing
   - Reverse engineering

---

## Resource Utilization

### Current State (2025-11-07)
- **CPU:** ~80% average utilization (healthy for active development)
- **Memory:** 22% used, 78% free (excellent headroom)
- **Disk:** 51% used, 427GB available (plenty of space)
- **Containers:** 58 running smoothly
- **Stability:** 77 days uptime without reboot

### Capacity for Growth
- ✅ Can easily add 10-15 more containerized services
- ✅ Memory capacity for heavy ML/AI workloads
- ✅ Disk space for extensive datasets and artifacts
- ✅ CPU headroom for additional parallel processing

---

## Notable Strengths

1. **Extensive Agent Ecosystem** - 48 specialized agents for diverse tasks
2. **Robust Infrastructure** - 77-day uptime, comprehensive monitoring
3. **Polyglot Environment** - Multiple languages and frameworks
4. **MCP Integration** - Connected to 7 external services
5. **Production-Ready** - Multiple live applications serving traffic
6. **Excellent Observability** - Grafana + Prometheus + exporters
7. **Scalable Architecture** - Docker-based, easily extensible

---

## Current Limitations & Considerations

1. **High CPU Load** - Running at ~80%, new intensive tasks may need optimization
2. **Swap Usage** - 11GB swap in use, indicates some memory pressure
3. **Container Density** - 58 containers is substantial, careful resource management needed
4. **No Kubernetes** - Docker Compose orchestration (simpler, but less robust for large scale)

---

## Quick Reference Commands

### System Status
```bash
# Overall health
uptime
free -h
df -h

# Container status
docker ps --format "table {{.Names}}\t{{.Status}}"

# Service inventory
jq '.allocations' /home/hercules/system-apps-config/PORT_REGISTRY.json

# Agent listing
jq -r '.agents | keys[]' /home/hercules/.agent-registry/agents.json
```

### Resource Monitoring
```bash
# CPU usage
top -bn1 | head -20

# Memory breakdown
free -h

# Disk usage by directory
du -sh /home/hercules/* | sort -h

# Container resources
docker stats --no-stream
```

---

## Related Experiments
- Potentially: Container optimization experiments
- Potentially: Load testing new services
- Potentially: AI model integration POCs

---

## Future Exploration Ideas

- [ ] Kubernetes migration POC for improved orchestration
- [ ] GPU integration for ML workloads
- [ ] Service mesh implementation (Istio/Linkerd)
- [ ] Advanced caching strategies (Varnish, Redis clustering)
- [ ] Multi-region deployment testing
- [ ] Performance benchmarking suite
- [ ] Automated scaling experiments

---

**Status:** 🌿 Growing (will update quarterly)

**Quick Assessment:** Powerful, stable platform with excellent tooling and agent support. Capable of handling complex full-stack development, AI integration, security research, and production deployments. Resource utilization is healthy with room for expansion.
