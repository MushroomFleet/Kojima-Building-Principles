# Kojima Building Principles

> *"Every mechanical system is an opportunity for thematic expression, and every player action is an opportunity for meaningful consequence."*

A specialized prompt framework for enhancing creative project plans through mythological substrate analysis and multi-dimensional design assessment. Inspired by Hideo Kojima's design philosophy—where invisible mythological architecture provides structural DNA, mechanics physically manifest themes, and accessible cores support infinite depth.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Compatible](https://img.shields.io/badge/Claude-Compatible-blueviolet)](https://claude.ai)
[![LLM Agnostic](https://img.shields.io/badge/LLM-Agnostic-green)](/)

---

## 🎯 What This Does

Kojima Building Principles analyzes creative plans against **Dimension Zero** (mythological substrate) and **nine surface dimensions** to identify enhancement opportunities:

| Dimension | Key Question |
|-----------|--------------|
| **0. Mythological Substrate** | What creation myth could structure this world? |
| 1. Narrative Layering | Surface → Theme → Myth → Meta? |
| 2. Mechanical Fusion | Does mechanic embody theme AND myth? |
| 3. Arcade Foundation | What's the pure 30-second loop? |
| 4. Strand Systems | How do strangers help strangers? |
| 5. Consequence Architecture | Do choices echo through myth-logic? |
| 6. Character Ensemble | Does cast cover thematic spectrum? |
| 7. Genre Alchemy | What incompatible genre creates friction? |
| 8. Contemplative Pacing | Where is ritual space for reflection? |
| 9. SF/Horror Integration | What's the technological sacred? |

The output is a scored assessment with concrete enhancement suggestions that deepen narrative and aesthetic roots **at the planning stage**—before implementation locks in shallow foundations.

---

## 🎮 Primary Use Case: Game Design

This framework was developed for enhancing game design documents, where:

- **Mythology becomes invisible load-bearing structure** (players feel depth without identifying source)
- **Mechanics physically manifest themes** (not just "gamey" systems attached to story)
- **Arcade satisfaction remains untouched** (depth never compromises accessibility)

### The Kojima Test

A design achieves true integration when:
1. ✅ Scholars could connect it to source myths
2. ✅ Players never need to know mythology exists
3. ✅ Myths are systems, not just story
4. ✅ Core gameplay loop fully satisfies in isolation
5. ✅ The work feels "about something" even if inarticulable

---

## 🔧 Not Limited to Games

While optimized for game design, this framework enhances any creative project with:

- **Narrative structure** (films, novels, series, worldbuilding)
- **Thematic depth** (brand narratives, experience design)
- **Systemic design** (interactive installations, escape rooms, ARGs)
- **Aesthetic coherence** (visual design systems, architectural concepts)

The core insight—that mythological mapping provides invisible structural coherence—applies wherever you want audiences to sense depth they can't quite articulate.

---

## 📋 Workflow

```
┌─────────────────┐     ┌──────────────────────────┐     ┌─────────────────────┐
│  INPUT          │     │  PROMPT                  │     │  OUTPUT             │
│  Plan Document  │ ──► │  "Assess using Kojima    │ ──► │  Enhancement        │
│  (GDD, pitch,   │     │   Building Principles"   │     │  Suggestions Plan   │
│   concept, etc) │     │                          │     │  (README_KJ.md)     │
└─────────────────┘     └──────────────────────────┘     └─────────────────────┘
```

### Simple Usage

1. Provide your plan document (game design doc, narrative outline, concept pitch)
2. Request: *"Assess using Kojima Building Principles"*
3. Receive: Dimensional scoring + mythological framework recommendations + concrete enhancements

---

## 🛠️ Installation Methods

### Option 1: Claude Code Capabilities (.skill)

For users with **Claude Code** or **Claude Desktop** with computer use enabled:

```bash
# Clone to your skills directory
git clone https://github.com/MushroomFleet/Kojima-Building-Principles.git /path/to/skills/user/kojima-building-principles
```

The skill will be automatically detected. Trigger with: *"using Kojima building principles"*

**Skill Structure:**
```
kojima-building-principles/
├── SKILL.md                          # Skill definition and workflow
└── references/
    ├── mythological-substrate.md     # Dimension Zero deep-dive
    ├── surface-dimensions.md         # Dimensions 1-9 detailed
    ├── assessment-protocol.md        # Scoring methodology
    ├── output-template.md            # README_KJ.md format
    ├── mythology-primer.md           # Quick myth reference
    └── example-enhancement.md        # Worked example
```

### Option 2: System Prompt (Any LLM)

For use with **ChatGPT, Claude (web), Gemini, local models**, or any conversational AI:

1. Copy contents of `SKILL.md` and `references/*.md` into your system prompt or custom instructions
2. Alternatively, paste the consolidated prompt from `system-prompt-full.md` (all references merged)
3. Begin conversation with your plan document + trigger phrase

### Option 3: API Integration

```python
# Example: Using with Anthropic API
import anthropic

client = anthropic.Anthropic()

# Load the system prompt
with open("system-prompt-full.md", "r") as f:
    system_prompt = f.read()

# Your game design document
with open("my-game-design.md", "r") as f:
    game_doc = f.read()

message = client.messages.create(
    model="claude-sonnet-4-20250514",
    max_tokens=8192,
    system=system_prompt,
    messages=[
        {
            "role": "user", 
            "content": f"{game_doc}\n\nAssess using Kojima Building Principles"
        }
    ]
)
```

---

## 📖 Mythological Traditions Supported

The framework includes mapping guidance for:

| Tradition | Best For |
|-----------|----------|
| **Iroquois Creation** | Twin conflict, world-building from void, necessary opposition |
| **Egyptian Cosmology** | Death/rebirth cycles, liminal spaces, soul mechanics |
| **Norse (Yggdrasil/Ragnarök)** | Connected realms, cataclysm/renewal, fate-webs |
| **Greek/Roman** | Tragic fate, heroic cycles, divine intervention |
| **Babylonian/Sumerian** | Exile narratives, civilization collapse, cosmic order |
| **Gnostic** | Hidden knowledge, fallen creation, spiritual escape |
| **Buddhist/Hindu** | Cycles, karma, interconnection, illusion |
| **Celtic** | Otherworld passage, seasonal cycles, transformation |

Custom mythological frameworks can be developed for any project.

---

## 📄 Output Format

The framework generates `README_KJ.md` containing:

1. **Executive Summary** - Core enhancement opportunities
2. **Dimensional Assessment** - Scores (1-5) for all ten dimensions
3. **Mythological Framework** - Recommended traditions with structural mapping
4. **Detailed Enhancements** - Specific changes per dimension
5. **Implementation Priority** - Phased enhancement roadmap
6. **Enhanced Plan** - Complete rewritten document incorporating changes
7. **Appendices** - Mythological reference, cross-validation, Kojima Test results

---

## 🤝 Contributing

Contributions welcome:

- **New mythological tradition mappings** - Expand the reference library
- **Worked examples** - Additional enhancement case studies
- **Dimension refinements** - Improved assessment criteria
- **Tool integrations** - Plugins for game engines, writing software

---

## 📚 Citation

### Academic Citation

If you use this framework in your research or project, please cite:

```bibtex
@software{kojima_building_principles,
  title = {Kojima Building Principles: Mythological Substrate Analysis for Creative Design Enhancement},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/Kojima-Building-Principles},
  version = {1.0.0}
}
```

### Donate

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)

---

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

---

*"The mythology must be present but not announced. Players feel it, don't read it. Structurally load-bearing—remove it and design collapses. Discoverable—rewards analysis without requiring it."*
