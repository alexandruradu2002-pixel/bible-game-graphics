# Credits — chapter 12 (Jacob)

The drawings in `graphics/jacob/`. The chapter also uses the rocks and bushes of the prologue (`graphics/haran/`), with their authors in
`credits/haran.md`. The authors below must appear on the Credits screen. The images made from
CC-BY-SA material remain CC-BY-SA 3.0: anyone may reuse them under the same terms.

## The files and their sources

| Our file | Made from | Modified by us |
|---|---|---|
| `iacov_teren.png` (the ground of the camp at Beersheba and of the hills at Bethel: dark earth, clay, trodden earth, cracked earth, gravel, dry grass, grass, flagstones, dark rock, grey rock) | [LPC] Terrains (`terrain-v7.png`): the types Dirt_Dark, Dirt_Brown, Dirt_Tan, Earth_Cracked, Gravel_1, Grass_Dead, Grass_Light, Stone_Tan, Rock_Dark, Rock_Gray; [LPC] Flowers / Plants (`plants.png`): tufts and flowers; LPC Base Assets (`mountains.png`): pebbles | Yes: the pieces rearranged into rows (the edges by corners); the dark earth made grey-brown, the dry grass the colour of straw, the green grass muted, the tufts recoloured dry yellow; the gravel redrawn by us on 28 Oct 2026, in the LPC manner (`unelte/lpc/piatra_seaca.py`), in place of the one from the pack; the dark rock and the grey rock (rows 8 and 9) and the pebbles (row 10) redrawn by us on 28 Oct 2026, in the manner of the walls in The Brothers (`unelte/lpc/pietre_rotunde.py`) |
| `iacov_iacov.png`, `iacov_iacov_toiag.png`, `iacov_iacov_haine.png` (Jacob; with a staff and lying down; in Esau's garment, with the young goat skins on his hands and on his neck), `iacov_isav.png`, `iacov_isaac.png`, `iacov_isaac_culcat.png`, `iacov_isaac_sezand.png`, `iacov_rebeca.png`, `iacov_debora.png`, `iacov_sluga.png`, `iacov_inger_1.png`, `iacov_inger_2.png` | Universal LPC Spritesheet Character Generator: the layers in the table below (walking in four directions) | Yes: recoloured (Jacob's olive-green garment, Esau's cherry-red garment with a golden sash, Isaac's beige tunic, Rebekah's light-blue robe and white veil, the warm white of the angels; Esau's reddish hair, Isaac's white hair, Rebekah's black hair with grey strands), brown eyes (Isaac's closed), the "breathing" frame, the shadow; the fur drawn by us (Esau's tunic, the young goat skins, the hair on Esau's arms), Esau's bow on his back drawn by us, Isaac lying under a blanket and Isaac sitting drawn by us from the walking frames; the staff without the blue stone at its tip |
| `iacov_capra_1..3.png`, `iacov_ied_1..3.png` | [LPC] Goat (`goat.png`) | Yes: recoloured (black, brown, grey), scaled down (the colours snapped back to their palette, the outline redone), the young goats smaller and with white spots, the grazing used as the standing animation, the shadow |
| `iacov_ied_1..3_85.png` (the young goat carried in the arms) | `iacov_ied_1..3.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redone), to 85% |
| `iacov_cort_isaac.png`, `iacov_cort_rebeca.png`, `iacov_cort_iacov.png`, `iacov_cort_isav.png`, `iacov_cort_slugi.png` | The prologue's tents (`graphics/haran/haran_cort_*.png`, drawn by us) | Yes: Isaac's tent widened by one panel, woven strips in colours, Rebekah's tent made lighter, Esau's with two hides at the entrance |
| `iacov_tamarisc_1.png`, `iacov_tamarisc_2.png` (the tamarisks of the grove at Beersheba) | [LPC] Trees (`trees-pale.png`) | Yes: the foliage recoloured grey-green, like a tamarisk |
| `iacov_vatra.png`, `iacov_oala_0..3.png`, `iacov_vreascuri.png`, `iacov_vreascuri_brat.png`, `iacov_fantana.png`, `iacov_jgheab.png`, `iacov_gard_o.png`, `iacov_gard_v.png`, `iacov_lada.png`, `iacov_lada_goala.png`, `iacov_haina.png`, `iacov_mancare.png`, `iacov_ulcior_vin.png`, `iacov_pat.png`, `iacov_opait.png`, `iacov_masuta.png`, `iacov_covor.png`, `iacov_piatra_1..3.png`, `iacov_stalp.png`, `iacov_untdelemn.png`, `iacov_semne.png` (the ear, the hand, the nose, the cat's step, the garment, the skin, the spoon) | Nothing from the packs | Drawn by us (from code), in the LPC manner: dark outline, stepped shading, light from the top left; the hearth, the well and the stones (`iacov_piatra_1..3.png`) redrawn by us on 28 Oct 2026, in the manner of the walls in The Brothers (`unelte/lpc/pietre_rotunde.py`) |
| `iacov_cort_interior.png` (Isaac's tent from the inside), `iacov_vis.png` (the dream: the ladder, the sky, the clouds, the landings) | Nothing from the packs | Drawn by us (from code) |

The light of the oil lamp, the fire under the pot, the footstep circles, Isaac's hearing circle, the distant view with Esau, the glow of the angels
and the stars at Bethel are made from code. The sounds (`sunete/iacov/`) are synthesised by us
(`unelte/sunete_iacov.py`), with no third-party files.

## The packs

### Universal LPC Spritesheet Character Generator (the chapter's people)
The generator: https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator (the authors of each layer,
from the generator's CREDITS.csv; the colour palettes are the generator's).

| Layer | Used for | Authors | Licences | Links |
|---|---|---|---|---|
| `body/bodies/male/walk.png` | Jacob, Esau, Isaac, the servant, the angels | bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-male-jumping-animation-by-durrani |
| `body/bodies/female/walk.png` | Rebekah, Deborah | Benjamin K. Smith (BenCreating), bluecarrot16, TheraHedwig, Evert, MuffinElZangano, Durrani, Pierre Vigier (pvigier), ElizaWy, Matthew Krohn (makrohn), Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-ladies |
| `head/heads/human/male/walk.png` | Jacob, Esau, the servant, the angels | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-character-bases |
| `head/heads/human/male_elderly/walk.png` | Isaac | Benjamin K. Smith (BenCreating), Eliza Wyatt (ElizaWy), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY 3.0 | https://opengameart.org/content/lpc-revised-elders, https://opengameart.org/content/lpc-character-bases |
| `head/heads/human/female/walk.png` | Rebekah, Deborah | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases |
| `hair/plain/adult/walk.png` | Jacob, the servant, one angel | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/ponytail-and-plain-hairstyles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/long/adult/walk.png` | Isaac, one angel | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-expanded-hair |
| `hair/long_straight/adult/walk.png` | Rebekah, Deborah | JaidynReiman, thecilekli, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-long-straight-hair-with-12-colors |
| `hair/unkempt/adult/walk.png` | Esau | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-expanded-hair |
| `beards/beard/basic/walk.png` | Esau | JaidynReiman, Carlo Enrico Victoria (Nemisys) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-white-beard |
| `beards/beard/medium/walk.png` | the servant | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/winter/male/walk.png` | Isaac | bluecarrot16 | CC0 | https://opengameart.org/content/lpc-santa |
| `torso/clothes/longsleeve/longsleeve/male/walk.png` | Jacob, Isaac, the servant, one angel (and the shape of Esau's fur) | JaidynReiman, Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, http://opengameart.org/content/lpc-clothing-updates |
| `torso/clothes/robe/female/walk/white.png` | Rebekah, Deborah, one angel | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `legs/skirts/plain/male/walk.png` | Jacob, Isaac, the servant, one angel (and the shape of Esau's fur) | bluecarrot16, Pierre Vigier (pvigier), Johannes Sjölund (wulax), Ahmad3366, JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `torso/waist/sash/male/walk.png` | Jacob, Isaac, the angels | bluecarrot16, Nila122 | OGA-BY 3.0, GPL 2.0, GPL 3.0, CC-BY-SA 3.0 | https://opengameart.org/content/more-lpc-clothes-and-hair |
| `feet/sandals/male/walk.png` | Jacob, Esau, Isaac, the servant, one angel | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `feet/sandals/thin/walk.png` | Rebekah, Deborah | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `hat/cloth/hijab/thin/walk.png` | Rebekah, Deborah | thecilekli | CC0 | https://opengameart.org/content/lpc-hijab |
| `weapon/magic/simple/` | the staffs of Jacob, Isaac and the servant | bluecarrot16, Dr. Jamgo | CC0 | https://opengameart.org/content/lpc-simple-staff |

### [LPC] Goat
- Author: bluecarrot16. Licence: CC-BY 3.0 / GPL 3.0 / GPL 2.0.
- https://opengameart.org/content/lpc-goat

### [LPC] Terrains
- Authors: bluecarrot16, Lanea Zimmerman (Sharm), Daniel Eddeland (Daneeklu), Richard Kettering (Jetrel), Zachariah Husiar (Zabin), Hyptosis, Casper Nilsson, Buko Studios, Nushio, ZaPaper, billknye, William Thompson, caeles, Redshrike, Bertram, Rayane Félix (RayaneFLX).
- Licence: CC-BY-SA 4.0 / CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-terrains (the works it builds on are in `credits/shared.md`)

### [LPC] Trees
- Authors and licence: as in `credits/shared.md` (CC-BY-SA 3.0). https://opengameart.org/content/lpc-trees

### [LPC] Flowers / Plants / Fungi / Wood
- Authors and licence: as in `credits/shared.md` (CC-BY-SA 3.0). https://opengameart.org/content/lpc-flowers-plants-fungi-wood

### Liberated Pixel Cup (LPC) Base Assets
- `mountains.png`: Lanea Zimmerman (Sharm). Licence: CC-BY-SA 3.0 / GPL 3.0 (Sharm's works are also OGA-BY 3.0).
- https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles
