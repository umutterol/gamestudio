# Contributing to Game Studio Sub-Agents

*Originally created by [Tuna Pamir](https://github.com/pamirtuna), maintained by [Umut Tunc Erol](https://github.com/umutterol)*

Thank you for your interest in contributing! This project aims to make game development accessible to everyone through AI assistance.

## How to Contribute

### Reporting Bugs
- Use the GitHub Issues tab
- Describe expected vs actual behavior
- Include error messages if any
- Specify which agent or command has issues

### Suggesting Features
- Check existing issues first
- Describe the problem your feature solves
- Provide use case examples

### Improving Agents
- Enhance agent prompts and capabilities
- Add new agent expertise areas
- Improve agent coordination

### Improving Documentation
- Fix typos and clarify instructions
- Add examples and use cases
- Create tutorials

## Development Setup

```bash
# Fork and clone
git clone https://github.com/umutterol/gamestudio-subagents.git
cd gamestudio-subagents

# Create branch
git checkout -b feature/your-feature-name

# Make changes and test
# Commit with clear messages

# Push and create PR
git push origin feature/your-feature-name
```

## Project Structure

```
gamestudio-subagents/
├── .claude-plugin/      # Plugin metadata
│   └── plugin.json
├── agents-plugin/       # Agent definitions
│   ├── game-design.md
│   ├── game-dev.md
│   ├── game-art.md
│   ├── market-intel.md
│   └── qa.md
├── commands/            # Slash commands
│   ├── new-game.md
│   ├── design.md
│   ├── prototype.md
│   └── develop.md
├── templates/           # Project templates
└── engine_configs/      # Engine configurations
```

## Code Standards

### Agent Definitions
- Clear role and purpose
- Structured deliverables
- Practical code examples
- Engine-specific knowledge where applicable

### Slash Commands
- Clear workflow description
- Step-by-step guidance
- User-friendly prompts

### Documentation
- Clear and concise
- Include examples
- Keep updated with changes

## Pull Request Process

1. Update documentation for any changes
2. Test commands and agents work correctly
3. Request review from maintainers

## Community Guidelines

- Be respectful and constructive
- Help newcomers get started
- Share knowledge and experiences

Thank you for helping make game development more accessible!
