# Clown Noise Board

A phone-friendly soundboard of clown and circus noises. Tap a tile to play its sound. It works offline after the first visit and can be added to your home screen.

**Live:** https://caosowl.github.io/clown-noises/

## Changing a sound for everyone

Every sound is a file in `sounds/`, named after its tile id (for example `sounds/honk.m4a` for "Popi popi"). To change one, replace the file. To add a new file under a different name, list it in `sounds/manifest.json`. Pushing to `main` redeploys the site.

Tile ids: `honk`, `laugh`, `giggle`, `whoopee`, `boing`, `spring`, `slide`, `banjo`, `fail`, `pop`, `march`, `roll`, `crash`, `tada`, `applause`, `bell`, `swell`, `cannon`, `fireworks`, `popper`, `gong`.

`whoopee` and `slide` have no file yet, so the page generates them in code. Add `sounds/whoopee.m4a` or `sounds/slide.m4a`, plus a line in the manifest, to replace them.

## Changing a sound on one device

In the app, tap **Swap sounds**, then a tile, and pick an audio file or a short video. The sound is kept in that browser only.

## Credits

- Clown horn ("free sound eff") and circus music ("Gaming Sound FX"): supplied by the repo owner.
- Laughs, boing, banjo, fail, drum roll, snare crash, ta-da: Oculus Audio Pack 1 by Meta, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- Applause, fireworks, popper, pop: sfx-kit by Wyzowl, CC0.
- Spring, gong: rubberduck on OpenGameArt, CC0. Cannon: Thimras on OpenGameArt, CC0.
- Cymbal swell: rubberduckie on Freesound, CC0. Ship's bell: Nigel K, public domain.
- Fallback organ version of "Entry of the Gladiators" (Julius Fučík, 1897): note data from the Fairy Lights mod by Paul Fulham (MIT).
