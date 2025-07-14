# Deploy or Die - Card Examples

## Package Cards

### Common Packages (1-2 cost)
**Python 3.11**
- Cost: 2 Energy
- Debug Power: 3
- Special: +1 card draw when installed
- *"Readable and reliable, perfect for beginners"*

**Bash Script**
- Cost: 1 Energy
- Debug Power: 2
- Special: Can be played instantly (no install needed)
- *"Quick and dirty, but it works"*

**JSON Parser**
- Cost: 1 Energy
- Debug Power: 1
- Special: Reveals hidden properties of Bug Monsters
- *"See through the data structures"*

### Uncommon Packages (3-4 cost)
**Node.js + NPM**
- Cost: 3 Energy
- Debug Power: 4
- Special: Chain up to 2 actions per turn
- Conflict: Cannot coexist with Deno
- *"Asynchronous power at your fingertips"*

**Rust Compiler**
- Cost: 4 Energy
- Debug Power: 6
- Special: Immune to Memory Leak damage
- *"Slow to compile, but battle-tested"*

**PostgreSQL**
- Cost: 3 Energy
- Debug Power: 2
- Special: Store 3 extra cards in "database"
- *"ACID compliant card storage"*

### Rare Packages (5-6 cost)
**Kubernetes Orchestrator**
- Cost: 6 Energy
- Debug Power: 5
- Special: Can manage 3 environments simultaneously
- Requires: Docker installed first
- *"Container orchestration mastery"*

**TensorFlow GPU**
- Cost: 5 Energy
- Debug Power: 8
- Special: Double damage vs AI-type bugs
- Requirement: CUDA-capable environment
- *"Machine learning firepower"*

### Legendary Packages (7+ cost)
**Nix Flakes**
- Cost: 7 Energy
- Debug Power: 10
- Special: Perfect reproducibility - immune to all conflicts
- *"The ultimate in declarative power"*

## Command Cards

**flox init**
- Type: Instant
- Effect: Create a new environment, discard all corruption
- *"Fresh start, fresh possibilities"*

**flox search**
- Type: Action
- Effect: Look at top 5 Package Cards, take up to 2
- *"80,000 packages at your disposal"*

**flox install -y**
- Type: Quick Action
- Effect: Install a package without energy cost (once per turn)
- *"Skip the confirmation, live dangerously"*

**flox activate -r**
- Type: Reaction
- Effect: Instantly switch to remote environment (dodge one attack)
- *"Beam me up, FloxHub!"*

**flox push --force**
- Type: Attack
- Effect: Force opponent to take one of your corrupted packages
- *"Sharing is caring... sort of"*

## Environment Cards

**Development Environment**
- Starting HP: 20
- Special: +2 to all package installations
- Weakness: Takes double damage from Production Bugs
- *"Where the magic happens"*

**CI/CD Pipeline**
- Starting HP: 15
- Special: Automatically run one test per turn
- Bonus: +1 Energy regeneration
- *"Continuous integration, continuous deployment"*

**Containerized Environment**
- Starting HP: 25
- Special: Isolated from corruption spread
- Limitation: -1 to package effects
- *"Secure but restricted"*

**FloxHub Remote**
- Starting HP: 18
- Special: Can pull cards from any player once per room
- Network Required: Lose 2 HP if disconnected
- *"Cloud-powered collaboration"*

## Bug Monster Cards

### Level 1 Bugs
**Syntax Error**
- HP: 5, Attack: 2
- Special: Returns to hand if not killed in one hit
- *"Unexpected token at line 42"*

**Missing Semicolon**
- HP: 3, Attack: 1
- Special: Prevents command card usage next turn
- *"JavaScript's eternal nemesis"*

### Level 2 Bugs
**Null Pointer Exception**
- HP: 8, Attack: 4
- Special: Attack targets random package
- *"Attempting to access memory at 0x00000000"*

**Race Condition**
- HP: 10, Attack: 3
- Special: Acts twice if player is too slow
- *"Timing is everything"*

### Level 3 Bugs
**Memory Leak**
- HP: 12, Attack: 2
- Special: Gains +2 HP each turn
- Weakness: Rust packages deal double damage
- *"Consuming all available resources"*

**Infinite Loop**
- HP: 15, Attack: 5
- Special: Player skips next turn if hit
- Counter: Break statement cards
- *"while(true) { suffer(); }"*

### Boss Bugs
**The Dependency Conflict Dragon**
- HP: 30, Attack: 8
- Special: Immune to packages with version conflicts
- Phase 2: Spawns mini-bugs when below 15 HP
- *"Requires package >= 2.0, but 1.9 is installed"*

**Works On My Machine Wizard**
- HP: 25, Attack: 6
- Special: Randomly changes environment requirements
- Ultimate: Forces environment swap with player
- *"But it worked perfectly in dev!"*

## Challenge/Room Cards

**The Library of Babel**
- Challenge: Have 5 different language packages installed
- Reward: Draw 3 Package Cards
- Failure: Spawn 2 Syntax Errors
- *"Every permutation of code exists here"*

**Version Control Vault**
- Challenge: Maintain exact package versions for 3 turns
- Reward: Git History artifact (3 undos)
- Failure: Lose half your packages
- *"Commit or lose everything"*

**The Proxy Gauntlet**
- Challenge: Install 3 packages in one turn
- Reward: SSL Certificate artifact
- Failure: Network timeout (skip next turn)
- *"Corporate firewall says no"*

**Platform Crossing**
- Challenge: Have cross-platform packages only
- Reward: Universal Adapter artifact
- Failure: Environment locked to one OS
- *"Write once, run anywhere... hopefully"*

## Artifact Cards

**FloxHub Premium Token**
- Effect: Push/Pull actions cost no energy
- Duration: Permanent
- *"Enterprise-grade environment sharing"*

**The Nixpkgs Codex**
- Effect: Search draws show all 5 cards
- Duration: 5 turns
- *"Ancient wisdom of 80,000 packages"*

**Root Access Privilege**
- Effect: Ignore one challenge requirement
- Duration: Single use
- *"sudo make me a sandwich"*

**Quantum Environment**
- Effect: Exist in two environments simultaneously
- Duration: 3 turns
- *"Schrödinger's development setup"*

## Special Event Cards

**Hackathon Weekend**
- Effect: All players gain +2 Energy for 3 turns
- *"Pizza, caffeine, and code"*

**Production Outage**
- Effect: Boss bugs gain +5 HP this room
- *"All hands on deck!"*

**Open Source Friday**
- Effect: Players can trade packages freely this turn
- *"Contributing back to the community"*

**Zero-Day Discovery**
- Effect: Spawn surprise bug in each environment
- *"CVE-2024-OHNO has been disclosed"*