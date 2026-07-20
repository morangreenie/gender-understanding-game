# GenderQuest: Prism Arena

GenderQuest is a private, child-friendly browser action game guided by the original Poison, Love, and Ghoul characters. The player dashes around a colourful arena, collects clue orbs, dodges harmless bumpers, uses a character ability, rescues creature friends, and clears the Mix-Up Cloud across three missions.

The game teaches four distinctions:

1. body and sex traits;
2. the gender category a person says fits them best;
3. gender expression; and
4. interests, personality, and stereotype-breaking (gender nonconformity).

## Play

Open the hosted game in Chrome:

**https://morangreenie.github.io/gender-understanding-game/**

Controls:

- Computer: arrow keys or WASD; Space for the hero ability; P to pause.
- Phone or tablet: large movement joystick and ability button.
- Low-action option: enable **Show tap answers** to complete the same 12 encounters without joystick precision.
- Calm Mode removes the clock. The ordinary clock also never causes failure or lost progress.

There are no accounts, advertisements, analytics, cookies, chat, or external services. The player's first name and progress remain in that browser's local storage.

## Clinical-use note

The game is an educational conversation aid, not an assessment and not a way to decide a child's identity. It never asks the player to disclose or label their own identity. Incorrect choices lose no points and lead to a brief hint and immediate retry.

The identity wording is **the gender category that fits a person best**, while interests, clothing, and personality are taught as separate information. The fictional scenarios use explicit clues rather than asking the player to guess a body or identity from appearance.

## Technical note

The app is a static GitHub Pages site: `index.html` contains the interface, styles, game logic, sounds, and Canvas arena, while the approved Poison-Love-Ghoul artwork is stored in `assets/poison-love-ghoul-trio.webp`. It has no build step and works offline after the two files have loaded.
