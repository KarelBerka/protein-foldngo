# 🧬 Protein Fold'n'Go (Proteinové Ubongo)

Interaktivní biochemická skládačka ve stylu deskové hry **Ubongo**, ve které z peptidových polyomino dílků skládáte trojrozměrné architektury proteinů podle vlastností postranních řetězců aminokyselin.

👉 **Hrát přímo v prohlížeči:** [https://karelberka.github.io/protein-foldngo/](https://karelberka.github.io/protein-foldngo/)

## Co hra obsahuje

- **8 různě velkých a obtížných proteinových skládaček (12–28 aminokyselin, 3–7 dílků):**
  1. ⭐ **Mini-globule** *(12 AK, 3 dílky)* — rozehřívačka s jádrem 2×2 a disulfidickým můstkem `C*–C*`
  2. ⭐ **Amfipatická páska** *(16 AK, 4 dílky, 8×2)* — hydrofilní strana vs. hydrofobní rozhraní
  3. ⭐⭐ **Globulární enzym (KSICHT)** *(20 AK, 5 dílků, ovál 6×4)* — hydrofobní jádro, solný můstek `K+–D−` a disulfidický můstek `C*–C*`
  4. ⭐⭐ **Membránový kanál (KSICHT)** *(20 AK, 5 dílků, 5×4)* — lipidová dvojvrstva po bocích, hydrofilní pór středem
  5. ⭐⭐ **Dlouhá fibrila (KSICHT)** *(20 AK, 5 dílků, 8×3)* — souvislá hydrofobní osa uprostřed vlákna
  6. ⭐⭐⭐ **Cysteinová proteáza** *(24 AK, 6 dílků, 7×4)* — polární tunel vedoucí dovnitř jádra + **aktivní místo `C*`**
  7. ⭐⭐⭐ **Tandemová dvou-doména** *(24 AK, 6 dílků, 12×2)* — modulární řetězec dvou bloků za sebou
  8. ⭐⭐⭐⭐ **Velký membránový transportér** *(28 AK, 7 dílků, 7×4)* — široký polární tunel v membráně + redoxní senzor `C*`
- **4 předpřipravené varianty (A–D) + generátor `🎲 Jiná kombinace`** pro nekonečnou znovuhratelnost u každého typu proteinu.
- **Pouze otáčení (bez zrcadlového překlápění)** — přetahování myší (Drag & Drop), magnetické přicvakávání, pravý klik / klávesa `R` pro otočení.
- **Tisková A4 šablona pro výuku a KSICHT** (včetně značek `●`, `+`, `−`, `*`, `°` pro černobílý tisk).

## Barevné a symbolické kódování aminokyselin

| Skupina | Barva / značka | Kódy | Chování při skládání |
|---|---|---|---|
| **Hydrofobní (nepolární)** | 🟨 žlutá (`●`) | `L●, V●, I●, F●, A●, M●` | Jádro proteinu, lipidová membrána, osa fibrily (`F●`) |
| **Polární bez náboje** | 🟩 zelená | `S, T, N, Q` | Vodný povrch a polární tunel / pór |
| **Kladně nabité (+)** | 🟦 modrá (`+`) | `K+, R+` | Vodné prostředí; tvoří **solný můstek** s `−` |
| **Záporně nabité (−)** | 🟥 červená (`−`) | `D−, E−` | Vodné prostředí; tvoří **solný můstek** s `+` |
| **Speciální / strukturní** | 🟪 fialová (`*` / `°`) | `C*, G°, P°` | Dva sousední `C*` tvoří **disulfidický můstek (`S–S`)**; aktivní místo enzymu |

## Licence

MIT © Karel Berka
