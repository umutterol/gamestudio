# Game Studio

**AI-Powered Game Development Team for Claude Code**

*Originally created by [Tuna Pamir](https://github.com/pamirtuna), now maintained by [Umut Tunc Erol](https://github.com/umutterol)*

Transform your game ideas into reality with an intelligent team of specialized AI agents. Each agent is an expert in their domain - from game design to QA testing - working together seamlessly to help you create games for any platform.

![Claude Code Plugin](https://img.shields.io/badge/claude--code-plugin-blue)
![Platform](https://img.shields.io/badge/platform-PC%20%7C%20Mobile%20%7C%20Console-green)
![Agents](https://img.shields.io/badge/agents-5%20specialized-orange)
![License](https://img.shields.io/badge/license-MIT-purple)

## Features

- **5 Specialized Agents**: Game Design, Game Dev, Game Art, Market Intel, QA
- **4 Slash Commands**: `/new-game`, `/design`, `/prototype`, `/develop`
- **Multi-Engine Support**: Godot, Unity, and Unreal Engine
- **Cross-Platform**: PC, Mobile, Console, Web development
- **Market Intelligence**: Competitive analysis and analytics
- **Production Templates**: GDD, feature specs, and more

## Installation

### Option 1: From Marketplace

```bash
/plugin marketplace add umutterol/gamestudio
/plugin install gamestudio
```

### Option 2: Direct GitHub Install

```bash
/plugin add umutterol/gamestudio
```

### Option 3: Manual Installation

```bash
# Clone the repository
git clone https://github.com/umutterol/gamestudio.git

# Copy to your project
cp -r gamestudio/.claude-plugin your-project/
cp -r gamestudio/commands your-project/.claude/
cp -r gamestudio/agents-plugin your-project/.claude/agents/

# Or install globally
cp -r gamestudio/.claude-plugin ~/.claude/
cp -r gamestudio/commands ~/.claude/commands/
cp -r gamestudio/agents-plugin ~/.claude/agents/
```

## Usage

### Slash Commands

| Command | Purpose |
|---------|---------|
| `/new-game` | Initialize a new game project |
| `/design` | Enter design phase - documentation focus |
| `/prototype` | Rapid proof of concept development |
| `/develop` | Full production pipeline |

### Example

```bash
# Start a new game
/new-game

# Or invoke agents directly
claude "Use the game-design agent to create a GDD for my platformer"
claude "Use the market-intel agent to analyze the roguelike market"
```

## Agents

| Agent | Role | Expertise |
|-------|------|-----------|
| **game-design** | Vision & Features | GDD, mechanics, content design, user stories |
| **game-dev** | Implementation | Core systems, game feel, optimization, code |
| **game-art** | Visual Direction | Art style, shaders, UI/UX, accessibility |
| **market-intel** | Market & Analytics | Competitors, metrics, A/B testing, projections |
| **qa** | Quality Assurance | Testing, bugs, performance, release validation |

## Development Modes

### Design Mode
Create comprehensive documentation before development:
- Game Design Document (GDD)
- Art style guides
- Technical architecture
- Market validation

### Prototype Mode
Build a playable proof of concept quickly:
- Core mechanic implementation
- Basic gameplay loop
- Validation testing

### Development Mode
Full production pipeline:
- Complete implementation
- Asset creation
- Quality assurance
- Release preparation

## Project Structure

When you run `/new-game`, the system creates:

```
your-game/
├── documentation/
│   ├── design/          # GDD, systems, mechanics
│   ├── art/             # Style guides, concepts
│   └── production/      # Timeline, milestones
├── source/              # Game source code (engine-specific)
├── qa/                  # Testing and bug reports
└── project-config.json  # Project configuration
```

## Engine Support

The agents have built-in knowledge for:

- **Godot**: GDScript, node-based architecture, signals
- **Unity**: C#, components, ScriptableObjects
- **Unreal**: Blueprints, C++, Gameplay Framework

## Templates

Production-ready templates are included in `/templates`:
- Game Design Document
- Feature Specifications
- Market Analysis
- Analytics Setup
- Engine Configuration

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](LICENSE) for details.

## Authors

**Umut Tunc Erol** (Maintainer)
- GitHub: [@umutterol](https://github.com/umutterol)

**Tuna Pamir** (Original Creator)
- GitHub: [@pamirtuna](https://github.com/pamirtuna)

## Support

- [GitHub Issues](https://github.com/umutterol/gamestudio/issues)

---

*Originally created by Tuna Pamir, maintained with love by Umut Tunc Erol*
