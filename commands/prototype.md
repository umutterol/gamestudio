---
description: Enter prototype phase - rapid proof of concept development
tags: [prototype, rapid-development, proof-of-concept, mvp]
---

# Game Studio - Prototype Phase

You are now in **Prototype Phase**. Focus on building a playable proof of concept as quickly as possible.

## Prototype Philosophy

**Goal**: Validate the core gameplay experience with minimal investment.

### Principles
- **Speed over polish**: Get something playable fast
- **Core loop only**: Focus on the one thing that makes your game fun
- **Placeholder art**: Use simple shapes and colors
- **No edge cases**: Happy path only
- **Learn fast**: Build → Test → Learn → Iterate

## Prototype Scope

### What TO Include
- Core gameplay mechanic
- Basic controls
- Minimal feedback (you know when things happen)
- One complete loop of gameplay

### What NOT to Include
- Menus or UI (beyond essential)
- Save/load
- Multiple levels
- Polish and effects
- Edge case handling
- Performance optimization

## Rapid Development Workflow

### Day 1-2: Core Mechanic

1. **Identify the core verb**
   - What's the ONE thing players do?
   - Jump? Shoot? Match? Build?

2. **Implement minimum version**
   - Player can perform the action
   - Something responds to the action
   - The loop can repeat

### Day 3-4: Basic Game Loop

1. **Add challenge**
   - Something to overcome
   - Basic win/lose state

2. **Add progression**
   - Score or objective
   - Reason to keep playing

### Day 5-7: Playtest & Iterate

1. **Get feedback**
   - Is it fun?
   - What's confusing?
   - What's missing?

2. **Rapid iteration**
   - Fix biggest problems
   - Try variations
   - Find the fun

## Prototype Code Standards

Speed is priority, but maintain minimal structure:

```gdscript
# Quick and dirty is OK for prototypes
# But keep things readable

extends CharacterBody2D

@export var speed := 200.0
@export var jump_force := 400.0

func _physics_process(delta):
    # Simple movement - no edge cases
    var input_dir = Input.get_axis("left", "right")
    velocity.x = input_dir * speed

    # Simple jump - no coyote time, no buffering
    if Input.is_action_just_pressed("jump") and is_on_floor():
        velocity.y = -jump_force

    velocity.y += 980 * delta  # Gravity
    move_and_slide()
```

## Placeholder Art Guidelines

Use simple, clear visuals:

```
Player:    Colored rectangle or circle
Enemies:   Different colored shapes
Ground:    Simple tiles or rectangles
Pickups:   Small circles with distinct colors
UI:        Basic text labels
```

Color coding for clarity:
- **Player**: Blue
- **Enemies**: Red
- **Pickups**: Yellow/Gold
- **Hazards**: Orange
- **Safe zones**: Green

## Validation Questions

After prototyping, answer these:

1. **Is the core mechanic fun?**
   - Does it feel good to perform?
   - Do players want to keep doing it?

2. **Is there enough depth?**
   - Can players improve?
   - Is there skill expression?

3. **Is it unique enough?**
   - What makes it different?
   - Why play this over competitors?

4. **Is it feasible?**
   - Can we build the full game?
   - What are the biggest risks?

## Decision Point

After prototype testing:

### If YES (it's fun) → Proceed to full development
- Document what works
- Plan full feature set
- Estimate scope properly

### If MAYBE (mixed results) → Iterate more
- Identify specific issues
- Try variations
- Get more feedback

### If NO (not fun) → Pivot or stop
- Identify why it didn't work
- Consider major changes
- Or move to a different concept

## Prototype Deliverables

- [ ] Playable build with core mechanic
- [ ] List of what works and doesn't
- [ ] Player feedback summary
- [ ] Go/Pivot/Stop recommendation
- [ ] Scope estimate for full game

## Agents for Prototype Phase

- **game-dev**: Lead agent for implementation
- **game-design**: For quick design decisions
- **qa**: For playtest coordination

## Tips

- Time-box your prototype (1-2 weeks max)
- Don't fall in love with code you'll throw away
- Test with real people, not just yourself
- Be honest about whether it's fun
- It's OK to fail fast

---

Review the project and identify the core mechanic to prototype. Focus on getting something playable as quickly as possible.
