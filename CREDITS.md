# No One Else — credits

- **Three.js**, https://github.com/mrdoob/three.js — MIT license.
- **cannon-es**, https://github.com/pmndrs/cannon-es — MIT license; articulated ragdoll physics.
- **Lee Perry-Smith head scan**, distributed in the official Three.js examples: https://github.com/mrdoob/three.js/tree/dev/examples/models/gltf/LeePerrySmith. Used for the visitor. Its model and color/normal maps are embedded in the standalone HTML; development assets live in public/models/.
- **DM Sans** — Colophon Foundry, Jonny Pinhorn and Indian Type Foundry; SIL Open Font License 1.1, via @fontsource/dm-sans.
- **Cormorant Garamond** — Christian Thalmann; SIL Open Font License 1.1, via @fontsource/cormorant-garamond.
- Apartment, limited city view, hooded actor, clothing, skeletal rigging, authored reaction layers, story, synthesized rain/knocks and combat audio created for this prototype.
- Optional English speech uses the browser's native speech synthesis and installed voices; no voice recording is bundled.

## Human motion capture

The data used in this project was obtained from mocap.cs.cmu.edu. The database was created with funding from NSF EIA-0196217. CMU permits research and commercial use worldwide. Bruce Hahne’s BVH conversion places no additional restrictions. The full original usage statement is in public/animations/CMU-LICENSE.txt and embedded in the standalone HTML.

Recorded walk, boxing guard, left jab and right cross are retargeted to the game’s anatomical skeleton. The idle and slow-walk sources are retained in the baked dataset but are not selected at runtime. Walking uses reduced body sway and a shorter stride; standing, the finishing hook and small reaction layers are authored additions. Pinned source URLs, SHA-256 hashes, source frame ranges and recording provenance are stored in src/motion-data.json. The source conversion mirror is https://github.com/una-dinosauria/cmu-mocap.
