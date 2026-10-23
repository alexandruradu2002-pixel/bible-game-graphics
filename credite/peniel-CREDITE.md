# Credite — capitolul 12 (Peniel)

Desenele din `grafica/peniel/`, folosite de capitolul 12 (Facerea 29–33). Sunt decupate, recolorate sau compuse din
pachete LPC de pe OpenGameArt.org și din generatorul de personaje LPC; unele sunt desenate de noi, în felul LPC
(contur închis, umbre în trepte, lumina din stânga-sus). Imaginile făcute din materiale CC-BY-SA rămân CC-BY-SA,
libere și pentru alții. Capitolul mai folosește, așa cum sunt, desene din alte capitole: zidurile stânii, stâncile și
pietricelele din capitolul 3, stâncile de munte din capitolul 5, corturile, tufele, vatra și oaia culcată din prolog,
trestia, găleata și bolovanii din capitolul 7, oaia, mielul, capra și lupul (autorii lor sunt în fișierele acelor
capitole și în `variante/lpc/CREDITE.md`).

## Fișierele și sursele lor

| Fișierul nostru | Din ce e făcut | Modificat de noi |
|---|---|---|
| `peniel_iacov.png`, `peniel_rahila.png`, `peniel_lia.png`, `peniel_laban.png`, `peniel_pastor_1.png`, `peniel_pastor_2.png`, `peniel_bilha.png`, `peniel_zilpa.png`, `peniel_isav.png`, `peniel_om_isav_1.png`, `peniel_om_isav_2.png`, `peniel_copil_1..3.png` | Universal LPC Spritesheet Character Generator (straturile de mers și, pentru Iacov, cele cu mâinile ridicate în față, „spellcast”) | Da: recolorate (Iacov cu păr castaniu închis, barbă scurtă, tunică verde-măsliniu și brâu maro; Rahila cu roba ca de rodie; Lia cu roba albastru-verzuie și val albastru; Laban cu barbă căruntă și haină vineție; Isav roșcat, cu haină de blană și tolbă), cadrul de „respirat”, umbra; pentru Iacov, rândurile de luptă (mâinile ridicate, capul luat din cadrul de stat) și închinarea până la pământ (în genunchi și cu fruntea la pământ, desenate de noi din cadrele de stat); pentru Rahila, șezutul pe samar |
| `peniel_umbra.png` (Cel ce se luptă cu Iacov) | Același generator: trup, cap, cămașă, fustă, sandale, cadrele de mers și „spellcast” | Da: totul făcut o umbră albastru-neagră, fără culori și fără chip |
| `peniel_oaie_pestrita.png`, `peniel_oaie_neagra.png`, `peniel_oaie_tunsa.png`, `peniel_miel_pestrit.png`, `peniel_miel_negru.png` | Oaia și mielul jocului (LPC style farm animals, `sheep_walk.png`, `sheep_eat.png`) | Da: pete mari cafeniu-închise (pestrițele), lâna neagră, oaia tunsă (pielea rozalie, lâna scurtă, trupul mai subțire) |
| `peniel_capra.png` | Capra capitolului 7 ([LPC] Goat, `goat.png`) | Da: pete albe (capră bălțată) |
| `peniel_camila.png` | LPC style farm animals (`llama_walk_0.png`, `llama_eat_0.png`) | Da: lama făcută cămilă: blana nisipie, cocoașa desenată de noi pe spate (în profil și din față), rearanjată, păscutul pus ca animație de stat, umbra |
| `peniel_caine.png` (câinele turmei) | [LPC] bears, deer, lions and more (`dog, shiba (Sevarihk).png`) | Da: recolorat ca un câine de păstor (alb-gălbui, cu spatele cafeniu), rearanjat, umbra |
| `peniel_plop.png`, `peniel_paltin.png` | [LPC] Trees (`trees-green.png`) | Nu, doar decupate |
| `peniel_migdal.png` | [LPC] Fruit Trees (`fruit-trees.png`): cireșul înflorit | Da: florile făcute alb-rozalii, ca ale migdalului |
| `peniel_iarba_mare.png`, `peniel_iarba_mica.png` | [LPC] Farming tilesets (`tallgrass.png`) | Da: petecul mic compus din colțurile celui mare, culorile puțin stinse, umbra |
| `peniel_fantana.png`, `peniel_piatra_mare.png`, `peniel_jgheab_*.png`, `peniel_casa.png`, `peniel_samar.png`, `peniel_idol_1..3.png`, `peniel_nuiele*.png`, `peniel_lana_*.png`, `peniel_movila_0..5.png`, `peniel_stalp.png` | Nimic din pachete | Desenate de noi (pietrele cu aceeași unealtă ca jertfelnicul din capitolul 3) |

Cercul luptei de la Iaboc, săgețile, lumina zorilor, zăpada, frunzele, petalele și praful sunt făcute din cod.
Sunetele (`sunete/peniel/`) sunt sintetizate de noi (`unelte/sunete_peniel.py`), fără fișiere de la terți.

## Pachetele

### Universal LPC Spritesheet Character Generator
Generatorul: https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator (autorii fiecărui strat,
din CREDITS.csv al generatorului):

| Stratul | Cine îl poartă | Autori | Licențe | Linkuri |
|---|---|---|---|---|
| `body/bodies/male` (mers, mâini ridicate) | bărbații, copiii, umbra | bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases, https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles |
| `body/bodies/female/walk.png` | Rahila, Lia, Bilha, Zilpa | Benjamin K. Smith (BenCreating), bluecarrot16, TheraHedwig, Evert, MuffinElZangano, Durrani, Pierre Vigier (pvigier), ElizaWy, Matthew Krohn (makrohn), Johannes Sjölund (wulax), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-ladies, https://opengameart.org/content/lpc-7-womens-shirts, https://opengameart.org/content/lpc-revised-character-basics |
| `head/heads/human/male/walk.png`, `head/heads/human/female/walk.png` | toți | bluecarrot16, Benjamin K. Smith (BenCreating), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-character-bases |
| `hair/plain/adult/walk.png` | Iacov, Laban, păstorul, oamenii lui Isav, copiii | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/ponytail-and-plain-hairstyles, https://opengameart.org/content/lpc-expanded-hair |
| `hair/long_straight/adult/walk.png` | Rahila, Lia, Bilha, Zilpa | JaidynReiman, thecilekli, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-long-straight-hair-with-12-colors, https://opengameart.org/content/lpc-hair |
| `hair/unkempt/adult/walk.png` | Isav | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/liberated-pixel-cup-lpc-base-assets-sprites-map-tiles, https://opengameart.org/content/lpc-expanded-hair |
| `beards/beard/medium/walk.png`, `beards/beard/trimmed/walk.png` | Laban, păstorii, oamenii lui Isav; Iacov (barba scurtă) | ElizaWy | OGA-BY 3.0 | https://github.com/ElizaWy/LPC/tree/main/Characters/Hair, https://opengameart.org/content/lpc-expanded-sit-run-jump-more |
| `beards/beard/basic/walk.png` | Isav | JaidynReiman, Carlo Enrico Victoria (Nemisys) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-white-beard |
| `hat/cloth/hijab/male/walk.png`, `hat/cloth/hijab/thin/walk.png` (broboada, vălurile) | Laban, Lia, Bilha, Zilpa | thecilekli | CC0 | https://opengameart.org/content/lpc-hijab |
| `hat/cloth/hood/adult/walk.png` (gluga) | păstorul al doilea | Johannes Sjölund (wulax), JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `hat/cloth/bandana/adult/walk.png` | oamenii lui Isav | Matthew Krohn (makrohn), JaidynReiman, Marcel van de Steeg (MadMarcel) | OGA-BY 3.0, CC-BY-SA 3.0 | https://opengameart.org/content/lpc-expanded-hats-facial-helmets |
| `torso/clothes/longsleeve` (mers, mâini ridicate) | bărbații, copiii, umbra | JaidynReiman, Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites, https://opengameart.org/content/lpc-expanded-simple-shirts |
| `torso/clothes/vest/male/walk/leather.png` | Isav | bluecarrot16, Thane Brimhall (pennomi), laetissima, Stephen Challener (Redshrike), Johannes Sjölund (wulax) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-2-characters, https://opengameart.org/content/lpc-pirates |
| `torso/clothes/robe/female/walk` | Rahila, Lia, Bilha, Zilpa | Luke Mehl | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/female-mage-clothing-set |
| `torso/waist/sash` (brâul; mers, mâini ridicate) | Iacov, Laban | bluecarrot16, Nila122 | OGA-BY 3.0, GPL 2.0, GPL 3.0, CC-BY-SA 3.0 | https://opengameart.org/content/more-lpc-clothes-and-hair, https://opengameart.org/content/lpc-pirates |
| `legs/skirts/plain` (mers, mâini ridicate) | bărbații, copiii, umbra | bluecarrot16, Pierre Vigier (pvigier), Johannes Sjölund (wulax), Ahmad3366, JaidynReiman | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `feet/sandals/male`, `feet/sandals/thin/walk.png` | toți | Nila122, JaidynReiman, Matthew Krohn (makrohn), Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 2.0, GPL 3.0 | https://opengameart.org/content/lpc-roman-armor, https://opengameart.org/content/lpc-expanded-socks-shoes |
| `quiver/walk.png` (tolba) | Isav | Johannes Sjölund (wulax) | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-medieval-fantasy-character-sprites |
| `weapon/magic/simple` (toiagul) | Iacov, păstorii | bluecarrot16, Dr. Jamgo | CC0 | https://opengameart.org/content/lpc-simple-staff |

Culorile pielii și ale părului sunt din paletele generatorului („olive”, „taupe”, „bronze”, „raven”, „gray”,
„ginger”) sau alese de noi pe aceleași trepte (castaniul închis al lui Iacov, verdele-măsliniu, rodia, blana).

### LPC style farm animals (lama făcută cămilă; oaia și mielul de bază)
- Autor: Daniel Eddeland (daneeklu), comandat de tebruno99. Licență: CC-BY 3.0 / GPL 2.0.
- https://opengameart.org/content/lpc-style-farm-animals

### [LPC] Goat (capra de bază)
- Autor: bluecarrot16, pe lângă animalele de fermă ale lui daneeklu. Licență: CC-BY 3.0 / GPL 3.0 / GPL 2.0.
- https://opengameart.org/content/lpc-goat

### [LPC] bears, deer, lions and more (câinele turmei)
- Câinele shiba: Sevarihk, în pachetul lui tapatilorenzo. Licență: CC-BY 4.0.
- https://opengameart.org/content/lpc-bears-deer-lions-and-more

### [LPC] Trees (plopul, paltinul)
- Autori: ca în `variante/lpc/CREDITE.md` (bluecarrot16, Jetrel, Zabin, Hyptosis, Surt, Buch, Johann Charlot, Stephen Challener și ceilalți). Licență: CC-BY-SA 3.0.
- https://opengameart.org/content/lpc-trees

### [LPC] Fruit Trees (migdalul)
- Autori: bluecarrot16, Joshua Taylor, cynicmusic. Comandat de castelonia. Licență: CC-BY-SA 4.0 / CC-BY-SA 3.0 / GPL 3.0.
- https://opengameart.org/content/lpc-fruit-trees

### [LPC] Farming tilesets, magic animations and UI elements (iarba înaltă)
- Autor: Daniel Eddeland (Daneeklu). Licență: CC-BY-SA 3.0 / GPL 3.0.
- https://opengameart.org/content/lpc-farming-tilesets-magic-animations-and-ui-elements
