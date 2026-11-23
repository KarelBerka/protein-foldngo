# 🧬 Protein Fold'n'Go (Proteinové Ubongo)

Interaktivní biochemická skládačka ve stylu deskové hry **Ubongo**, ve které z peptidových polyomino dílků skládáte trojrozměrné architektury proteinů podle vlastností postranních řetězců aminokyselin.

👉 **Hrát přímo v prohlížeči:** [https://karelberka.github.io/protein-foldngo/](https://karelberka.github.io/protein-foldngo/)  
🌐 **Jazykové verze / Languages:** [Čeština (CZ)](https://karelberka.github.io/protein-foldngo/cz/) · [English (EN)](https://karelberka.github.io/protein-foldngo/en/) · [Deutsch (DE)](https://karelberka.github.io/protein-foldngo/de/) · [Français (FR)](https://karelberka.github.io/protein-foldngo/fr/)

## Co hra obsahuje

- **9 různě velkých a obtížných proteinových skládaček (12–28 aminokyselin, 3–7 dílků) včetně reálných molekulárních příkladů z PDB:**
  1. ⭐ **Mini-globule** *(12 AK, 3 dílky)* — rozehřívačka s jádrem 2×2 a disulfidickým můstkem `C*–C*` · 🧪 **Lidský inzulín** ([PDB: `3I40`](https://www.rcsb.org/structure/3I40))
  2. ⭐ **Amfipatická páska** *(16 AK, 4 dílky, 8×2)* — hydrofilní strana vs. hydrofobní rozhraní · 🧪 **Melitin (včelí jed)** ([PDB: `2MLT`](https://www.rcsb.org/structure/2MLT))
  3. ⭐⭐ **Globulární enzym** *(20 AK, 5 dílků, ovál 6×4)* — hydrofobní jádro, solný můstek `K+–D−` a disulfidický můstek `C*–C*` · 🧪 **Lysozym (vaječný bílek)** ([PDB: `1DPX`](https://www.rcsb.org/structure/1DPX))
  4. ⭐⭐ **Membránový kanál** *(20 AK, 5 dílků, 5×4)* — lipidová dvojvrstva po bocích, hydrofilní pór středem · 🧪 **Akvaporin-1 (AQP1)** ([PDB: `1J4N`](https://www.rcsb.org/structure/1J4N))
  5. ⭐⭐ **Dlouhá fibrila** *(20 AK, 5 dílků, 8×3)* — souvislá hydrofobní osa uprostřed vlákna · 🧪 **Amyloid-β(1–42) fibrila** ([PDB: `2BEG`](https://www.rcsb.org/structure/2BEG))
  6. ⭐⭐⭐ **Cysteinová proteáza** *(24 AK, 6 dílků, 7×4)* — polární tunel vedoucí dovnitř jádra + **aktivní místo `C*`** · 🧪 **Papain (*Carica papaya*)** ([PDB: `9PAP`](https://www.rcsb.org/structure/9PAP))
  7. ⭐⭐⭐ **Tandemová dvou-doména** *(24 AK, 6 dílků, 12×2)* — modulární řetězec dvou bloků za sebou · 🧪 **Lidská protilátka IgG1** ([PDB: `1HZH`](https://www.rcsb.org/structure/1HZH))
  8. ⭐⭐⭐⭐ **Velký membránový transportér** *(28 AK, 7 dílků, 7×4)* — široký polární tunel v membráně + redoxní senzor `C*` · 🧪 **Mitochondriální porin VDAC1** ([PDB: `3EMN`](https://www.rcsb.org/structure/3EMN))
  9. ⭐⭐⭐⭐ **Cytochrom P450** *(26 AK, 6 dílků, 6×7)* — periferní membránový enzym s N-terminální transmembránovou kotvou + kanálem k hemovému **aktivnímu místu `C*`** · 🧪 **Cytochrom P450 (CYP51, plná délka)** ([PDB: `4LXJ`](https://www.rcsb.org/structure/4LXJ))
- **4 jazykové verze:** čeština (`CZ`), angličtina (`EN`), němčina (`DE`) a francouzština (`FR`).
- **4 předpřipravené varianty (A–D) + generátor `🎲 Jiná kombinace`** pro nekonečnou znovuhratelnost u každého typu proteinu.
- **Pouze otáčení (bez zrcadlového překlápění)** — přetahování myší (Drag & Drop), magnetické přicvakávání, pravý klik / klávesa `R` pro otočení.
- **Tisková A4 šablona pro výuku v měřítku 1:1 (`20 × 20 mm` velké dílky / `14 × 14 mm` kompaktní)** — všech 9 podkladů a všech 42 dílků k vystřižení (včetně výběru rozsahu tisku, kontrolního pravítka `80 mm` / `70 mm` a značek `●`, `+`, `−`, `*`, `°` pro černobílý tisk).

## Barevné a symbolické kódování aminokyselin

| Skupina | Barva / značka | Kódy | Chování při skládání |
|---|---|---|---|
| **Hydrofobní (nepolární)** | 🟨 žlutá (`●`) | `L●, V●, I●, F●, A●, M●` | Jádro proteinu, lipidová membrána, osa fibrily (`F●`) |
| **Polární bez náboje** | 🟩 zelená | `S, T, N, Q` | Vodný povrch a polární tunel / pór |
| **Kladně nabité (+)** | 🟦 modrá (`+`) | `K+, R+` | Vodné prostředí; tvoří **solný můstek** s `−` |
| **Záporně nabité (−)** | 🟥 červená (`−`) | `D−, E−` | Vodné prostředí; tvoří **solný můstek** s `+` |
| **Speciální / strukturní** | 🟪 fialová (`*` / `°`) | `C*, G°, P°` | Dva sousední `C*` tvoří **disulfidický můstek (`S–S`)**; aktivní místo enzymu |

## Autor a související projekty

- **Autor:** [Karel Berka](https://karelberka.github.io/)
- **Další biochemické výukové hry:** [🧬 BioDobble](https://karelberka.github.io/bio-dobble/)

## Poděkování / Acknowledgement

This work was supported in part by complimentary access to [Google Antigravity](https://antigravity.google/) and Gemini 4 Argon, Carbon, Neon and Hydrogen to accelerate scientific workflows.

## Licence

MIT © [Karel Berka](https://karelberka.github.io/)
