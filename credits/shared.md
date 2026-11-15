# Credits — the "lpc" style

All the images in `graphics/` are cut out of or composed from free packs of the **Liberated Pixel Cup (LPC)** family,
from OpenGameArt.org and from the LPC character generator. The licences are mixed; for each of our files we state
where it comes from, who drew it, under which licence and what we changed.

**What the licences require:** the names of all the authors below and the links to their pages must appear somewhere
the player can see them (a credits screen in the game or a page linked from the game). Images made from CC-BY-SA
material (the ground, the trees, the plants, the fruit trees, the stones) are CC-BY-SA as well: anyone may reuse them
under the same terms, and the files must not be encrypted or locked (Godot's ordinary export is fine). The game's code
is not affected.

## Our files and their sources

| Our file | Made from | Modified by us |
|---|---|---|
| `teren.png` | [LPC] Terrains (`terrain-v7.png`): the grass, the dark grass, the shallow water with a grassy bank; for chapter 3: the earth, the cracked earth, the sand, the gravel, the dry grass, the ploughed earth, the path, the grass on earth, the lighter grass, the water with an earthen bank, pebbles; [LPC] Flowers / Plants (`plants.png`): flowers, tufts, water lilies; LPC Base Assets (`rock.png`): the small stones of the ford; [LPC] Farming tilesets (`wheat.png`): the wheat on the field | Yes: the pieces rearranged into rows, the water made slightly bluer (three colours changed), the dry grass recoloured from rust to straw yellow, the ploughed earth made less reddish, the ford stones placed in pairs, with foam and a shadow in the water drawn by us; the grassy banks copied without the grass beneath them (rows 19-20, `unelte/lpc/teren_maluri.py`), so the water can be placed over forest and path; the gravel (rows 10 and 14) redrawn by us on 28 Oct 2026, in the LPC manner (`unelte/lpc/piatra_seaca.py`), in place of the one from the pack; the ford stones (row 5) and the pebbles (row 6) redrawn by us on 28 Oct 2026, in the manner of the walls in The Brothers (`unelte/lpc/pietre_rotunde.py`) |
| `copac_1.png`, `copac_2.png`, `copac_3.png`, `padure_1.png`, `padure_2.png`, `padure_3.png` | [LPC] Trees (`trees-green.png`) | No, only cut out |
| `pomul_vietii.png` (apple tree with golden fruit), `pomul_cunostintei.png` (pomegranate tree, red fruit) | [LPC] Fruit Trees (`fruit-trees.png`) | No, only cut out |
| `pomul_cunostintei_mare.png` (the tree of knowledge in the chapters The Garden and The Tree, the same as the one on the map, without an outline) | [LPC] Trees (`trees-green.png`): the tree with the spreading crown; [LPC] Fruit Trees (`fruit-trees.png`): the pomegranates from `pomul_cunostintei.png` | Yes: the pomegranates placed on the crown, by us (`unelte/lpc/repere/pomul.gd`) |
| `reper_pomul.png`, `reper_pomul_inchis.png` (the tree of knowledge on the map of the "Chapters" screen, whole and unfinished) | [LPC] Trees (`trees-green.png`): the tree with the spreading crown; [LPC] Fruit Trees (`fruit-trees.png`): the pomegranates from `pomul_cunostintei.png` | Yes: the pomegranates and the flowers placed on the crown, by us (`unelte/lpc/repere/pomul.gd`, `unelte/lpc/drumul_repere.gd`) |
| `reper_turnul.png`, `reper_betel.png`, `reper_cosuletul.png`, `reper_stalpul.png`, `reper_sarpele.png`, `reper_mormantul.png`, `reper_snopii.png`, each with its unfinished drawing (`reper_<cheie>_inchis.png`): the landmarks on the map of the "Chapters" screen | Nothing from the packs | Drawn by us (from code: `unelte/lpc/repere/<cheie>.gd`, written by `unelte/lpc/drumul_repere.gd`), in the LPC manner: dark outline, stepped shading; the bulrushes of the basket and the ear of grain of the sheaves are our drawings from the chapters The Basket and The Threshing Floor |
| `map-regions/*.png` (the regions on the map of the "Chapters" screen, 7 Nov 2026: the olive trees, the vine, the terrace wall, the bulrushes, the reeds, the willow, the tamarisk, the oak, the walnut tree, the plane tree, the dry bush, the red rocks) | Copies of the drawings from the chapters, with their sources from there: `mamvri_maslin.png` and `valaam_salcie.png` (from `chemarea_copac_3.png`, [LPC] Trees), `moria_maslin.png`, `chemarea_stejar.png`, `peniel_nuc.png`, `peniel_paltin.png` ([LPC] Trees, `trees-green.png`), `iacov_tamarisc_1.png` ([LPC] Trees, `trees-pale.png`), `chemarea_trestie_1..2.png` ([LPC] Flowers / Plants), `iosif_vie.png`, `iosif_papirus.png`, `pustia_tufa_1.png`, `zid_o_plin.png` (our drawings), `haran_stanca_1..3.png` (LPC Base Assets, `mountains.png`) | Only the rocks: recoloured red, like the granite of the wilderness (`unelte/lpc/drumul_tinuturi.gd`); the rest copied exactly |
| `smochin.png` (chapter 2) | [LPC] Fruit Trees (`fruit-trees.png`): a bare, branching trunk; [LPC] Flowers / Plants (`plants.png`): the large, lobed leaves | Yes: the trunk recoloured grey (the bark of the fig tree), the crown composed by us from leaves, the figs drawn by us |
| `tufis.png` | [LPC] Flowers / Plants (`plants.png`) | No, only cut out |
| `piatra.png` | LPC Base Assets (`rock.png`) | Yes: shadow added; the stone redrawn by us on 28 Oct 2026, in the manner of the walls in The Brothers (`unelte/lpc/pietre_rotunde.py`) |
| `adam.png`, `eva.png` | Universal LPC Spritesheet Character Generator: body, head, hair, beard (the walking layers); the shape of the LPC skirt, used only as a template | Yes: recoloured ("olive" skin, dark chestnut hair for Adam and light chestnut for Eve, brown eyes), the covering of leaves painted by us (on Adam from the waist down, on Eve from the shoulders to the knees), the "breathing" frame, Adam lying down (the front view rotated, eyes closed), Adam kneeling (the front view, lowered over the shins), the shadow |
| `adam_haine.png`, `eva_haine.png` (chapter 2) | The same generator layers as for `adam.png` and `eva.png` | Yes: instead of leaves, the garments of skin (Genesis 3:21) painted by us: fur tunics, with a belt and tufts at the hem; Adam and Eve lying down, as in `adam.png` |
| `sarpe.png` (chapter 2) | Nothing from the packs: drawn by us, in the LPC manner (dark outline, stepped shading) | Drawn by us |
| `the-brothers/stanca_1.png`, `the-brothers/stanca_2.png`, `the-brothers/stanca_3.png` (chapter 3) | LPC Base Assets (`mountains.png`): the brown boulder, the stone spikes, the small stones | Yes: the boulder turned around and placed with two small stones beside it; shadow added under the spikes |
| `the-brothers/spini_1.png`, `the-brothers/spini_2.png`, `the-brothers/spini_3.png` (chapter 3) | [LPC] Flowers / Plants (`plants.png`): dry, thorny bushes | No, only cut out |
| `the-brothers/spini_1_75.png` (chapter 3, the thorns in the sheep's wool) | `the-brothers/spini_1.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redrawn), to 75% |
| `the-brothers/pietricica_1.png` … `pietricica_4.png` (chapter 3) | [LPC] Terrains (`terrain-v7.png`): the small stones | Yes: redrawn by us on 28 Oct 2026, in the manner of the walls in The Brothers (`unelte/lpc/pietre_rotunde.py`) |
| `the-brothers/floare_spin_1.png`, `floare_spin_2.png`, `ramurele.png`, `tufa_mica_1.png`, `tufa_mica_2.png` (chapter 3) | [LPC] Flowers / Plants (`plants.png`): purple flowers, a dry twig, small bushes | No, only cut out |
| `the-brothers/smoc_uscat_1.png`, `smoc_uscat_2.png` (chapter 3) | [LPC] Flowers / Plants (`plants.png`): tufts of grass | Yes: recoloured straw yellow (dry grass) |
| `the-brothers/zid_*.png`, `the-brothers/jertfelnic.png`, `the-brothers/cort.png` (chapter 3) | Nothing from the packs: the dry-stone wall of the sheepfold (slabs in courses, with coping, corners and ends) and the altar of unhewn stones (`unelte/lpc/piatra_seaca.py`, since 28 Oct 2026), the tent of skins on poles, all drawn by us, in the LPC manner | Drawn by us |
| `the-brothers/cain.png`, `the-brothers/abel.png` (chapter 3) | The generator layers: body, head, short hair, beard (Cain), long shirt, skirt, sandals, staff ("simple staff", for Abel) | Yes: recoloured (Cain: "taupe" skin, black hair and beard, brown clothes; Abel: "olive" skin, dark chestnut hair, light woollen clothes), the blue stone removed from the top of the staff (the crook remains), the staff held upright when walking, the shadow |
| `the-brothers/miel.png` (chapter 3) | LPC style farm animals (`sheep_walk.png`, `sheep_eat.png`) | Yes: the sheep scaled down to 70%, brought back to its own colours and re-outlined, shadow |
| `the-brothers/miel_72.png`, `the-brothers/miel_86.png` (chapter 3, the smaller lambs; chapter 13, the lamb carried on the shoulders) | `the-brothers/miel.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redrawn), to 72% and 86% |
| `oaie.png` | LPC style farm animals (`sheep_walk.png`, `sheep_eat.png`) | Yes: cut out, rearranged, the grazing set as the idle animation, shadow |
| `oaie_70.png` (the hidden lamb in every chapter), `oaie_84.png` (the young ewes in chapter 3, the thin sheep in chapter 13) | `oaie.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redrawn), to 70% and 84% |
| `iepure.png` | Bunny Rabbit LPC style for PixelFarm, in the reorganised version (`rabbit_2.png`) | Yes: recoloured from white to brown (a hare), rearranged, shadow |
| `porumbel.png` | [LPC] Birds (`bird_1_white.png`) | Yes: rearranged, shadow |
| `porumbel_50.png` (the doves behind the Tower of Babel) | `porumbel.png` | Yes: scaled down by `unelte/sprite_mic.py`, with whole pixels (each pixel is a colour of the large drawing, the outline redrawn), to half size |
| `leu.png` | [LPC] bears, deer, lions and more (`lion.png`) | Yes: the coloured background removed, rearranged, shadow; the lion lying down (the body lowered, the front leg stretched out, the tail on the grass) drawn by us from its profile frame |

## The packs

### [LPC] Terrains
- Authors: bluecarrot16, Lanea Zimmerman (Sharm), Daniel Eddeland (Daneeklu), Richard Kettering (Jetrel), Zachariah Husiar (Zabin), Hyptosis, Casper Nilsson, Buko Studios, Nushio, ZaPaper, billknye, William Thompson, caeles, Redshrike, Bertram, Rayane Félix (RayaneFLX).
- Licence: CC-BY-SA 4.0 / CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-terrains
- The works it builds on (from CREDITS-terrain.txt): LPC Base Assets (Sharm, CC-BY 3.0 / CC-BY-SA 3.0 / GPL 3.0); [LPC] Farming tilesets (Daneeklu, CC-BY-SA 3.0 / GPL 3.0); ZRPG Tiles (Jetrel, Zabin, Hyptosis, Sharm, Open Pixel Project, CC-BY-SA 3.0+); LPC C.Nilsson (CC-BY-SA 3.0 / GPL 3.0); Frozen Lake [LPC] (Buko Studios, CC-BY 3.0); LPC Animated Water and waterfalls (ZaPaper, CC-BY-SA 3.0); LPC More Water Transitions (billknye, CC-BY-SA 3.0 / GPL 3.0); [LPC] Sand+Rock Alt Colors (William.Thompsonj, Daniel Eddeland, CC-BY-SA 3.0 / GPL 3.0); [LPC] Colorful Sand + Deep Water! (Nushio, CC-BY-SA 3.0 / GPL 3.0); LPC terrain extension (caeles, CC-BY-SA 3.0 / GPL 3.0); RPG Tiles: Cobble stone paths & town objects (Zabin, Daneeklu, Jetrel, Hyptosis, Redshrike, Bertram, CC-BY-SA 3.0); RPG Terrains (RayaneFLX, CC-BY-SA 3.0).

### [LPC] Trees
- Authors: bluecarrot16, Jetrel, Zabin, Hyptosis, Surt, Buch, Johann Charlot, Stephen Challener and the Open Surge team (http://opensnc.sourceforge.net), Gaurav Munjal, Ivan Voirol (Silver IV), Guido Bos, Yar, Paulina Riva (PauR), William.Thompsonj, Casper Nilsson, ansimuz, qubodup, Bart K., Blarumyrran, Lanea Zimmerman (Sharm), Leonard Pabin, Chris Phillips, Barbara Rivera, Talosaurus.
- Licence: CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-trees
- The pack does not say who drew each individual tree, so we list them all.

### [LPC] Fruit Trees
- Authors: bluecarrot16, Joshua Taylor, cynicmusic. Commissioned by castelonia.
- Licence: CC-BY-SA 4.0 / CC-BY-SA 3.0 / GPL 3.0.
- https://opengameart.org/content/lpc-fruit-trees
- Builds on: Fruit and Veggie Inventory (Joshua Taylor, CC-BY-SA 3.0 / GPL 3.0, https://opengameart.org/content/fruit-and-veggie-inventory) and Pixelsphere 32x32 Tileset (cynicmusic, CC0).

### [LPC] Flowers / Plants / Fungi / Wood
- Authors: bluecarrot16, Guido Bos, Ivan Voirol (Silver IV), SpiderDave, William.Thompsonj, Yar, Stephen Challener and the Open Surge team, Gaurav Munjal, Johann Charlot, Casper Nilsson, Jetrel, Zabin, Hyptosis, Surt, Lanea Zimmerman, George Bailey, ansimuz, Buch, the Open Pixel Project contributors (OpenPixelProject.com).
- Licence: CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-flowers-plants-fungi-wood

### Liberated Pixel Cup (LPC) Base Assets
- `rock.png`, `mountains.png`: Lanea Zimmerman (Sharm).
- Licence: CC-BY-SA 3.0 / GPL 3.0 (Sharm's works are also OGA-BY 3.0).
- https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles

### Universal LPC Spritesheet Character Generator (Adam, Eve, Cain, Abel)
The generator: https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator (the authors of each layer, from CREDITS.csv):

| Layer | Authors | Licences | Links |
|---|---|---|---|
| `body/bodies/male/walk.png` (Adam) | bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases, https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-revised-character-basics |
| `body/bodies/female/walk.png` (Eve) | Benjamin K. Smith (BenCreating), bluecarrot16, TheraHedwig, Evert, MuffinElZangano, Durrani, Pierre Vigier (pvigier), ElizaWy, Matthew Krohn (makrohn), Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases, https://opengameart.org/content/lpc-ladies, https://opengameart.org/content/lpc-7-womens-shirts, https://gitlab.com/vagabondgame/lpc-characters |
| `head/heads/human/male/walk.png`, `head/heads/human/female/walk.png` | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-character-bases |
| `hair/long/adult/walk.png` (Adam) | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/long_straight/adult/walk.png` (Eve) | JaidynReiman, thecilekli, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-long-straight-hair-with-12-colors, https://opengameart.org/content/lpc-hair, https://opengameart.org/content/lpc-expanded-hair |
| `beards/beard/medium/walk.png` (Adam) | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `legs/skirts/plain/male/walk.png` (the shape of the leaves; Cain's and Abel's skirt) | bluecarrot16, Pierre Vigier (pvigier), Johannes Sjölund (wulax), Ahmad3366, JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `hair/plain/adult/walk.png` (Cain, Abel) | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/ponytail-and-plain-hairstyles, https://opengameart.org/content/lpc-expanded-hair |
| `torso/clothes/longsleeve/longsleeve/male/walk.png` (Cain, Abel) | JaidynReiman, Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-revised-character-basics |
| `feet/sandals/male/walk.png` (Cain, Abel) | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, http://opengameart.org/content/lpc-clothing-updates, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `weapon/magic/simple/` (Abel's staff) | bluecarrot16, Dr. Jamgo | CC0 | https://opengameart.org/content/lpc-simple-staff |

The skin and hair colours are the generator's palettes ("olive", "taupe", "dark_brown", "light_brown", "black");
Cain's and Abel's clothes are the layers above, recoloured, also with the generator's palettes ("walnut", "brown", "tan"). The eyes in the heads were
recoloured brown by us; the generator's separate eye layer is not used.

### [LPC] Farming tilesets, magic animations and UI elements (the wheat)
- Author: Daniel Eddeland (Daneeklu). Required attribution: "Daniel Eddeland", with a link to the page.
- Licence: CC-BY-SA 3.0 / GPL 3.0.
- https://opengameart.org/content/lpc-farming-tilesets-magic-animations-and-ui-elements

### LPC style farm animals (the sheep, the lamb)
- Author: Daniel Eddeland (daneeklu), commissioned by tebruno99.
- Licence: CC-BY 3.0 / GPL 2.0. Required attribution: "Daniel Eddeland", with a link to the page.
- https://opengameart.org/content/lpc-style-farm-animals

### Bunny Rabbit LPC style for PixelFarm (the hare)
- Author: Stephen "Redshrike" Challener, commissioned by Tebruno99 for PixelFarm (https://bitbucket.org/tebruno99/pixelfarm).
- Licence: CC-BY 3.0 / CC-BY-SA 3.0 / OGA-BY 3.0.
- https://opengameart.org/content/bunny-rabbit-lpc-style-for-pixelfarm
- Used in the version reorganised by Evert (who does not require credit): https://opengameart.org/content/reorganised-lpc-rabbit

### [LPC] Birds (the dove)
- Author: bluecarrot16, commissioned by castelonia. Asks for a link back to the page.
- Licence: CC-BY 4.0 / CC-BY 3.0 / CC-BY-SA 4.0 / CC-BY-SA 3.0 / GPL 3.0 / GPL 2.0 / OGA-BY 3.0.
- https://opengameart.org/content/lpc-birds

### [LPC] bears, deer, lions and more (the lion)
- Author: tapatilorenzo (the pack also includes works adapted from Sevarihk, but not the lion).
- Licence: CC-BY 4.0.
- https://opengameart.org/content/lpc-bears-deer-lions-and-more
