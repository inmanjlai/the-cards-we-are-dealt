# The Cards We're Dealt

## Original Prompt:
I would like to create a 2d game, it will be story based with multiple outcomes based on your choices, with a turn based combat system, (2d as in side scroller), set in a metro 2033 style setting, Act 1 will include starting in the metro and finding people to join your group as you prepare to go to the surface (which is a hostile uninhabitable land, crawling with mutated humans, scavangers, and other dangers), Act 2 will be the surface level, and Act 3 will be going down into the metro even deeper to find the truth (whatever that is). Im not entirely satisfied with the Act 3 so that is changeable. Anyway, I want there to be classes, and equipement. And I want the game to basically be a deckbuilder. Where each piece of equipment gives you certain cards in your deck, and same with you class choice, and you draw from that deck when you get into combat. I havent thought about action economy yet, so maybe I can get some ideas here. I'd like to incorporate cover mechanics, limited resources like ammo/health/food. Food for camping to regen health etc

# Design Overview

## 🔥 What’s Already Fun

- **Metro setting + deckbuilder mechanics**: Combining oppressive, atmospheric worldbuilding with the strategic joy of a deckbuilder is a unique hook.
- **Choice-driven story**: Multiple outcomes based on player decisions will boost replayability and immersion.
- **Classes + equipment = deck**: Super smart. Encourages experimentation and adds weight to your gear choices.

---

## 🧠 Systems Suggestions

### Combat / Action Economy

To make your turn-based combat snappy and strategic:

- **Standard AP System**: 2–3 Action Points per turn (e.g., Move = 1, Attack = 1, Reload = 1).
- **Card Costs**: Cards cost different AP depending on power.
  - Light attack = 1 AP
  - Suppressive fire = 2 AP
  - Stimpack = Free but exhausts the card
- **Hand Limit**: Draw 4–6 cards per turn to keep turns short and decisions tight.

### Cover Mechanics

Lean into the side-scroller format:

- **Cover Zones**: Place waist-high barriers or derelict structures players can move behind.
- **Cover Effects**:
  - Partial cover = 25% damage reduction
  - Full cover = 50% and chance to avoid hits altogether
  - Some enemies could ignore cover or destroy it

### Survival Systems

You’ve already got great ideas here:

- **Ammo as Card Fuel**: Some attack cards require X ammo to be played.
- **Food/Resting**:
  - Campfires/checkpoints = restore health, reshuffle deck, maybe cook for buffs
  - Food scarcity could gate progress or act as soft time pressure.
- **Random Events**: While camping, sometimes ambushes or moral choices pop up (e.g., a starving child asks for food—do you help?).

---

## 🧭 Narrative Progression & Acts

### Act 1 – Metro Life

- Focus on recruiting allies and surviving human factions.
- Introduce moral decisions—are you helping people or just helping yourself?

### Act 2 – Surface

- Dangerous traversal, scavenging, and dealing with mutants or rival groups.
- Could add weather hazards (radiation storms, acid rain) that affect your deck/draws.

### Act 3 – Deep Metro (Alternative Ideas)

Instead of “finding the truth” as a vague goal, here are some hooks:

- **The Source**: Something is causing the mutations—descend to stop it.
- **Civilization Remnant**: A hidden, thriving community underground—friend or foe?
- **Personal Backstory**: The player character has suppressed memories that resurface.

---

## 🎴 Deckbuilding Ideas

### Classes

- **Soldier**: Weapon-focused, armor-based cards, AoE attacks.
- **Scavenger**: Stealth, evasion, utility cards.
- **Medic**: Buffs, heals, DoTs like poison/stims.
- **Engineer**: Can set traps, create cover, repair gear.

### Card Types

- **Attack**: Requires ammo. High damage but low draw frequency.
- **Tactics**: Positioning, cover use, smoke grenades.
- **Utility**: Medkits, stimulants, scouting.
- **Passive Gear**: Some gear could auto-modify your draw or offer a once-per-combat benefit.

---

## 🧪 Mechanics That Could Really Shine

- **Card Exhaustion/Fatigue**: Some cards are one-use per battle or removed until resting.
- **Party Synergy**: Party members can “combo” with your moves if placed correctly.
- **Moral Deck Influence**: Player choices influence what types of cards show up (Merciless vs Compassionate, for example).

# Feature Plan
## Epic: Core Gameplay Loop
- [ ] As a player, I want to move my character left and right in a side-scrolling world so that I can explore levels.
- [ ] As a player, I want to interact with NPCs in the metro to recruit party members.
- [ ] As a player, I want to trigger story events that offer dialogue choices and branching consequences.
- [ ] As a player, I want to rest/camp between missions so I can recover health and prepare for the next challenge.
- [ ] As a player, I want to manage limited resources like food, ammo, and medkits during exploration.

## Epic: Turn-Based Combat
- [ ] As a player, I want to enter combat when I encounter hostile enemies so I can fight for survival.
- [ ] As a player, I want to draw a hand of cards from my deck at the start of combat.
- [ ] As a player, I want to play cards that consume action points so I can plan my turn strategically.
- [ ] As a player, I want to take cover behind obstacles to reduce incoming damage.
- [ ] As a player, I want to use specific cards that require ammo to deal damage.
- [ ] As a player, I want to reload my weapon using a card/action during combat.
- [ ] As a player, I want to see enemy intent so I can make tactical decisions based on their next move.
- [ ] As a player, I want combat to end when all enemies are defeated or the player flees.

## Epic: Deckbuilding System
- [ ] As a player, I want to choose a class at the beginning that defines my starting deck.
- [ ] As a player, I want to equip gear that adds cards to my combat deck.
- [ ] As a player, I want to upgrade or swap out gear to change the cards I draw in combat.
- [ ] As a player, I want to preview my deck outside of combat so I can understand my strategy.
- [ ] As a player, I want some cards to be exhausted after use to encourage resource management.

## Epic: Character Progression
- [ ] As a player, I want to level up my character to unlock new passive abilities or stats.
- [ ] As a player, I want to improve my party by training, equipping, or leveling them up.
- [ ] As a player, I want to assign skill points or perks to specialize my build.

## Epic: World & Acts Structure
- [ ] As a player, I want to explore a metro-based hub world in Act 1 where I can gather supplies and allies.
- [ ] As a player, I want to explore the surface in Act 2 and face harsh environments and new enemies.
- [ ] As a player, I want to make choices that influence the story, NPCs, and party alignment.
- [ ] As a player, I want my decisions in Act 1 and 2 to impact what happens in Act 3.

## Epic: Survival Mechanics
- [ ] As a player, I want to manage a limited supply of food to heal and camp between fights.
- [ ] As a player, I want to find or scavenge ammo and supplies to survive the surface.
- [ ] As a player, I want to choose whether to help NPCs or keep resources for myself.

## Epic: UI & Feedback
- [ ] As a player, I want to see clear UI for my current hand of cards, AP, HP, and ammo.
- [ ] As a player, I want to view tooltips or details for each card in my hand.
- [ ] As a player, I want visual and audio feedback when cards are played or enemies are hit.
- [ ] As a player, I want the deck, inventory, and map to be accessible from a menu.