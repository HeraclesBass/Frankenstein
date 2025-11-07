# 🔬 Experiments

Welcome to the laboratory. This is where ideas come to life (or die trying).

## Experiment Categories

### 🚀 Prototypes (`prototypes/`)
**Purpose:** Full-featured implementations that could become real projects.

**Characteristics:**
- Relatively polished and functional
- Production-ready or near-production-ready
- Could be extracted into standalone projects
- Has tests and documentation

**Examples:**
- MVP of a new service
- Fully-working CLI tool
- Complete API implementation

### 💡 POC - Proof of Concept (`poc/`)
**Purpose:** Test if an idea is technically feasible.

**Characteristics:**
- Focus on core functionality only
- Minimal polish required
- Quick to implement (hours to days)
- Proves or disproves a hypothesis

**Examples:**
- "Can this API do what I need?"
- "Will this architecture work?"
- "Is this library suitable for X?"

### 🎨 Sandbox (`sandbox/`)
**Purpose:** Throwaway code for learning and exploration.

**Characteristics:**
- No quality expectations
- Quick and dirty
- Learning-focused
- May never be complete

**Examples:**
- Testing a new language feature
- Playing with a library
- Reproducing a bug
- Following a tutorial

## Starting a New Experiment

1. **Choose category** based on your goal
2. **Create dated directory:**
   ```bash
   mkdir experiments/[category]/$(date +%Y%m%d)-experiment-name
   cd experiments/[category]/$(date +%Y%m%d)-experiment-name
   ```
3. **Copy template:**
   ```bash
   cp ../../templates/experiment-template.md README.md
   ```
4. **Fill in the template** with your experiment details
5. **Code away!**
6. **Document results** as you go

## Experiment Lifecycle

```
Idea → Setup → Implementation → Testing → Documentation → Review
```

### During the Experiment
- Commit frequently with descriptive messages
- Document challenges as they arise
- Update status in README
- Link to related documentation

### After the Experiment
- Update final results and learnings
- Set final status (✅ Successful | ❌ Failed | ⏸️ Paused)
- Cross-reference in documentation
- Consider graduation to production

## Graduation Path

Successful experiments can:
1. **Graduate to Production** - Move to Hercules platform or standalone repo
2. **Become a Template** - Extract pattern for future use
3. **Inform Documentation** - Create guide based on learnings
4. **Stay as Reference** - Remain as working example

## Active Experiments

<!-- Update this list as you create experiments -->

| Date | Name | Category | Status | Description |
|------|------|----------|--------|-------------|
| YYYY-MM-DD | experiment-name | POC | 🔬 In Progress | What you're testing |

## Failed Experiments Hall of Fame

**Remember:** Failed experiments are successful learning opportunities!

<!-- List notable failures and what you learned -->

---

**Lab Safety Reminder:** Always commit before trying something risky. Git is your safety net.