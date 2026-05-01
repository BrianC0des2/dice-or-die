# Dice or Die
A 2-player board game built in Java with a graphical user interface.

## Team Members
- Bryan P. Saavedra
- Landis Angelo J. Landis
- Datu Johari I. Esmail

## Description
Dice or Die is a 2-player board game where players take turns rolling a dice 
and moving across a 64-tile board. Each tile carries a different effect that 
can help or hinder their progress. The board is randomized every game so no 
two playthroughs are the same.

## How to Win
- Be the first player to reach **tile 64**, or
- Be the **last player with lives remaining**

Each player starts with **3 life bars**. Losing all 3 lives means the opponent 
wins regardless of board position.

## Tile Types
| Tile | Effect |
|------|--------|
| Safe | Nothing happens, free turn |
| Forward | Moves the player ahead by a set number of tiles |
| Backward | Moves the player back by a set number of tiles |
| Lava | Costs the player 1 life bar |
| Shield | Grants one-time protection against the next Lava tile |
| Extra Life | Restores 1 life bar (capped at 3). If already full, converts to a Shield |
| Swap | Forces both players to exchange board positions (mandatory) |
| Freeze | Player skips their next turn |
| Gamble | Roll again — even number moves forward, odd moves backward |

## Rules
1. Players decide who goes first by each rolling the dice — highest roll goes first
2. Players alternate turns, no skipping
3. Roll a standard 6-sided dice each turn
4. Move forward by the number rolled
5. The tile landed on triggers its effect immediately
6. Landing on a Forward, Backward, or Gamble tile may chain into another tile effect
7. Shield blocks the next Lava tile only — consumed after one use, cannot be stacked
8. Players cannot go below tile 1 regardless of backward movement
9. Tile 1 and tile 64 are always Safe tiles
10. The board layout is randomized at the start of every game

## Screenshots
