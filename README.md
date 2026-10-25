# Flappy J

A flappy-bird shooter starring **J**, the [Bluejay](https://getbluejay.ai) mascot. Fly J through four fur-covered worlds, zap the glitches swarming in, collect feathers to power up your shots, and take down voice-AI bosses.

Built by [Abdullah Sultan](https://www.amsultan.site).

## Play

[Play Flappy J](https://flappyjay.grok.me)

It's a static site with no build step. To run the source locally:

```bash
python3 -m http.server 8000
```

## Controls

| Action | Desktop | Mobile |
|---|---|---|
| Flap | Space, W or ↑ | Tap anywhere, or the Flap button |
| Shoot | Automatic | Automatic |
| Voice blast (when charged) | X or Shift | Blast button |
| Pause | P or Esc | Pause button |
| Mute | M | Speaker button |

## How it plays

- **Worlds.** Cotton Sky, Glass Lake, Fur Dunes and Dream Clouds rotate every 8 gates.
- **Glitches.** Mites, wisps, darts (watch for the `!` warning) and turrets that fire back.
- **Feathers.** Each run starts at power level 1, and collecting feathers raises it:

  | Level | Feathers | Effect |
  |---|---|---|
  | 1 | 0 | Single pulse |
  | 2 | 10 | Faster fire |
  | 3 | 25 | Twin pulses |
  | 4 | 45 | Double damage |
  | 5 | 70 | Three-way spread |

- **Bosses.** The first appears at gate 12, then one every 16 gates:
  - **Static** fires rings, bursts and spirals.
  - **Feedback** sends sound waves you have to fly through the gap in.
  - **Echo** records your flight path and fires it back at you.
- **Power-ups.** Slow-mo, triple shot, shield and an instant blast charge.
- **Wardrobe.** Five of J's outfits, all free to wear.

## Files

```
index.html   the whole game (HTML, CSS and canvas JS)
assets/      world backdrops, fur textures and J cutouts (WebP)
fonts/       Terrane Serif Bold and Haffer (Bluejay brand fonts)
```

## Credits

J, the world art, the logo, the feature icons and the fonts all come from the Bluejay brand kit and belong to Bluejay Intelligence. Terrane Serif is by Production Type and Haffer is by Displaay; both are commercially licensed. The code is by Abdullah Sultan.
