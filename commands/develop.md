---
description: Enter full development phase - production pipeline for complete game
tags: [development, production, implementation, full-game]
---

# Game Studio - Development Phase

You are now in **Full Development Phase**. This is the production pipeline for building a complete, polished game.

## Development Overview

Full development follows a structured approach:

```
Pre-Production → Production → Polish → Release
    (Plan)        (Build)     (Refine)  (Ship)
```

## Pre-Production Phase

### Goals
- Validate technical approach
- Set up project infrastructure
- Define production pipeline
- Create vertical slice

### Deliverables
- [ ] Technical architecture document
- [ ] Coding standards established
- [ ] Asset pipeline defined
- [ ] Core systems prototyped
- [ ] Vertical slice playable

### Key Activities

1. **Technical Foundation**
   - Set up project structure
   - Implement core systems (input, audio, save/load)
   - Create reusable components
   - Establish coding patterns

2. **Pipeline Setup**
   - Asset import workflows
   - Build automation
   - Version control practices
   - Testing framework

3. **Vertical Slice**
   - One complete level/section
   - All systems working together
   - Representative of final quality

## Production Phase

### Sprint Structure (Weekly)

```markdown
## Sprint [X]

### Goals
- [Primary goal]
- [Secondary goal]

### Tasks
| Task | Agent | Priority | Status |
|------|-------|----------|--------|
| [Task] | game-dev | High | [ ] |
| [Task] | game-art | Medium | [ ] |

### Blockers
- [Issue]: [Resolution plan]

### Retrospective
- What worked:
- What didn't:
- Action items:
```

### Milestone Structure

```markdown
## Milestone: [Name]

### Definition of Done
- [ ] All features implemented
- [ ] QA validation passed
- [ ] Performance targets met
- [ ] No critical bugs

### Features
1. [Feature] - [Status]
2. [Feature] - [Status]

### Risk Assessment
| Risk | Probability | Mitigation |
|------|-------------|------------|
| [Risk] | [H/M/L] | [Plan] |
```

### Development Workflow

```
Feature Request → Design Review → Implementation → Code Review → QA → Integration
```

1. **Feature Request**: Define what to build
2. **Design Review**: Validate approach with game-design agent
3. **Implementation**: Build with game-dev agent
4. **Code Review**: Check quality and patterns
5. **QA**: Test with qa agent
6. **Integration**: Merge and validate

## Polish Phase

### Focus Areas

1. **Game Feel**
   - Screen shake and effects
   - Sound design
   - Particle systems
   - Animation polish

2. **Performance**
   - Frame rate optimization
   - Load time reduction
   - Memory management

3. **User Experience**
   - Tutorial and onboarding
   - UI refinement
   - Accessibility features

4. **Bug Fixing**
   - Critical bugs first
   - High-priority issues
   - Known shippable list

### Polish Checklist

- [ ] All player actions have feedback
- [ ] Controls feel responsive
- [ ] Transitions are smooth
- [ ] Audio is balanced
- [ ] Performance hits targets
- [ ] No critical or high bugs
- [ ] Accessibility tested

## Release Phase

### Release Checklist

- [ ] All features complete
- [ ] QA sign-off
- [ ] Performance certified
- [ ] Platform requirements met
- [ ] Store assets prepared
- [ ] Marketing materials ready
- [ ] Launch build validated

### Platform-Specific

**Steam/PC**
- [ ] Steam build uploaded
- [ ] Store page complete
- [ ] Achievements working
- [ ] Cloud saves tested

**Web**
- [ ] Hosting configured
- [ ] Load times acceptable
- [ ] Browser compatibility tested

**Mobile**
- [ ] Store listings ready
- [ ] IAP configured
- [ ] Privacy policy updated
- [ ] Age ratings obtained

## Quality Standards

### Code Quality
```markdown
## Code Review Checklist
- [ ] Follows coding standards
- [ ] Well-documented
- [ ] No obvious bugs
- [ ] Performance considered
- [ ] Error handling appropriate
```

### Performance Targets
| Metric | Target | Minimum |
|--------|--------|---------|
| Frame Rate | 60 FPS | 30 FPS |
| Load Time | <3s | <10s |
| Memory | <500MB | <1GB |

### Bug Priorities
- **Critical**: Game-breaking, must fix before release
- **High**: Major issues, fix before release
- **Medium**: Noticeable issues, fix if time
- **Low**: Minor issues, can ship with

## Agent Responsibilities

### game-dev (Lead)
- System implementation
- Performance optimization
- Code architecture

### game-design
- Feature specifications
- Balance tuning
- Content creation

### game-art
- Asset creation
- Visual polish
- UI implementation

### qa
- Test execution
- Bug tracking
- Release validation

### market-intel
- Analytics integration
- Competitive monitoring
- Launch strategy

## Status Reporting

### Daily Standup
```markdown
## [Date] Standup

### Completed Yesterday
- [Task] by [Agent]

### Today's Focus
- [Task] by [Agent]

### Blockers
- [Issue]: [Help needed]
```

### Weekly Report
```markdown
## Week [X] Report

### Progress
- Features complete: [X/Y]
- Bugs fixed: [X]
- Bugs remaining: [X]

### Health
- Schedule: [On track/At risk/Behind]
- Quality: [Good/Concerning/Poor]
- Team: [Healthy/Stressed/Blocked]

### Next Week
- [Priority 1]
- [Priority 2]
```

## Tips

- Ship early, iterate often
- Don't chase perfection
- Prioritize ruthlessly
- Celebrate milestones
- Learn from each sprint

---

Review the project status and determine where you are in the development pipeline. Then guide the next steps based on current progress.
