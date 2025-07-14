# Deploy or Die: A Flox Survival Game - Official Rulebook

## Table of Contents
1. [Game Overview](#game-overview)
2. [Components](#components)
3. [Setup](#setup)
4. [How to Play](#how-to-play)
5. [Card Types](#card-types)
6. [Combat](#combat)
7. [Environments](#environments)
8. [Winning the Game](#winning-the-game)
9. [Advanced Rules](#advanced-rules)
10. [Quick Reference](#quick-reference)

## Game Overview

In Deploy or Die, you are a developer venturing into the treacherous Dependency Dungeon. Using the power of Flox environments, you must overcome bugs, solve challenges, and ultimately deploy your application to production.

**Players**: 1-4
**Time**: 45-90 minutes
**Age**: 12+

## Components

- 200 Package Cards
- 60 Command Cards
- 40 Environment Cards
- 80 Challenge/Room Cards
- 40 Bug Monster Cards
- 20 Artifact Cards
- 4 Developer Class Cards
- 100 Corruption Tokens
- 4 Developer Meeples
- 1 Dungeon Board
- 4 Environment Boards
- 2 Six-sided Dice
- Energy Tokens
- HP Markers

## Setup

1. **Choose Developer Class**: Each player selects a Developer Class card:
   - Backend Dev: +2 Package Power, 5 Energy/turn
   - Frontend Dev: +1 Action/turn, 6 Energy/turn
   - DevOps Engineer: Environment switching is free, 5 Energy/turn
   - Full-Stack Dev: No restrictions, 5 Energy/turn

2. **Prepare Decks**: 
   - Shuffle Package Cards into Package Deck
   - Shuffle Command Cards into Command Deck
   - Create Dungeon by shuffling Room Cards by level (1-3)
   - Place Boss Card at end of each level

3. **Starting Resources**:
   - 1 Basic Environment Card
   - 3 Package Cards
   - 2 Command Cards
   - 20 HP
   - 5 Energy Tokens

4. **Dungeon Setup**:
   - Place entry room face-up
   - Stack remaining Level 1 rooms face-down
   - Repeat for Levels 2 and 3

## How to Play

### Turn Structure

Each turn consists of three phases:

1. **Energy Phase**
   - Gain Energy based on your class
   - Draw 1 card (Package or Command, your choice)
   - Clear any "until end of turn" effects

2. **Action Phase**
   - Play cards by paying Energy costs
   - Activate environment abilities
   - Move between rooms (costs 1 Energy)
   - Trade with other players in same room

3. **Environment Phase**
   - Check for package conflicts
   - Apply corruption effects
   - Resolve any triggered abilities

### Actions

Players may perform multiple actions per turn as long as they have Energy:

- **Install Package** (X Energy): Add Package card to environment
- **Use Command** (Usually 1-2 Energy): Play Command card for effect
- **Move** (1 Energy): Enter new room or retreat
- **Trade** (1 Energy): Exchange cards with teammate
- **Rest** (All Energy): Heal 5 HP, clear 1 Corruption

## Card Types

### Package Cards
- **Cost**: Energy required to install
- **Debug Power**: Damage dealt to bugs
- **Special Abilities**: Unique effects
- **Requirements**: Prerequisites needed
- **Conflicts**: Incompatible packages

### Command Cards
- **Instant**: Play anytime, even opponent's turn
- **Action**: Play during your Action Phase
- **Reaction**: Play in response to specific triggers

### Environment Cards
- Provide base stats and abilities
- Can be switched using `flox activate`
- Maximum 3 active via Layering

### Bug Monster Cards
- **HP**: Health points
- **Attack**: Damage dealt each turn
- **Special**: Unique abilities
- **Loot**: Rewards when defeated

### Challenge Cards
- **Requirement**: What you need to pass
- **Success**: Reward for completion
- **Failure**: Penalty for failing
- **Optional**: Side objectives for bonus rewards

## Combat

When encountering Bug Monsters:

1. **Bug Spawns**: Read card, apply entrance effects
2. **Player Turn**: Use packages/commands to attack
3. **Bug Turn**: Bug attacks based on card text
4. **Repeat** until bug is defeated or player retreats/dies

### Damage Calculation
- Base Damage = Package Debug Power
- Modified by environment bonuses
- Some packages have type advantages
- Critical hits on natural 6 (roll d6)

## Environments

### Basic Rules
- One Active Environment at a time
- Switching costs Energy (unless DevOps class)
- Corrupted environments cause ongoing damage

### Layering (Advanced)
- Combine up to 3 environments
- Each layer adds its bonuses
- Risk of conflicts increases
- Powerful late-game strategy

### Corruption
- Failed challenges add Corruption Tokens
- 5 Corruption = -1 HP per turn
- 10 Corruption = Environment destroyed
- Can be cleansed with specific commands

## Winning the Game

### Solo/Cooperative Victory
- Reach the Production Gate (final room)
- Defeat the deployment boss
- Have at least 1 HP remaining
- Successfully deploy (pass final challenge)

### Competitive Victory
- First player to deploy wins
- Or last player alive if others fall

### Scoring (Optional)
- 10 points per defeated boss
- 5 points per completed challenge
- 2 points per package in final environment
- -3 points per corruption token
- Bonus: 20 points for no environment resets

## Advanced Rules

### Package Dependencies
Some packages require others to function:
- Must install dependencies first
- Chain bonuses for complete stacks
- Example: npm requires Node.js

### Version Conflicts
- Packages may specify version requirements
- Incompatible versions cause corruption
- Version Manager artifacts help resolve

### Platform-Specific Challenges
- Some rooms require specific OS
- Cross-platform packages always work
- Platform switching has penalties

### Collaborative Mode
- Share environments with `flox push/pull`
- Combined attacks on bosses
- Shared resource pool variant
- Revive fallen players with fresh environments

### Time Attack Variant
- 60-second turn timer
- Rush decisions create "technical debt"
- Debt tokens = negative points
- Speed bonuses for quick clears

## Quick Reference

### Energy Costs
- Install Package: Listed on card
- Basic Command: 1 Energy
- Move Room: 1 Energy
- Switch Environment: 2 Energy (0 for DevOps)
- Rest: All remaining Energy

### Status Effects
- **Activated**: Environment is active
- **Corrupted**: Taking damage over time
- **Locked**: Cannot switch environments
- **Boosted**: Temporary power increase
- **Debugged**: Immune to bug effects

### Common Combos
- Python + Debugger = +2 damage vs bugs
- Docker + Kubernetes = Manage multiple environments
- Git + CI/CD = Automatic version control
- Rust + C++ = Memory leak immunity

### Turn Order Summary
1. Gain Energy & Draw
2. Play Cards & Act
3. Resolve Environment
4. Check Victory/Defeat

### First Game Tips
- Start with Development Environment
- Focus on 2-3 compatible packages
- Save energy for emergencies
- Clear corruption regularly
- Don't forget to use commands!

## FAQ

**Q: Can I have multiple copies of the same package?**
A: No, each package is unique in your environment.

**Q: What happens at 0 HP?**
A: In co-op, others can revive you. In competitive, you're eliminated.

**Q: Can I uninstall packages?**
A: Yes, with the `flox uninstall` command card.

**Q: Do artifacts stay between environments?**
A: Yes, artifacts are permanent until used/lost.

**Q: Can bugs attack on the turn they spawn?**
A: No, unless specifically stated on the card.

---

*Remember: In the Dependency Dungeon, reproducibility is survival!*

For questions and clarifications, visit: flox.dev/dungeon-support