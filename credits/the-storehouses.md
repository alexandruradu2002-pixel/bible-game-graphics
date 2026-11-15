# Credits — chapter 15, The Storehouses (the "lpc" style)

The images in `graphics/the-storehouses/` are made by the chapter's tools (`unelte/lpc/granarele_*.py`) from free LPC packs
on OpenGameArt.org, from the layers of the LPC character generator and from drawings made by us, in the LPC manner.
The palm trees, the acacias, the bushes, the rocks and Jacob's tent are the ones from the prologue (`graphics/haran/`,
see `credits/haran.md`).

**What the licences require:** the names of the authors below and the links to their pages must appear on the Credits
page. Images made from CC-BY-SA material (the ground of the maps, the fields of grain, the sacks, the people, the ox,
the donkeys) remain CC-BY-SA 3.0: anyone may reuse them under the same terms.

## Our files and their sources

| Our file | Made from | Modified by us |
|---|---|---|
| `granarele_sol_egipt.png`, `granarele_sol_egipt_uscat.png`, `granarele_sol_cetate.png`, `granarele_sol_gosen.png` (the ground of the three maps) | [LPC] Terrains (`terrain-v7.png`): the sand, the black earth, the grass, the ploughed and the cracked earth, the roads, the flagstones; the water with its bank, the tufts, the flowers and the pebbles from `graphics/teren.png` (see `credits/shared.md`); the face of the walls from [LPC] Adobe Building Set | Yes: composed by us into a single image, by corners, with patches chosen by a noise pattern; the top of the walls drawn by us |
| `granarele_holda_verde.png`, `granarele_holda_copt.png` | [LPC] Farming tilesets (`youngwheat.png`, `wheat.png`) | Yes: stretched over 9 x 3 tiles |
| `granarele_holda_secerat.png`, `granarele_holda_uscat.png` | [LPC] Terrains (the ploughed earth, the cracked earth), in the shape of the field from [LPC] Farming tilesets | Yes: the stubble drawn by us |
| `granarele_sac.png`, `granarele_sac_grau.png`, `granarele_saci.png`, `granarele_trestie.png`, `granarele_barca.png` | [LPC] Farming tilesets (`farming_fishing.png`, `reed.png`) | Only cut out, shadow added |
| `granarele_sac_50.png` (the sacks in the piles and on the counter) | `granarele_sac.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redrawn), to half size |
| `granarele_sac_argint.png`, `granarele_sac_cupa.png` | The open sack from [LPC] Farming tilesets | Yes: the bundle of silver and the cup drawn by us |
| `granarele_casa_1.png`, `granarele_casa_2.png`, `granarele_taraba.png`, `granarele_umbrar.png`, `granarele_coloana.png` | [LPC] Adobe Building Set (`adobe-2.png`): the roof, the walls, the door, the window, the cloth awning, the portico pillar | Yes: arranged by us, the column painted with coloured bands |
| `granarele_granar.png`, `granarele_granar_1.png`, `granarele_granar_2.png`, `granarele_tejghea.png`, `granarele_piramida.png`, `granarele_masa_*.png`, `granarele_portie.png`, `granarele_scaun.png`, `granarele_lighean.png`, `granarele_cupa.png`, `granarele_argint.png`, `granarele_car_*.png` | Nothing from the packs: drawn by us (from code), in the LPC manner (dark outline, stepped shading, light from the top left) | Drawn by us |
| `granarele_cupa_mana.png` (the cup held in the hand) | `granarele_cupa.png` | Yes: scaled down by us with whole pixels, without a shadow (`unelte/lpc/in_mana.py`), 14 Nov 2026 |
| `granarele_bou.png` | LPC bull (`bull_1.png`) | Yes: recoloured reddish-brown (the ox that pulls the cart) |
| `granarele_asin.png`, `granarele_asin_*.png` | [LPC] Horses (`horse-gray_0.png`) | Yes: scaled down to three quarters, recoloured like a donkey, the ears lengthened; the blanket and the sack on its back drawn by us |
| `granarele_iosif.png`, `granarele_ruben.png` … `granarele_veniamin.png`, `granarele_iacov.png`, `granarele_ispravnic.png`, `granarele_scrib_*.png`, `granarele_slujitor_*.png`, `granarele_taran_*.png`, `granarele_vaduva.png`, `granarele_negustor.png`, `granarele_batran.png`, `granarele_vecin.png`, `granarele_strain_*.png`, `granarele_femeie_*.png` | Universal LPC Spritesheet Character Generator: the layers in the table below (walking and sitting in four directions) | Yes: recoloured with the generator's palettes (skin, hair, clothes, the gold of the coin necklace), the eyes made brown, the "breathing" frame, the sash painted on the sitting frames, the shadow |

## The packs

### [LPC] Terrains
- Authors: bluecarrot16, Lanea Zimmerman (Sharm), Daniel Eddeland (Daneeklu), Richard Kettering (Jetrel), Zachariah Husiar (Zabin), Hyptosis, Casper Nilsson, Buko Studios, Nushio, ZaPaper, billknye, William Thompson, caeles, Redshrike, Bertram, Rayane Félix (RayaneFLX).
- Licence: CC-BY-SA 4.0 / CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-terrains (the works it builds on are listed in `credits/shared.md`).

### [LPC] Adobe Building Set
- Author: Lanea Zimmerman (Sharm); contributor (paid for the commission): William.Thompsonj (William Thompson).
- Licence: CC-BY 4.0 / CC-BY 3.0 / GPL 3.0 / GPL 2.0 / OGA-BY 3.0. Required attribution: "Sharm" as author, "William.Thompsonj" as contributor, with a link to the page.
- https://opengameart.org/content/lpc-adobe-building-set

### [LPC] Farming tilesets, magic animations and UI elements
- Author: Daniel Eddeland.
- Licence: CC-BY-SA 3.0 / GPL 3.0. Required attribution: "Daniel Eddeland", with a link to the page.
- https://opengameart.org/content/lpc-farming-tilesets-magic-animations-and-ui-elements

### LPC bull (the ox)
- Author: Evert, from Daniel Eddeland's cow and Nila122's horns (LPC lizard headgear).
- Licence: CC-BY-SA 3.0 / GPL 3.0.
- https://opengameart.org/content/lpc-bull

### [LPC] Horses (the donkeys, from the grey horse)
- Author: bluecarrot16. Licence: CC-BY 3.0 / CC-BY-SA 3.0 / GPL 3.0 / GPL 2.0 / OGA-BY 3.0.
- https://opengameart.org/content/lpc-horses

### Universal LPC Spritesheet Character Generator (the chapter's people)
The generator: https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator (the authors of each layer,
from the generator's CREDITS.csv; the colour palettes are the generator's).

| Layer | Used for | Authors | Licences | Links |
|---|---|---|---|---|
| `beards/beard/5oclock_shadow/sit.png` | zabulon | JaidynReiman, Thane Brimhall (pennomi), laetissima | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-base-character-expressions |
| `beards/beard/5oclock_shadow/walk.png` | zabulon | JaidynReiman, Thane Brimhall (pennomi), laetissima | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-base-character-expressions |
| `beards/beard/basic/sit.png` | aser, dan, simeon | JaidynReiman, Carlo Enrico Victoria (Nemisys) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-white-beard |
| `beards/beard/basic/walk.png` | aser, dan, simeon, strain_1 | JaidynReiman, Carlo Enrico Victoria (Nemisys) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-white-beard |
| `beards/beard/medium/sit.png` | gad, iuda, ruben | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/medium/walk.png` | gad, iuda, negustor, ruben | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/trimmed/sit.png` | isahar, levi, neftali | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/trimmed/walk.png` | isahar, levi, neftali | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/winter/male/sit.png` | iacov | bluecarrot16 | CC0 | https://opengameart.org/content/lpc-santa |
| `beards/beard/winter/male/walk.png` | batran, iacov | bluecarrot16 | CC0 | https://opengameart.org/content/lpc-santa |
| `body/bodies/female/walk.png` | femeie_1, femeie_2, strain_2, vaduva | Benjamin K. Smith (BenCreating), bluecarrot16, TheraHedwig, Evert, MuffinElZangano, Durrani, Pierre Vigier (pvigier), ElizaWy, Matthew Krohn (makrohn), Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-ladies |
| `body/bodies/male/sit.png` | aser, dan, gad, iacov, iosif, isahar, iuda, levi, neftali, ruben, scrib_1, scrib_2, scrib_3, simeon, veniamin, zabulon | bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-male-jumping-animation-by-durrani |
| `body/bodies/male/walk.png` | aser, batran, dan, gad, iacov, iosif, isahar, ispravnic, iuda, levi, neftali, negustor, ruben, scrib_1, scrib_2, scrib_3, simeon, slujitor_1, slujitor_2, slujitor_3, strain_1, strain_3, taran_1, taran_2, taran_3, vecin, veniamin, zabulon | bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-male-jumping-animation-by-durrani |
| `feet/sandals/male/sit.png` | aser, dan, gad, iacov, iosif, isahar, iuda, levi, neftali, ruben, scrib_1, scrib_2, scrib_3, simeon, veniamin, zabulon | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `feet/sandals/male/walk.png` | aser, batran, dan, gad, iacov, iosif, isahar, ispravnic, iuda, levi, neftali, negustor, ruben, scrib_1, scrib_2, scrib_3, simeon, slujitor_1, slujitor_2, slujitor_3, strain_1, strain_3, taran_1, taran_2, taran_3, vecin, veniamin, zabulon | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `feet/sandals/thin/walk.png` | femeie_1, femeie_2, strain_2, vaduva | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `hair/balding/adult/sit.png` | ruben | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-hair |
| `hair/balding/adult/walk.png` | batran, ruben | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-hair |
| `hair/bedhead/adult/sit.png` | veniamin | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/bedhead/adult/walk.png` | veniamin | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/bob/adult/sit.png` | scrib_1, scrib_2, scrib_3 | ElizaWy, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-hair, https://github.com/ElizaWy/LPC/blob/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `hair/bob/adult/walk.png` | scrib_1, scrib_2, scrib_3 | ElizaWy, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-hair, https://github.com/ElizaWy/LPC/blob/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `hair/buzzcut/adult/sit.png` | gad | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-hair |
| `hair/buzzcut/adult/walk.png` | gad, slujitor_1, slujitor_3 | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-hair |
| `hair/curly_short/adult/sit.png` | neftali, simeon, zabulon | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `hair/curly_short/adult/walk.png` | neftali, simeon, zabulon | ElizaWy | OGA-BY 3.0 | https://opengameart.org/content/lpc-hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `hair/long/adult/sit.png` | aser, iacov, levi | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/long/adult/walk.png` | aser, iacov, levi, negustor, strain_1 | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/natural/adult/sit.png` | dan | ElizaWy, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-hair, https://github.com/ElizaWy/LPC/blob/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `hair/natural/adult/walk.png` | dan, strain_3, taran_2, vecin | ElizaWy, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-hair, https://github.com/ElizaWy/LPC/blob/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `hair/plain/adult/sit.png` | iosif, isahar, iuda | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/ponytail-and-plain-hairstyles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/plain/adult/walk.png` | iosif, isahar, iuda | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/ponytail-and-plain-hairstyles, https://opengameart.org/content/lpc-expanded-hair |
| `hat/cloth/hijab/thin/walk.png` | femeie_1, femeie_2, strain_2, vaduva | thecilekli | CC0 | https://opengameart.org/content/lpc-hijab, https://opengameart.org/content/lpc-expanded-hats-facial-helmets |
| `hat/headband/tied/adult/walk.png` | taran_1, taran_3 | Nila122 | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-lizard-headgear, https://opengameart.org/content/lpc-expanded-hats-facial-helmets |
| `head/heads/human/female/walk.png` | femeie_1, femeie_2, strain_2, vaduva | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/, https://opengameart.org/content/lpc-character-bases |
| `head/heads/human/male/sit.png` | aser, dan, gad, iosif, isahar, iuda, levi, neftali, ruben, scrib_1, scrib_2, scrib_3, simeon, veniamin, zabulon | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-character-bases |
| `head/heads/human/male/walk.png` | aser, dan, gad, iosif, isahar, ispravnic, iuda, levi, neftali, negustor, ruben, scrib_1, scrib_2, scrib_3, simeon, slujitor_1, slujitor_2, slujitor_3, strain_1, strain_3, taran_1, taran_2, taran_3, vecin, veniamin, zabulon | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-character-bases |
| `head/heads/human/male_elderly/sit.png` | iacov | Benjamin K. Smith (BenCreating), Eliza Wyatt (ElizaWy), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-revised-elders, https://opengameart.org/content/lpc-character-bases |
| `head/heads/human/male_elderly/walk.png` | batran, iacov | Benjamin K. Smith (BenCreating), Eliza Wyatt (ElizaWy), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-revised-elders, https://opengameart.org/content/lpc-character-bases |
| `legs/skirts/plain/male/sit.png` | aser, dan, gad, iacov, iosif, isahar, iuda, levi, neftali, ruben, scrib_1, scrib_2, scrib_3, simeon, veniamin, zabulon | bluecarrot16, Pierre Vigier (pvigier), Johannes Sjölund (wulax), Ahmad3366, JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `legs/skirts/plain/male/walk.png` | aser, batran, dan, gad, iacov, iosif, isahar, ispravnic, iuda, levi, neftali, negustor, ruben, scrib_1, scrib_2, scrib_3, simeon, slujitor_1, slujitor_2, slujitor_3, strain_1, strain_3, taran_1, taran_2, taran_3, vecin, veniamin, zabulon | bluecarrot16, Pierre Vigier (pvigier), Johannes Sjölund (wulax), Ahmad3366, JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `neck/necklace/beaded_large/male/sit.png` | iosif | bluecarrot16 | CC0 | https://opengameart.org/content/lpc-jewelry |
| `neck/necklace/beaded_large/male/walk.png` | iosif, negustor | bluecarrot16 | CC0 | https://opengameart.org/content/lpc-jewelry |
| `torso/clothes/longsleeve/longsleeve/male/sit.png` | aser, dan, gad, iacov, iosif, isahar, iuda, levi, neftali, ruben, simeon, veniamin, zabulon | JaidynReiman, Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-revised-character-basics |
| `torso/clothes/longsleeve/longsleeve/male/walk.png` | aser, batran, dan, gad, iacov, iosif, isahar, iuda, levi, neftali, negustor, ruben, simeon, strain_1, veniamin, zabulon | JaidynReiman, Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-revised-character-basics |
| `torso/clothes/robe/female/walk/blue.png` | strain_2 | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `torso/clothes/robe/female/walk/brown.png` | vaduva | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `torso/clothes/robe/female/walk/forest_green.png` | femeie_1 | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `torso/clothes/robe/female/walk/white.png` | femeie_2 | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `torso/clothes/shortsleeve/shortsleeve/male/sit.png` | scrib_1, scrib_2, scrib_3 | bluecarrot16, ElizaWy, JaidynReiman, Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, http://opengameart.org/content/lpc-revised-character-basics, http://opengameart.org/content/lpc-clothing-updates |
| `torso/clothes/shortsleeve/shortsleeve/male/walk.png` | ispravnic, scrib_1, scrib_2, scrib_3 | bluecarrot16, ElizaWy, JaidynReiman, Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, http://opengameart.org/content/lpc-revised-character-basics, http://opengameart.org/content/lpc-clothing-updates |
| `torso/clothes/sleeveless/sleeveless/male/walk/white.png` | taran_3, vecin | bluecarrot16, Matthew Krohn (makrohn), JaidynReiman, Marcel van de Steeg (MadMarcel), Nila122, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-female-orcogregoblintroll-base-walkcycle, https://opengameart.org/content/lpc-curly-hair-elven-ears-white-cape-with-blue-trim-and-more, https://opengameart.org/content/more-lpc-clothes-and-hair |
| `torso/waist/sash/male/walk/tan.png` | aser, batran, dan, gad, iacov, iosif, isahar, ispravnic, iuda, levi, neftali, negustor, ruben, scrib_1, scrib_2, scrib_3, simeon, slujitor_1, slujitor_2, slujitor_3, strain_1, strain_3, vecin, veniamin, zabulon | bluecarrot16, Nila122 | OGA-BY 3.0, GPL 2.0, GPL 3.0, CC-BY-SA 3.0 | https://opengameart.org/content/more-lpc-clothes-and-hair, https://opengameart.org/content/lpc-pirates |
