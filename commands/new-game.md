---
description: Initialize a new game project with the Game Studio framework
tags: [game-development, project-setup, initialization]
---

# Game Studio - New Project Setup

You are initializing a new game development project. Guide the user through setup and create the project structure.

## Project Discovery

First, gather essential information from the user. Ask these questions conversationally:

### Required Information

1. **Project Name**: What is the name of your game?

2. **Game Concept**: Describe your game in one sentence.

3. **Target Platform**:
   - PC (Windows/Mac/Linux)
   - Mobile (iOS/Android)
   - Console
   - Web Browser
   - Multiple platforms

4. **Game Engine**:
   - Godot (recommended for indie)
   - Unity
   - Unreal Engine

5. **Development Mode**:
   - **Design Only**: Create documentation and design specs
   - **Prototype**: Build a proof of concept quickly
   - **Full Development**: Complete production pipeline

6. **Genre**: Action, Strategy, Puzzle, RPG, Simulation, Adventure, Casual, etc.

7. **Art Style**: Pixel art, 3D realistic, stylized, low-poly, etc.

8. **Reference Games**: 1-3 games that inspire this project

9. **Unique Selling Point**: What makes your game special?

## Project Structure Creation

Once you have the information, create the project structure:

```
[project-name]/
├── documentation/
│   ├── design/
│   │   ├── gdd.md              # Game Design Document
│   │   ├── systems/            # System design docs
│   │   └── mechanics/          # Mechanic specifications
│   ├── art/
│   │   ├── style-guide.md      # Visual style guide
│   │   └── concepts/           # Concept art references
│   ├── technical/
│   │   └── architecture.md     # Technical architecture
│   └── production/
│       ├── timeline.md         # Project timeline
│       └── milestones.md       # Milestone definitions
├── source/
│   └── [engine-specific-structure]
├── resources/
│   ├── references/             # Visual references
│   └── market-research/        # Competitor analysis
├── qa/
│   ├── test-plans/
│   └── bug-reports/
└── project-config.json
```

## Project Configuration

Generate a `project-config.json`:

```json
{
  "project": {
    "name": "[Name]",
    "concept": "[One-line description]",
    "genre": "[Genre]",
    "platform": "[Platform]",
    "engine": "[Engine]",
    "mode": "[design/prototype/development]",
    "art_style": "[Style]",
    "version": "0.0.1",
    "created": "[Date]"
  },
  "references": {
    "games": ["[Game 1]", "[Game 2]"],
    "usp": "[Unique selling point]"
  },
  "team": {
    "active_agents": [
      "game-design",
      "game-dev",
      "game-art",
      "market-intel",
      "qa"
    ]
  },
  "milestones": [],
  "status": "initialized"
}
```

## Engine-Specific Setup

### Godot Project
```
source/
├── scenes/
├── scripts/
├── assets/
│   ├── sprites/
│   ├── audio/
│   └── fonts/
├── autoload/
└── project.godot
```

### Unity Project
```
source/
├── Assets/
│   ├── Scripts/
│   ├── Prefabs/
│   ├── Materials/
│   └── Resources/
└── ProjectSettings/
```

### Unreal Project
```
source/
├── Content/
│   ├── Blueprints/
│   ├── Materials/
│   └── Maps/
└── Source/
```

## Initial GDD Template

Create a starter GDD in `documentation/design/gdd.md`:

```markdown
# [Project Name] - Game Design Document

## Overview
**Concept**: [One sentence]
**Genre**: [Genre]
**Platform**: [Platform]
**Target Audience**: [Audience]

## Design Pillars
1. [Pillar 1]
2. [Pillar 2]
3. [Pillar 3]

## Core Loop
[Describe the primary gameplay cycle]

## Key Features
- [Feature 1]
- [Feature 2]
- [Feature 3]

## References
- [Game 1]: [What we're taking from it]
- [Game 2]: [What we're taking from it]

## Unique Selling Point
[What makes this game special]

---
*Document created: [Date]*
*Status: Draft*
```

## Next Steps

After project creation, suggest:

1. **If Design Mode**: Start with market analysis and GDD expansion
2. **If Prototype Mode**: Jump to core mechanic implementation
3. **If Full Development**: Begin with market validation, then design

## Available Agents

Remind the user they can invoke specialized agents:
- `game-design` - For GDD and feature specs
- `game-dev` - For implementation and coding
- `game-art` - For visuals and UI
- `market-intel` - For market research and analytics
- `qa` - For testing and quality

---

Create the project structure, generate the config file, and provide a summary of next steps.
