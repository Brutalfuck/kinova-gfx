# Kinova GFX — Server (GOKU style folders)

## Naya pack add karna / pak daalna:
1. `configs/` mein folder mein jao (jaise `2_60fps`)
2. "Add file" -> "Upload files" -> apni .pak file daalo
   (naam: game_patch.pak — FPS wale folder mein: game_patch_4.5.0.21377.pak)
3. Bas! App mein download button kaam karne lagega

## Image badalni ho:
Usi folder mein nayi image `image.png` naam se upload karo — replace ho jayegi.

## Poori nayi pack banana ho:
1. `configs/` mein "Create new file" -> naam: `8_mera_pack/README.txt` -> commit (folder ban gaya)
2. Us folder mein `image.png` aur `game_patch.pak` upload karo
3. `gfx_configs.json` mein ek entry jodo (aakhri wali copy karke badlo)

## Baaki files:
app_config.json (telegram/title), domain_filters.json (370 domains),
filters.json (VPN), app_updates.json (update), broadcasts.json (announcement)
