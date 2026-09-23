# Bab 4: Music Theory, Fretboard Geometry & Harmony

## Pendahuluan
Banyak gitaris menganggap teori musik sebagai hal yang rumit dan membosankan. Padahal, bagi seorang pemain gitar, teori harmoni musik adalah **peta navigasi GPS** yang menjelaskan mengapa susunan akor tertentu terdengar indah bersama, bagaimana cara menebak kunci lagu yang sedang diputar di radio, serta bagaimana mentransposisi nada secara instan [18, 54, 89, 131].

Bab ini membedah teori harmonisasi skala diatonis mayor dan minor, sistem penomoran internasional (*Roman Numeral Analysis* & *Nashville Number System*), visualisasi Kompas Musik **Circle of Fifths**, serta geometri navigasi fretboard [3, 17, 48, 61, 89, 130].

---

## 4.1 Harmonisasi Skala Diatonis & Keluarga Akor (Chord Family)

Sebuah skala mayor terikat oleh formula jarak interval laras: **Whole - Whole - Half - Whole - Whole - Whole - Half** (1 - 1 - ½ - 1 - 1 - 1 - ½) [17, 122, 125]. 

Jika kita membangun akor bertumpuk interval nada ke-3 (*triad*) di atas setiap 7 tingkatan nada pada skala mayor, kita akan menghasilkan urutan jenis akor yang **selalu konstan dan identik di kunci nada dasar apa pun** [18, 44, 89]:

```text
               RUMUS ARSITEKTUR KELUARGA AKOR DIATONIS MAYOR
               
 Degree :   I        ii       iii       IV        V        vi       vii°
 Type   : Major    minor    minor     Major     Major    minor    diminished
 NNS    :   1        2m       3m        4         5        6m        7dim
```

### 1. Keluarga Akor Kunci C Major (C Major Chord Family)
Skala C Major terdiri dari nada: **C - D - E - F - G - A - B** (tanpa nada kres `#` atau mol `♭`) [18, 60, 89]:

| Tingkatan Degree | Roman Numeral | Nashville Number | Nama Akor | Komposisi Triad Nada | Fungsi Harmoni |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **Tingkat 1** | **I** | **1** | **C Major** | C - E - G | **Tonic (Home / Rest)** |
| **Tingkat 2** | **ii** | **2m** | **D minor** | D - F - A | **Subdominant (Away)** |
| **Tingkat 3** | **iii** | **3m** | **E minor** | E - G - B | **Tonic Extension** |
| **Tingkat 4** | **IV** | **4** | **F Major** | F - A - C | **Subdominant (Away)** |
| **Tingkat 5** | **V** | **5** | **G Major** | G - B - D | **Dominant (Tension / Pull)** |
| **Tingkat 6** | **vi** | **6m** | **A minor** | A - C - E | **Relative Minor / Tonic** |
| **Tingkat 7** | **vii°** | **7dim** | **B diminished** | B - D - F | **Dominant Tension** |

### 2. Keluarga Akor Kunci G Major (G Major Chord Family)
Skala G Major memiliki 1 nada kres (F#): **G - A - B - C - D - E - F#** [18, 60, 89]:
*   `I` = G Major | `ii` = A minor | `iii` = B minor | `IV` = C Major | `V` = D Major | `vi` = E minor | `vii°` = F# diminished [18, 89].

---

## 4.2 Akor Relatif Minor & Skala Aeolian

Setiap kunci skala mayor memiliki **Keluarga Akor Relatif Minor** (*Relative Minor*) yang terletak tepat pada **tingkatan nada ke-6 (`vi`)**, atau berjarak **1.5 laras (3 fret) ke bawah** dari nada dasar mayornya [17, 66, 129, 130].

```text
 Hubungan Relatif:
   * Kunci C Major  ───► Relative Minor = A minor (A Aeolian) [Sama-sama tanpa kres/mol]
   * Kunci G Major  ───► Relative Minor = E minor (E Aeolian) [Sama-sama memiliki 1 kres (F#)]
```

### Urutan Akor Diatonis Natural Minor (Natural Minor Chord Family)
Ketika lagu berada dalam tangga nada Natural Minor, urutan akor diatonisnya bergeser menjadi [17, 66, 137]:

```text
 NNS Minor:   1m       2dim      3        4m       5m       6        7
 RNA Minor:   i        ii°      III       iv       v       VI       VII
 Type     : minor   diminished Major   minor    minor    Major    Major
```
*   *Contoh pada Kunci A Natural Minor:* `i` = Am, `ii°` = Bdim, `III` = C, `iv` = Dm, `v` = Em, `VI` = F, `VII` = G [17, 66].

---

## 4.3 Roman Numeral Analysis (RNA) & Nashville Number System (NNS)

Untuk berkomunikasi secara efisien dengan musisi lain di atas panggung atau studio tanpa terbatas pada nama huruf kunci tertentu, musisi profesional mengkonversi akor menjadi notasi angka [61, 89, 102, 137].

```text
              PERBANDINGAN NOTASI TEORI MUSIK
              
Skala C Major :  C      Dm     Em     F      G      Am     Bdim
RNA Notation  :  I      ii     iii    IV     V      vi     vii°
NNS Notation  :  1      2m     3m     4      5      6m     7dim
```

### Matriks Progresi Akor Universal Populer

1.  **Traditional Backbone Progression (`1 - 4 - 5` / `I - IV - V`):**
    *   *Kunci C:* C - F - G
    *   *Kunci G:* G - C - D
    *   *Fungsi:* Progresi dasar musik Folk, Blues, Country, dan Rock n Roll klasik [61, 89, 102].
2.  **Modern Pop Chassis (`1 - 5 - 6m - 4` / `I - V - vi - IV`):**
    *   *Kunci C:* C - G - Am - F
    *   *Kunci G:* G - D - Em - C
    *   *Fungsi:* Progresi paling populer di dunia yang digunakan pada ribuan lagu pop modern (seperti *Let It Be*, *Perfect*, *I'm Yours*) [21, 89, 102].
3.  **Jazz Standard Cadence (`2m - 5 - 1` / `ii - V - I`):**
    *   *Kunci C:* Dm - G - C
    *   *Kunci G:* Am - D - G
    *   *Fungsi:* Kadensi resolusi paling halus dalam musik Jazz dan Pop kontemporer [36, 61, 89].
4.  **The 12-Bar Blues Blueprint:**
    *   `| 1 | 1 | 1 | 1 | 4 | 4 | 1 | 1 | 5 | 4 | 1 | 5 |` (Menggunakan akor Dominant 7th) [36, 89].

---

## 4.4 Navigasi Kompas Musik: Circle of Fifths

Circle of Fifths (Lingkaran Kuinta) adalah diagram visual melingkar yang menyusun 12 nada kromatis berdasarkan interval kuint murni (*perfect 5th*) searah jarum jam atau kuart murni (*perfect 4th*) berlawanan jarum jam [48, 51, 54, 130, 131].

```text
                       THE CIRCLE OF FIFTHS
                            
                             C (0♯/♭)
                        Am
                   F         │         G (1♯)
                 Dm          │           Em
               ♭            │             
           Bb                │               D (2♯)
          Gm                 │                 Bm
         ♭♭                  │                 
        Eb ──────────────────┼────────────────── A (3♯)
        Cm                   │                 F#m
         ♭♭♭                 │                 
           Ab                │               E (4♯)
             Fm              │             C#m
               ♭♭♭♭          │            
                   Db        │        B (5♯)
                        B♭m     G♯m
                            F# / Gb
```

### Cara Membaca Circle of Fifths Sebagai Alat Bantu Praktis
1.  **Menentukan Jumlah Sharps & Flats:**
    *   Puncak lingkaran adalah C Major (tanpa `#` atau `♭`) [51, 130].
    *   Bergerak **searah jarum jam (Clockwise)** menambah 1 nada Kres (`#`): G (1#), D (2#), A (3#), E (4#), B (5#) [51, 130].
    *   Bergerak **berlawanan jarum jam (Counter-Clockwise)** menambah 1 nada Mol (`♭`): F (1♭), Bb (2♭), Eb (3♭), Ab (4♭) [51, 130].
2.  **Kipas Penemu Chord Family Instan:**
    *   Pilih satu kunci sasaran di lingkaran luar (misalnya **G Major**).
    *   Searah jarum jam di sebelah kanannya adalah akor **`V` (D Major)** [18, 54].
    *   Berlawanan jarum jam di sebelah kirinya adalah akor **`IV` (C Major)** [18, 54].
    *   Lingkaran dalam tepat di bawah ketiga akor tersebut adalah relatif minornya: **`vi` (Em)**, **`ii` (Am)**, dan **`iii` (Bm)** [18, 54].
    *   Akor diatonis ke-7 (`vii°`) terletak di sebelah kanan relatif minor (F#dim) [18, 54].

---

## 4.5 Geometri & Koordinat Navigasi Fretboard

Untuk menghafal lokasi nada di seluruh leher gitar tanpa harus menghafalnya satu per satu secara membabi buta, gunakan 3 hukum geometri fretboard berikut [3, 17, 31, 63, 88]:

### 1. Asimetri Interval Senar G ke B
*   Seluruh senar gitar disetem berjarak interval *Perfect 4th* (5 semitone/fret), **kecuali antar senar 3 (G) dan senar 2 (B)** yang disetem berjarak *Major 3rd* (4 semitone/fret) [28, 122].
*   *Dampak Visual:* Setiap bentuk pola akor atau skala yang melewati garis batas senar G-B harus digeser **1 fret ke arah badan gitar (ke kanan)** [28, 122].

### 2. Aturan Oktaf Diagonal (Octave Rules)
*   **Rule 2-2 (Untuk Senar 6 dan Senar 5):**
    *   Nada oktaf berjarak **2 senar ke bawah dan 2 fret ke kanan** [63].
    *   *Contoh:* Nada C di Senar 5 Fret 3 -> Oktafnya berada di Senar 3 Fret 5 [63].
*   **Rule 2-3 (Untuk Senar 4 dan Senar 3 - Melewati Batas B):**
    *   Nada oktaf berjarak **2 senar ke bawah dan 3 fret ke kanan** [63].
    *   *Contoh:* Nada C di Senar 4 Fret 10 -> Oktafnya berada di Senar 2 Fret 13 [63].

### 3. Perbandingan Sistem Skala CAGED vs Three-Notes-Per-String (3NPS)

| Fitur Analisis | Skala Sistem CAGED (5 Box Shapes) | Skala Three-Notes-Per-String (3NPS) |
| :--- | :--- | :--- |
| **Kerangka Visual** | Terikat langsung pada 5 bentuk akor CAGED [31, 88]. | Terikat pada 7 tingkatan skala diatonis [31, 88]. |
| **Jumlah Nada per Senar** | Tidak teratur (berganti antara 2 dan 3 nada) [88]. | **Konstan 3 nada per senar** pada seluruh 6 senar [31, 88]. |
| **Jangkauan Fret** | Membentuk area kotak 4–5 fret (pergeseran tangan minimal) [88]. | Membutuhkan jangkauan 5–6 fret (stretching jari lebih lebar) [88]. |
| **Keunggulan Utama** | Sangat bagus untuk arpeggio vertikal dan chord melody [30, 88]. | **Sangat optimal untuk alternate picking cepat dan legato** [31, 88]. |

---

## Ringkasan Bab 4
Dengan memahami arsitektur diatonis, notasi RNA/NNS, kompas Circle of Fifths, serta geometri oktaf, Anda memiliki pemahaman teori musik yang solid. Di **Bab 5**, kita akan menerapkan teori ini ke teknik akustik tingkat lanjut seperti Travis Picking dan Tuning DADGAD [11, 51, 91].
