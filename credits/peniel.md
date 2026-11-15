# Credits — chapter 13 (Peniel)

The drawings in `graphics/peniel/`, used by chapter 13 (Genesis 29–33). They are cut out, recoloured or composed from
LPC packs on OpenGameArt.org and from the LPC character generator; some are drawn by us, in the LPC manner
(dark outline, stepped shading, light from the top left). Images made from CC-BY-SA material remain CC-BY-SA,
free for others as well. The chapter also uses, as they are, drawings from other chapters: the sheepfold walls, the rocks and
the pebbles from chapter 3, the mountain rocks from chapter 5, the tents, the bushes, the hearth and the lying sheep from the
prologue, the reeds, the bucket and the boulders from chapter 7, the sheep, the lamb, the goat and the wolf (their authors are in
the files of those chapters and in `credits/shared.md`).

## The files and their sources

| Our file | Made from | Modified by us |
|---|---|---|
| `peniel_iacov.png`, `peniel_rahila.png`, `peniel_lia.png`, `peniel_laban.png`, `peniel_pastor_1.png`, `peniel_pastor_2.png`, `peniel_bilha.png`, `peniel_zilpa.png`, `peniel_isav.png`, `peniel_om_isav_1.png`, `peniel_om_isav_2.png`, `peniel_copil_1..3.png` | Universal LPC Spritesheet Character Generator (the walking layers and, for Jacob, the ones with the hands raised in front, "spellcast") | Yes: recoloured (Jacob with dark chestnut hair, a short beard, an olive-green tunic and a brown sash; Rachel with a pomegranate-coloured robe; Leah with a blue-green robe and a blue veil; Laban with a grey beard and a purplish garment; Esau red-haired, with a fur garment and a quiver), the "breathing" frame, the shadow; for Jacob, the wrestling rows (hands raised, the head taken from the standing frame) and the bowing down to the ground (kneeling and with the forehead to the ground, drawn by us from the standing frames); for Rachel, sitting on the pack saddle |
| `peniel_copil_1..3_62.png`, `peniel_copil_1..3_50.png` (Jacob's children) | `peniel_copil_1..3.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is the pixel of the large drawing beneath it, the outline redone), to 62% and 50% |
| `peniel_umbra.png` (the One who wrestles with Jacob) | The same generator: body, head, shirt, skirt, sandals, the walking and "spellcast" frames | Yes: all of it made into a blue-black shadow, without colours and without a face |
| `peniel_oaie_pestrita.png`, `peniel_oaie_neagra.png`, `peniel_oaie_tunsa.png`, `peniel_miel_pestrit.png`, `peniel_miel_negru.png` | The game's sheep and lamb (LPC style farm animals, `sheep_walk.png`, `sheep_eat.png`) | Yes: large dark brown spots (the speckled ones), the black wool, the shorn sheep (pinkish skin, short wool, a thinner body) |
| `peniel_miel_pestrit_80.png`, `peniel_miel_negru_80.png` (the weak lambs) | `peniel_miel_pestrit.png`, `peniel_miel_negru.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redone), to 80% |
| `peniel_capra.png` | The goat of chapter 7 ([LPC] Goat, `goat.png`) | Yes: white spots (a piebald goat) |
| `peniel_camila.png` (the camels at Gilead and the ones given to Esau, since 14 Nov 2026) | Nothing from the packs: the camel from The Well (`fantana_camila_1.png`), copied | Drawn by us (`unelte/lpc/fantana_camila.py`); here only the standing and walking rows. Until 14 Nov 2026 it was the llama from LPC style farm animals, with a hump drawn by us |
| `peniel_caine.png` (the flock's dog) | [LPC] bears, deer, lions and more (`dog, shiba (Sevarihk).png`) | Yes: recoloured as a sheepdog (yellowish white, with a brown back), rearranged, the shadow |
| `peniel_plop.png`, `peniel_paltin.png` | [LPC] Trees (`trees-green.png`) | No, only cut out |
| `peniel_nuc.png` | [LPC] Trees (`trees-green.png`): the tree with the round, sparse crown | Yes: the bark made grey, the green walnuts drawn by us (`unelte/lpc/peniel_nuc.gd`) |
| `peniel_iarba_mare.png`, `peniel_iarba_mica.png` | [LPC] Farming tilesets (`tallgrass.png`) | Yes: the small patch composed from the corners of the large one, the colours slightly muted, the shadow |
| `peniel_fantana.png`, `peniel_piatra_mare.png`, `peniel_jgheab_*.png`, `peniel_casa.png`, `peniel_samar.png`, `peniel_idol_1..3.png`, `peniel_lana_*.png`, `peniel_movila_0..5.png`, `peniel_stalp.png` | Nothing from the packs | Drawn by us (the stones with the same tool as the altar in chapter 3); the well, the stone over its mouth and the heap at Gilead redrawn by us on 28 Oct 2026, in the manner of the walls in The Brothers (`unelte/lpc/pietre_rotunde.py`) |
| `peniel_stalp_80.png`, `peniel_stalp_60.png` (the pillar lying on the ground and carried by Jacob) | `peniel_stalp.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redone), to 80% and 60% |
| `peniel_bolovan_mana_1..3.png`, `peniel_stalp_mana.png` (the stones and the pillar held in the hand, 14 Nov 2026) | `chemarea_bolovan_1..3.png` from chapter 7 (copied here), `peniel_stalp.png` | Yes: without the shadow on the ground, scaled down with whole pixels (`unelte/lpc/in_mana.py`, like `unelte/sprite_mic.py`) to 65% and 55%; the pillar first turned onto its side by a quarter turn |
| `peniel_galeata_mana.png`, `peniel_idol_mana_1..3.png` (the bucket and the idols held in the hand, 14 Nov 2026) | `chemarea_galeata.png` from chapter 7 and `peniel_idol_1..3.png` (the colours and the shape) | Drawn by us, pixel by pixel, smaller (`unelte/lpc/in_mana.py`) |

The wrestling circle at the Jabbok, the arrows, the dawn light, the snow, the leaves, the petals and the dust are made from code.
The sounds (`sunete/peniel/`) are synthesised by us (`unelte/sunete_peniel.py`), with no third-party files.

## The packs

### Universal LPC Spritesheet Character Generator
The generator: https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator (the authors of each layer,
from the generator's CREDITS.csv):

| Layer | Worn by | Authors | Licences | Links |
|---|---|---|---|---|
| `body/bodies/male` (walking, hands raised) | the men, the children, the shadow | bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases, https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles |
| `body/bodies/female/walk.png` | Rachel, Leah, Bilhah, Zilpah | Benjamin K. Smith (BenCreating), bluecarrot16, TheraHedwig, Evert, MuffinElZangano, Durrani, Pierre Vigier (pvigier), ElizaWy, Matthew Krohn (makrohn), Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-ladies, https://opengameart.org/content/lpc-7-womens-shirts, https://opengameart.org/content/lpc-revised-character-basics |
| `head/heads/human/male/walk.png`, `head/heads/human/female/walk.png` | everyone | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases |
| `hair/plain/adult/walk.png` | Jacob, Laban, the shepherd, Esau's men, the children | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/ponytail-and-plain-hairstyles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/long_straight/adult/walk.png` | Rachel, Leah, Bilhah, Zilpah | JaidynReiman, thecilekli, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-long-straight-hair-with-12-colors, https://opengameart.org/content/lpc-hair |
| `hair/unkempt/adult/walk.png` | Esau | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `beards/beard/medium/walk.png`, `beards/beard/trimmed/walk.png` | Laban, the shepherds, Esau's men; Jacob (the short beard) | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/basic/walk.png` | Esau | JaidynReiman, Carlo Enrico Victoria (Nemisys) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-white-beard |
| `hat/cloth/hijab/male/walk.png`, `hat/cloth/hijab/thin/walk.png` (the headscarf, the veils) | Laban, Leah, Bilhah, Zilpah | thecilekli | CC0 | https://opengameart.org/content/lpc-hijab |
| `hat/cloth/hood/adult/walk.png` (the hood) | the second shepherd | Johannes Sjölund (wulax), JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `hat/cloth/bandana/adult/walk.png` | Esau's men | Matthew Krohn (makrohn), JaidynReiman, Marcel van de Steeg (MadMarcel) | OGA-BY 3.0, CC-BY-SA 3.0 | https://opengameart.org/content/lpc-expanded-hats-facial-helmets |
| `torso/clothes/longsleeve` (walking, hands raised) | the men, the children, the shadow | JaidynReiman, Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-expanded-simple-shirts |
| `torso/clothes/vest/male/walk/leather.png` | Esau | bluecarrot16, Thane Brimhall (pennomi), laetissima, Stephen Challener (Redshrike), Johannes Sjölund (wulax) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-2-characters, https://opengameart.org/content/lpc-pirates |
| `torso/clothes/robe/female/walk` | Rachel, Leah, Bilhah, Zilpah | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `torso/waist/sash` (the sash; walking, hands raised) | Jacob, Laban | bluecarrot16, Nila122 | OGA-BY 3.0, GPL 2.0, GPL 3.0, CC-BY-SA 3.0 | https://opengameart.org/content/more-lpc-clothes-and-hair, https://opengameart.org/content/lpc-pirates |
| `legs/skirts/plain` (walking, hands raised) | the men, the children, the shadow | bluecarrot16, Pierre Vigier (pvigier), Johannes Sjölund (wulax), Ahmad3366, JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `feet/sandals/male`, `feet/sandals/thin/walk.png` | everyone | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `quiver/walk.png` (the quiver) | Esau | Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `weapon/magic/simple` (the staff) | Jacob, the shepherds | bluecarrot16, Dr. Jamgo | CC0 | https://opengameart.org/content/lpc-simple-staff |

The skin and hair colours are from the generator's palettes ("olive", "taupe", "bronze", "raven", "gray",
"ginger") or chosen by us on the same steps (Jacob's dark chestnut, the olive green, the pomegranate, the fur).

### LPC style farm animals (the base sheep and lamb)
- Author: Daniel Eddeland (daneeklu), commissioned by tebruno99. Licence: CC-BY 3.0 / GPL 2.0.
- https://opengameart.org/content/lpc-style-farm-animals

### [LPC] Goat (the base goat)
- Author: bluecarrot16, to go with daneeklu's farm animals. Licence: CC-BY 3.0 / GPL 3.0 / GPL 2.0.
- https://opengameart.org/content/lpc-goat

### [LPC] bears, deer, lions and more (the flock's dog)
- The shiba dog: Sevarihk, in tapatilorenzo's pack. Licence: CC-BY 4.0.
- https://opengameart.org/content/lpc-bears-deer-lions-and-more

### [LPC] Trees (the poplar, the walnut, the sycamore)
- Authors: as in `credits/shared.md` (bluecarrot16, Jetrel, Zabin, Hyptosis, Surt, Buch, Johann Charlot, Stephen Challener and the others). Licence: CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-trees

### [LPC] Farming tilesets, magic animations and UI elements (the tall grass)
- Author: Daniel Eddeland (Daneeklu). Licence: CC-BY-SA 3.0 / GPL 3.0.
- https://opengameart.org/content/lpc-farming-tilesets-magic-animations-and-ui-elements
