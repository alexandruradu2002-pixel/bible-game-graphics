# Credite — capitolul 7 (Chemarea)

Desenele din `grafica/chemarea/`. Capitolul folosește și desenele prologului (`grafica/haran/`: solul, corturile,
palmierii, stâncile, Avram, Sarai, Lot), cu autorii lor în `parti/haran-CREDITE.md`. Autorii de mai jos trebuie să
apară pe ecranul de mulțumiri. Imaginile făcute din materiale CC-BY-SA rămân CC-BY-SA.

## Fișierele și sursele lor

| Fișierul nostru | Din ce e făcut | Modificat de noi |
|---|---|---|
| `terah.png` | Universal LPC Spritesheet Character Generator: trup, capul de bătrân, păr lung, barba albă („winter”), cămașă lungă, fustă, sandale, toiag | Da: recolorate (păr și barbă albe, haina vișinie închisă), ochii capului de bătrân făcuți căprui, cadrul de „respirat”, umbra |
| `chemarea_sluga.png`, `chemarea_slujnica.png` | Același generator: trup, cap, păr, cămașă lungă, fustă, robă, văl, sandale | Da: recolorate (lână nevopsită, cafeniu, cenușiu), cadrul de „respirat”, umbra |
| `chemarea_canaanit.png`, `chemarea_canaanita.png` | Același generator: trup, cap, păr, barbă, cămașă lungă, fustă, brâu, robă, broboadă, sandale | Da: recolorate în roșu și purpuriu (Canaaneii), cadrul de „respirat”, umbra |
| `chemarea_capra.png` | [LPC] Goat (`goat.png`) | Da: recolorată din alb în negru-cafeniu (caprele de păr din Orient), micșorată la 60% (culorile întoarse pe paleta ei, conturul refăcut), rearanjată, păscutul pus ca animație de stat, umbra |
| `chemarea_stejar.png` (stejarul Mamvri) | [LPC] Trees (`trees-green.png`) | Nu, doar decupat |
| `chemarea_copac_1.png`, `chemarea_copac_3.png` | [LPC] Trees (`trees-pale.png`) | Nu, doar decupați |
| `chemarea_trestie_1..3.png` | [LPC] Flowers / Plants (`plants.png`): papura și trestia | Da: o umbră mică |
| `chemarea_cort_lasat.png`, `chemarea_cort_strans.png`, `chemarea_tarus.png` | Nimic din pachete | Desenate de noi: cortul lui Avram lăsat pe prăjini și făcut sul, țărușul |
| `chemarea_jgheab_0..3.png`, `chemarea_galeata.png`, `chemarea_ulcior.png`, `chemarea_burduf.png`, `chemarea_sac.png`, `chemarea_cos.png`, `chemarea_covor.png`, `chemarea_rasnita.png` | Nimic din pachete | Desenate de noi |
| `chemarea_stela_1..3.png`, `chemarea_jertfelnic_0..8.png`, `chemarea_bolovan_1..3.png`, `chemarea_movila.png` | Nimic din pachete | Desenate de noi, cu aceeași unealtă de pietre ca jertfelnicul din capitolul 3 |
| `chemarea_casa.png`, `chemarea_casa_noapte.png` | Nimic din pachete | Desenate de noi: casa de piatră cu acoperiș plat (cu lumina aprinsă, la Betel și Hai) |
| `chemarea_negustor.png`, `chemarea_negustor_2.png`, `chemarea_satean.png`, `chemarea_sateanca.png` | `chemarea_canaanit.png` și `chemarea_canaanita.png` de mai sus (Universal LPC Spritesheet Character Generator) | Da: hainele recolorate (albastru, verde-măsliniu, cafeniu, verde-albastru), cu `unelte/lpc/chemarea_oameni.py` |
| `chemarea_camila.png` (cămilele negustorilor de la vad) | Nimic din pachete | Desenată de noi pentru capitolul 10 (`unelte/lpc/fantana_camila.py`), copiată aici |
| `chemarea_harta.png`, `chemarea_harta_gol.png` (harta drumului caravanei) | Nimic din pachete | Desenate de noi, din cod (`unelte/lpc/chemarea_harta.py`): pergamentul, marea, râurile, munții, pustia, locurile drumului |

Curcubeul (taina de la piatra lui Sem), luminile, flăcările și stelele sunt făcute din cod, la fel ca drumurile,
caravana mică și etichetele de pe harta drumului. Pietrele vadului sunt bolovanii de mai sus.
Sunetele (`sunete/chemarea/`) sunt sintetizate de noi (`unelte/sunete_chemarea.py`), fără fișiere de la terți.

## Pachetele

### Universal LPC Spritesheet Character Generator
https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator. Straturile comune cu Avram, Sarai și
Lot (trupuri, capete, barba „medium”, broboada și vălul, cămașa lungă, roba, brâul, fusta, sandalele, toiagul) sunt
în `parti/haran-CREDITE.md`, cu autorii lor. În plus:

| Stratul | Cine îl poartă | Autori | Licențe | Linkuri |
|---|---|---|---|---|
| `head/heads/human/male_elderly/walk.png` | Terah | Benjamin K. Smith (BenCreating), Eliza Wyatt (ElizaWy), Stephen Challener (Redshrike) | OGA-BY 3.0, CC-BY 3.0 | https://opengameart.org/content/lpc-revised-elders, https://opengameart.org/content/lpc-character-bases |
| `hair/long/adult/walk.png` | Terah | JaidynReiman, Manuel Riecke (MrBeast) | CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/lpc-expanded-hair |
| `hair/plain/adult/walk.png` | sluga, Canaanitul | JaidynReiman, Manuel Riecke (MrBeast), Joe White | OGA-BY 3.0, CC-BY-SA 3.0, GPL 3.0 | https://opengameart.org/content/ponytail-and-plain-hairstyles |
| `hair/long_straight/adult/walk.png` | slujnica, Canaanita | JaidynReiman, thecilekli, bluecarrot16 | CC0 | https://opengameart.org/content/lpc-long-straight-hair-with-12-colors |
| `beards/beard/winter/male/walk.png` | Terah | bluecarrot16 | CC0 | https://opengameart.org/content/lpc-santa |

### [LPC] Goat
- Autor: bluecarrot16 (o capră care să meargă cu animalele lui daneeklu). Licență: CC-BY 3.0 / GPL 3.0 / GPL 2.0.
- https://opengameart.org/content/lpc-goat

### [LPC] Trees
- Autori și licență: ca în `variante/lpc/CREDITE.md` (CC-BY-SA 3.0). https://opengameart.org/content/lpc-trees

### [LPC] Flowers / Plants / Fungi / Wood
- Autori și licență: ca în `variante/lpc/CREDITE.md` (CC-BY-SA 3.0). https://opengameart.org/content/lpc-flowers-plants-fungi-wood
