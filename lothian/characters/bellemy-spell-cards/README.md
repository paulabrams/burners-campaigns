# Bellemy Wrenfeather — spell cards

Printable spell cards at true **MTG / poker size (2.5" × 3.5")** for Bellemy’s Burners hand. Letter prints six cards per page at 100%; this kit spills to a second page.

Reusable kit / how-to for the next caster: [`rpg-original/burners/cards/`](../../../../burners/cards/).

## What’s in the deck

| Card | School | Notes |
| --- | --- | --- |
| Read Magic | Sorcerie 1 | Always known |
| Visual Illusion | Illusione 1 | Lasting |
| Auditory Illusion | Illusione 1 | |
| Bewitch | Illusione 1 | Control — Defend vs cast total |
| Web Weave | Elementale 1 | Lasting until burned |
| Fog Cloud | Elementale 1 | Fades in one turn |
| Undead Warding Glyph | — | Session 0 |
| Card back | — | Face-down = burned |
| Table Zones | — | Reminder card (optional) |

Spell text is from Burners Spells. Hand rules are from Burners Sorcerie.

## Print

1. Open `index.html` in a browser (Chrome or Safari).
2. **File → Print** (or ⌘P).
3. Paper: **US Letter**.
4. Scale: **Actual size** / **100%** (not Fit to Page).
5. Margins: default is fine; the sheet already pads.
6. Color: **Black & white** is intended — line art only.
7. Prefer **cardstock** (65–110 lb cover). Plain paper works for a test cut first.

Cut on the outer black border of each card. Use a ruler and craft knife, or scissors.

### Optional double-sided backs

The shared **card back** prints once on the sheet. To sleeve with a back:

- Print a second Letter sheet with only backs (duplicate the `.card.back` block in HTML as needed), or
- Glue / tape the cut back onto each face after cutting.

For play at the table, a single face-up hand is enough: when burned, flip face-down — they all look blank the same way.

## At the table

- Start with all five spell faces **ready** (face-up, upright).
- **Cast** → rotate 90° (tap). Instant goes to discard; lasting stays **in play** until the effect ends, then discard.
- **Burn** a ready card for recast / copy → flip it face-down (exile). Burned cards still count against hand size.
- After **8 hours sleep**, recover up to your **Sorcerie** in cards (Bellemy: 1).

## MTG → Burners (for Alek)

| Magic | Burners |
| --- | --- |
| Your hand | Cards ready to cast |
| Mana cost | Spell level — spend at least that many Fuel dice in combat |
| Cast spell | One Action; pay Fuel; roll for cast total |
| Tap | Rotate the card — you’ve spent that casting |
| Permanent / duration | Lasting — leave the card in play while it runs |
| Exile | Burn — flip face-down; gone until sleep recovery |
| Graveyard | Discard (tapped / used, but not burned) |
| Deck / library | Spellbook (known spells); redraw from it on rest / swaps |
| Flash / sorcery timing | Combat cast is your Action; Ward is free reaction vs hostile magic |

Burning is the tight choice: every card is both a spell and fuel. You can’t keep both.

## Tweaking

Edit `index.html` to add a face when Bellemy learns a new spell. Keep the art box ~1.15" tall if you tape a hand-drawn sketch over the SVG glyph.
