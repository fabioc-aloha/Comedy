# 🎭 Git Workflow for Comedy Development

## Quick Commands for Comedy Writers

### Daily Material Development
```bash
# Quick save of new material
git comedy-save "✨ New joke: [brief description]"

# Save character development
git comedy-save "🎭 Character update: [character name] - [what changed]"

# Save routine work
git comedy-save "🎪 Routine: [routine name] - [improvement made]"
```

### Performance Tracking
```bash
# Before performance
git comedy-save "🎬 Pre-performance: [venue/event] - material ready"

# After performance
git comedy-save "📊 Performance review: [venue] - [success level] - [key learnings]"

# Material refinement after testing
git comedy-save "🔧 Material refinement: [joke/routine] - [what improved]"
```

### Character Development
```bash
# New character creation
git comedy-save "👤 New character: [character name] - initial creation"

# Character evolution
git comedy-save "📈 Character evolution: [character name] - [development notes]"

# Character consistency fix
git comedy-save "🔄 Character consistency: [character name] - [consistency issue fixed]"
```

### Learning and Analysis
```bash
# Pattern recognition
git comedy-save "🧠 Pattern recognition: [what pattern discovered]"

# Technique mastery
git comedy-save "⚡ Technique improvement: [technique] - [progress made]"

# Cognitive architecture update
git comedy-save "🔮 Architecture update: [memory file] - [improvement]"
```

## Commit Message Convention

### Format
```
[emoji] [category]: [brief description]

[optional longer description]
[performance metrics if applicable]
[learning extracted if applicable]
```

### Emoji Guide
- 🎭 **Character work**: Persona development, voice work
- ✨ **New material**: Fresh jokes, bits, routines
- 🎪 **Routine work**: Set construction, ordering, flow
- 🔧 **Refinement**: Improving existing material
- 📊 **Analysis**: Performance review, success metrics
- 🎬 **Performance**: Live testing, audience feedback
- 🧠 **Learning**: Pattern recognition, technique improvement
- 🔮 **Architecture**: Cognitive system improvements
- 📚 **Research**: Comedy study, technique learning
- 🎯 **Testing**: Material testing, feedback integration

### Example Commits
```bash
git commit -m "🎭 Character: Self-deprecating husband - added coordination incompetence trait"

git commit -m "✨ New joke: Airport security confusion - 3 punchline variations developed"

git commit -m "🎪 Routine: Punta Cana disaster - restructured for better energy flow"

git commit -m "📊 Performance review: Open mic success - timing improvements identified"
```

## Branching Strategy for Comedy Development

### Main Branch: `master`
- Stable, performance-ready material
- Tested jokes and routines
- Proven character work

### Development Branches
```bash
# Create feature branch for new material
git checkout -b joke/travel-disasters
git checkout -b character/anxious-parent
git checkout -b routine/5min-relationships

# Work on material, then merge when ready
git checkout master
git merge joke/travel-disasters
```

### Experimental Branches
```bash
# For risky or experimental material
git checkout -b experiment/dark-humor-test
git checkout -b experiment/crowd-work-integration

# Keep experimental - don't merge unless successful
```

## Useful Git Commands for Comedy

### Review Recent Work
```bash
# See comedy-related commits
git joke-log

# Review performance-related work
git performance-review

# See what changed in last commit
git show HEAD

# Compare versions of a joke/routine
git diff HEAD~1 HEAD comedy-projects/jokes/my-joke.md
```

### Backup and Recovery
```bash
# Create backup before major changes
git tag backup-$(date +%Y%m%d)

# Recover previous version of material
git checkout HEAD~1 -- comedy-projects/routines/my-routine.md

# See all versions of a file
git log --follow -- path/to/joke.md
```

### Collaboration Features
```bash
# Add remote repository (if working with writing partners)
git remote add origin [repository-url]

# Push your comedy work
git push origin master

# Get updates from collaborators
git pull origin master
```

## Performance Integration Workflow

### Before Each Performance
1. **Commit current state**
   ```bash
   git comedy-save "🎬 Pre-performance: [venue] - material locked"
   ```

2. **Create performance branch**
   ```bash
   git checkout -b performance/$(date +%Y%m%d)-venue-name
   ```

3. **Make performance-specific adjustments**
   ```bash
   git comedy-save "🎯 Venue adaptation: [specific changes for audience]"
   ```

### After Each Performance
1. **Document results**
   ```bash
   git comedy-save "📊 Performance results: [success metrics and audience feedback]"
   ```

2. **Extract learnings**
   ```bash
   git comedy-save "🧠 Learning extraction: [what worked, what didn't, improvements needed]"
   ```

3. **Merge successful changes back**
   ```bash
   git checkout master
   git merge performance/$(date +%Y%m%d)-venue-name
   ```

## Git Aliases Reference

```bash
# Quick material save
git comedy-save "message"

# View comedy commits
git joke-log

# Review performance work
git performance-review

# Quick status
git status

# See recent changes
git log --oneline -10
```

## Best Practices for Comedy Git

1. **Commit Often**: Every joke refinement, character tweak, routine adjustment
2. **Descriptive Messages**: Include what changed and why
3. **Performance Tracking**: Document before/after every live test
4. **Learning Documentation**: Capture insights and pattern recognition
5. **Character Evolution**: Track persona development systematically
6. **Backup Critical Material**: Tag important milestones

---

*Git workflow optimized for systematic comedy development and cognitive architecture integration* 🎭✨
