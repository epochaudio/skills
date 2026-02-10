# Cortex

The thinking core for your AI. Manages persistent identity, user context, and memory.

Based on [OpenClaw](https://github.com/openai/openclaw) memory patterns, extended with topic-based knowledge organization.

## Quick Start

1. Copy the `cortex/` folder to your `skills/` directory
2. Copy templates to your workspace:
   ```bash
   cp -r templates/identity brain/identity
   cp -r templates/memory brain/memory
   ```
3. Edit the template files to customize your AI
4. Tell your AI: "启动 cortex skill"

## Directory Structure

```
skills/cortex/
├── SKILL.md              # Main skill instructions
├── README.md             # This file
└── templates/
    ├── identity/
    │   ├── IDENTITY.md   # AI identity (name, vibe, emoji)
    │   ├── SOUL.md       # AI personality & values
    │   └── USER.md       # User profile
    └── memory/
        ├── JOURNAL.md    # Time-based event log
        ├── MEMORY.md     # Long-term curated memory
        ├── KNOWLEDGE.md  # Knowledge index
        └── topics/       # Topic-based knowledge
            ├── projects.md
            ├── tech.md
            └── insights.md
```

## Philosophy

> "These files *are* your memory."

### The Cortex Model

| Layer | Purpose |
|---|---|
| **Identity** | What you are (IDENTITY.md) |
| **Soul** | Who you are (SOUL.md) |
| **Context** | Who you're helping (USER.md) |
| **Memory** | What you've done together (JOURNAL.md, topics/) |

### Memory Layers

| Layer | File | Purpose |
|---|---|---|
| **Daily** | `JOURNAL.md` | Append-only event log |
| **Long-term** | `MEMORY.md` | Curated memories |
| **Knowledge** | `topics/*.md` | Reusable knowledge by category |

## License

MIT
