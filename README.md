# QIX

A remake of Taito's 1981 arcade game Qix, in one HTML file. It has a neon look, combos and a daily challenge, and the original rules are unchanged.

**Play:** https://nightowlcoder.kovadj.dev/qix/

## How to play

Claim 75% of the screen by drawing lines out from the border and closing them back onto it. The Qix roams the open area and kills you if it touches the line you are drawing. The Sparx run along the border and kill you if they reach you there.

| Key | Action |
|---|---|
| Arrows | Move |
| Space (hold) | Draw fast |
| Shift (hold) | Draw slow, worth 2× points |
| Enter | Play |
| D | Daily challenge |
| P | Pause |
| C / R / N / M | CRT filter / death replay / music / sound |
| S | Share your score (after game over) |

On a phone, drag on the board to steer and hold DRAW or SLOW to cut.

## Rules

- **Fuse:** if you stop partway through a line, a spark burns along it toward you.
- **Combo:** each box you close within 5 seconds of the last one raises the combo, up to ×5.
- **Bonuses:** every 1% claimed over 75% is worth 1,000 points. Reaching 90% earns a TRAPPED! bonus.
- **Two Qix:** from level 3 there are two. Cutting them into separate areas clears the level and raises your score multiplier.
- **Cage:** closing a box over a Sparx cages it for 5 seconds.
- **Green orb:** claim it to turn the Sparx into slow zombies for 8 seconds.
- **Death replay:** when you die, the game replays your last 3 seconds in slow motion.

Sound and music are generated in code with WebAudio. There are no dependencies and no build step.
