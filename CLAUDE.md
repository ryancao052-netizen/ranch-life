# CLAUDE.md

## Project Overview
This is a horse racing game focused on progression, horse management, and stat-based race outcomes.

Core loop:
- Buy horse → Race → Earn money → Upgrade / buy better horses → Progress to harder races

Current focus:
- Systems first
- Visuals are NOT a priority right now

## Horse Stats
Every horse must have and display:
- Speed
- Stamina
- Health

These must be visible:
- In horse menu
- When purchasing horses

## Race Difficulty Scaling
- Races must get progressively harder
- Scaling should be slightly curved, not linear
- Early races should be forgiving
- Mid-game should ramp up
- Late-game should require strong horses

Avoid:
- sudden spikes
- flat progression
- randomness dominating results

## Retired Horses
- No upkeep
- Removed from gameplay systems
- Exist only for record/history
- Continue aging passively

Do not:
- charge upkeep for retired horses
- allow retired horses to race again

## UI Rules
- Prioritize clarity
- Show all 3 stats in relevant menus
- Make race outcomes understandable

## Code Rules
- Keep systems modular
- Keep UI separate from game logic
- Make incremental changes
- Do not add new systems unless asked
