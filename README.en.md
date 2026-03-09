# OpenClaw Automation Learning & Training

## Project Positioning
This repository is designed to build and iterate an **OpenClaw automation learning and training system** with an engineering-first approach.

The focus is not one-off scripts, but a reusable and measurable capability stack:
- Automated task orchestration (scheduling, triggering, reporting)
- Standardized and versioned Prompt/Skill assets
- Runtime data collection and effectiveness evaluation
- Continuous training loop (execution → feedback → optimization)

## Core Capabilities
- **Automation Pipelines**: Daily automation workflows (reports, backups, content pipelines)
- **Skill Engineering**: Skill installation, adaptation, composition, and evolution
- **Operational Memory**: Structured persistence of key configs, practices, and decisions
- **Multi-Environment Deployment**: Migration and recovery across Linux/macOS/cloud hosts

## Key Directories
- `automation/`: automation scripts and scheduled jobs
- `skills/`: reusable skills and extensions
- `memory/`: operational memory and long-term knowledge
- `duoduo/`: business-case assets and generated outputs (retain as needed)
- `backups/`: backup and migration artifacts

## Engineering Principles
1. **Traceable**: critical changes are logged and auditable
2. **Recoverable**: fast migration and rollback for config/state
3. **Measurable**: evaluate by token usage, success rate, latency, etc.
4. **Risk-Minimized**: incremental changes over high-risk big-bang operations

## Use Cases
- OpenClaw personal assistant operations automation
- Agent workflow training and iterative optimization
- Scripted content generation pipelines
- Cross-server / cross-platform migration and recovery

## Quick Start
1. Configure OpenClaw gateway and model credentials
2. Initialize jobs under `automation/`
3. Install/load skills based on your business goals
4. Enable cron, validate on small scale, then scale up

## Internationalization
This repository follows bilingual documentation rules:
- Chinese: `README.md`
- English: `README.en.md`

Please keep both README files aligned in structure and meaning.

## License
This repository follows the root `LICENSE` file.