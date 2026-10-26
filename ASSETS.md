# Pixel lab assets

- Research room, typing trainer sprite sheet and forest landscape: created for this profile using the built-in imagegen tool, following the approved concept. Original generated plates and exact prompts are retained in the local project backup.
- `assets/lab/lab-animated.gif`: 120 frames, 12-second loop, 1200 × 488. Independent trainer typing/blink poses, Pikachu and Bulbasaur source animations, steam and light particles. Fixed palette with transparent frame deltas keeps the background steady and the file around 1 MB.
- Pokémon animation source: [PokéAPI sprites](https://github.com/PokeAPI/sprites), Generation V / Black & White animated sprites. Pikachu #25 and Bulbasaur #1. Original source GIFs remain under `assets/pokemon/`. Pokémon names and characters belong to their respective owners.
- Trainer card, quest menu, project cards and map entrance are self-contained SVGs without scripts or external image dependencies. The scene and trainer artwork are embedded. Motion includes a blinking/typing trainer, gentle quest chevrons, card sparkles, a rocking Poké Ball, moving map arrow and water glints.
- Small-screen variants enlarge the trainer and quest labels; project cards wrap naturally at narrow widths.
- The hero includes a static poster selected when the viewer requests `prefers-reduced-motion`.
- Contribution snake: [Platane/snk](https://github.com/Platane/snk), generated from the actual `cmerber` contribution data by the original workflow. The displayed contribution grid is not fabricated artwork.

The pre-redesign profile is recoverable via [PROFILE_BACKUP.md](./PROFILE_BACKUP.md).
