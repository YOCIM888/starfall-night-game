# 🌃 Starfall Night · NEON NIGHTFALL

A cyberpunk-themed social deduction (Werewolf-style) web game. Three factions, over a dozen roles — outwit your opponents under neon lights!

## 🎮 How to Play

1. Choose the player count (6/8/10/12/14) and your role on the setup screen
2. The game cycles through **Night → Day → Vote** phases
3. Use skills at night, discuss during the day, and vote to exile suspects
4. Eliminate the opposing faction to win

## ⚔️ Three Factions

| Faction | Win Condition |
|---------|---------------|
| Tian Star (天星) | Eliminate all Di Star players |
| Di Star (地星) | Eliminate all Tian Star players |
| Loose Immortal (散仙) | Survive and have at least 2 players you silenced be exiled |

## 🌟 Roles

### Tian Star Faction
| Role | Skill |
|------|-------|
| Tiansu Star | Transfer damage to another player; immune on the first night |
| Tianquan Star | Zero out a player's votes after voting concludes |
| Tiandun Star | Guard up to 2 players each night from damage |
| Tianguang Star | Revive a player who died that night |
| Tianwang Star | Check a player's faction each night |
| Tianheng Star | Track a player to see if they used an active skill |
| Tiandou Star | Double vote while the Loose Immortal lives; gains a life-or-death gamble after |

### Di Star Faction
| Role | Skill |
|------|-------|
| Disha Star | Kill a player each night |
| Dibao Star | Take another player down when exiled |
| Didu Star | Poison a player — death occurs 2 nights later |
| Diyan Star | Immune to Disha attacks; stores a curse kill |
| Dimei Star | On death, mark a player for +1 vote in the next 2 votes |
| Diying Star | Break Tiandun's guard and reveal the guardian's identity |

### Loose Immortal
| Role | Skill |
|------|-------|
| Loose Immortal | Immune to kills, first exile can be negated, silence a player each night |

## 🛠️ Tech Stack

- Pure HTML5 + CSS3 + JavaScript
- Cyberpunk neon UI design
- Font Awesome icons
- Google Fonts (Inter)

## 🚀 Getting Started

Open `index.html` in your browser to start playing.

## 📁 Project Structure

```
├── index.html                # Game page
├── starfall_night_game.css   # Styles
├── starfall_night_game.js    # Game logic
└── audio/                    # Background music
```
