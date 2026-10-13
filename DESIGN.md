# Fresno Airsoft Arena: Design Language

**Concept:** *The range card.* The page reads like a printed field sheet: sand paper, olive and black ink, ruled lines. It has a milsim mood but stays dry: no glow, no HUD overlays, no fake grid references or "mission" copy.
**Audience:** Central Valley walk-on players, first-timers and parents.
**Mood:** Plain-spoken, practical and a little dusty.

## 1. Principles

1. **Paper, not a screen.** The site is light. One dark olive band (Field rules) gives the page its weight.
2. **Colour has jobs.** Logo red (`--red`) marks actions and "Free". Logo blue (`--blue`) marks inline links and focus. Olive (`--od`) is the emphasis word in headlines. Nothing else gets colour.
3. **Real ground, real photos.** Use the field's own photos and name the real features: the bus, the plywood town, the rubble line, the orchard boundary.
4. **Hairlines, square corners.** No shadows, radii, gradients or glass. The logo roundel is the only circle.

## 2. Tokens

| Token | Hex | Use |
|---|---|---|
| `--paper` | `#ECE6D6` | Page |
| `--paper-2` | `#E3DCC8` | Alternate section (The ground) |
| `--card` | `#F4EFE3` | Visit card |
| `--ink` | `#1C1E17` | Text, rules, footer |
| `--ink-2` | `#3E4135` | Body copy |
| `--mute` | `#6D6C5C` | Labels |
| `--line` | `#C8BFA6` | Hairlines |
| `--od` | `#3B4527` | Headline emphasis, zone numerals |
| `--od-deep` | `#252B19` | Rules band |
| `--red` | `#B3202A` | Primary CTA, "Free" |
| `--blue` | `#1E3478` | Links, focus ring |

## 3. Type

| Role | Family | Treatment |
|---|---|---|
| Wordmark, zone numerals, hero tile numerals | **Big Shoulders Stencil** 800 | The only stencil use, kept small |
| Display | **Big Shoulders** 700/900 | UPPERCASE, line-height .86–.9 |
| Body | **Public Sans** 400–700 | 16px / 1.6 |
| Labels, data | **IBM Plex Mono** 400/500 | 12px UPPERCASE, .08em tracking |

## 4. Signature components

- **Hero:** the H1 is three imperatives ("Take the bus. / Clear the town. / Hold the rubble.") set at 112px, with a plain introductory paragraph and CTAs beside it. Below that is a tick-mark ruler, then a full-width photo mosaic (one large tile, two stacked) at ~80vh. No background image, no text over a photo.
- **Milsim marks (keep to these):** viewfinder corner brackets on hero tiles, a faint centre crosshair on the large tile only, stencil zone numerals 01–03, "Objective · ___" mono tags, the real coordinates (36°41′55″N 120°01′56″W) and 24-hour gate times in the meta line.
- **Brief bar:** a four-column ruled strip under the mosaic: walk-on days, "first game free", rentals and location.
- **Section header:** a 200px mono label with a 2px ink top rule, then the H2.
- **Steps line:** five steps on a single ink rule with square markers. The last marker is red.
- **Shot:** a photo with a 1px border and a two-sided mono caption below.
- **Rates table:** condensed item names with a body-copy sub-line, and big right-aligned prices.

## 5. Don'ts

- No neon, glow, scanlines, HUD brackets or night-vision green.
- No "OPERATION ___", callsigns, coordinates or redacted-document gimmicks.
- No stock "soldier silhouette at sunset" photos. If stock is needed, use daylight shots of dirt fields.
- No invented reviews or ratings.
