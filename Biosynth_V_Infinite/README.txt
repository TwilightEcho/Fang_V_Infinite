Fang V Infinite - reconstructed BN baseline

Included:
- Android Toolkit CBM
- Android Toolkit (Extended) included bionic menu option
- QSR-0P Quantum Reactor CBM
- Installable CBM items
- FVI_bionics test item group
- Fox Ears CBM (toggleable overlay, +1 PER, small head protection, cancels BADHEARING/DEAF)
- Fox Tail CBM (toggleable overlay, small torso protection)
- UndeadPeople-compatible tileset overlay definition
- gfx/FVI_overlays_realistic.png sprite sheet placeholder/current supplied sheet

Fox overlay IDs used by the tileset:
- overlay_mutation_bio_fox_ears_cbm -> sprite index 0, sprite_offset_y -16
- overlay_mutation_bio_fox_tail_cbm -> sprite index 1, sprite_offset_y 16, rotates true

Notes:
- This rebuild uses BN-style bionic fields such as stat_bonus, bash_protec, cut_protec, env_protec, occupied_bodyparts, and BIONIC_TOGGLED.
- If you replace the sprite sheet, keep it at gfx/FVI_overlays_realistic.png or update fvi_overlays_realistic_tileset.json.
