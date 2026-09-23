
```markdown
# Bab 2: Geometri & Pemetaan Fretboard Instan

> *"Fretboard gitar bukanlah deretan fret yang acak; ia adalah sebuah matriks koordinat geometris yang logis dan konsisten jika Anda memahami rumusnya."*

---

## Poin 2.1: Memahami Asimetri Interval Fretboard (Pengecualian Senar G ke B)

Sebagian besar instrumen dawai menggunakan penalaan simetris, namun gitar memiliki satu keunikan yang sering membingungkan pemula: hubungan interval antarsenar.

### 1. Hubungan Interval Perfect Fourth (4 Semitone / 5 Fret)
Secara standar, jarak nada antara senar yang berdekatan adalah interval **Perfect Fourth (Kuart Murni)** atau setara 5 fret:
* Senar 6 (E) ke Senar 5 (A) = 5 fret
* Senar 5 (A) ke Senar 4 (D) = 5 fret
* Senar 4 (D) ke Senar 3 (G) = 5 fret
* Senar 2 (B) ke Senar 1 (E) = 5 fret

### 2. Pengecualian Kritis: Senar 3 (G) ke Senar 2 (B)
Jarak antara senar 3 ke senar 2 dituning dengan interval **Major Third (Ters Mayor)** atau hanya berjarak **4 fret**:
* Senar 3 (G) ke Senar 2 (B) = 4 fret (1 fret lebih sempit dibanding pasangan senar lainnya).

```text
               DIAGRAM PERGESERAN ASIMETRI
               
Senar 6 (E) ---> [ Jarak: 5 Fret / Perfect 4th ] ---> Senar 5 (A)
Senar 5 (A) ---> [ Jarak: 5 Fret / Perfect 4th ] ---> Senar 4 (D)
Senar 4 (D) ---> [ Jarak: 5 Fret / Perfect 4th ] ---> Senar 3 (G)
Senar 3 (G) ---> [ Jarak: 4 Fret / Major 3rd   ] ---> Senar 2 (B) <--- PERGESERAN!
Senar 2 (B) ---> [ Jarak: 5 Fret / Perfect 4th ] ---> Senar 1 (E)

```

> **💡 Dampak Permainan:** Setiap bentuk pola skala, akor, atau arpeggio yang melintasi perbatasan antara senar 3 dan senar 2 **wajib digeser maju 1 fret ke arah bodi** untuk mengompensasi selisih 1 fret tersebut.

---

## Poin 2.2: Navigasi Horizontal & Two Critical Half-Steps Rule

Sebelum menghafal nada secara vertikal, kuasai pergerakan nada secara horizontal menyusuri satu senar tunggal (*single-string navigation*).

### Hukum Jarak Nada Diatonis:

Tangga nada natural (C-D-E-F-G-A-B-C) memiliki jarak:

* **Whole-step (1 laras / lompat 2 fret):** C–D, D–E, F–G, G–A, A–B.
* **Half-step (setengah laras / geser 1 fret berdampingan):** Hanya terjadi pada dua pasangan nada kritis:
1. **B ke C** (tidak ada fret pemisah)
2. **E ke F** (tidak ada fret pemisah)



```text
PETA HORIZONTAL PADA SENAR 1 (E TINGGI):

Fret:   0     1     2     3     4     5     6     7     8     9    10    11    12
Nada:  [E] - [F] -  .  - [G] -  .  - [A] -  .  - [B] - [C] -  .  - [D] -  .  - [E]
        |     |           |           |           |     |           |           |
        +-----+           +-----------+           +-----+           +-----------+
       Half-step           Whole-step            Half-step           Whole-step
       (1 Fret)             (2 Fret)             (1 Fret)             (2 Fret)

```

> **Aturan Ingatan:** Tidak ada tanda kres/kres (#) atau mol (b) alami di antara B–C dan E–F. Di fretboard gitar, nada C selalu menempel tepat di depan B, dan nada F selalu menempel tepat di depan E.

---

## Poin 2.3: Pemetaan Vertikal Pola Oktaf (Octave Rule 2-2 & 2-3)

Pola oktaf adalah jalan pintas tercepat untuk menemukan nada yang sama pada rentang nada yang lebih tinggi di fretboard tanpa perlu menghitung nada satu per satu dari awal.

### 1. Aturan Oktaf 2-2 (Berasal dari Senar 6 dan Senar 5)

Jika nada dasar berada di senar 6 atau senar 5:

* **Rumus:** Turun **2 senar ke bawah**, lalu geser **2 fret maju ke depan**.

```text
Contoh: Menemukan Oktaf Nada G (Fret 3 Senar 6):

Senar 6 (E): ---|---|-(G)-|---|---|---  (Fret 3)
Senar 5 (A): ---|---|---|---|---|---
Senar 4 (D): ---|---|---|---|-(G)-|---  (Fret 5) <-- Turun 2 senar, maju 2 fret

```

### 2. Aturan Oktaf 2-3 (Berasal dari Senar 4 dan Senar 3)

Karena melintasi batas asimetri senar 3 ke senar 2:

* **Rumus:** Turun **2 senar ke bawah**, lalu geser **3 fret maju ke depan**.

```text
Contoh: Menemukan Oktaf Nada D (Fret 0 Senar 4):

Senar 4 (D): (D)|---|---|---|---|---  (Senar Terbuka / Fret 0)
Senar 3 (G): ---|---|---|---|---|---
Senar 2 (B): ---|---|---|-(D)|---|--- (Fret 3) <-- Turun 2 senar, maju 3 fret

```

---

## Poin 2.4: Mnemonic & Landmark Fret (Fret 3, 5, 7, 10, 12)

Alih-alih menghafal seluruh fret sekaligus, jadikan titik penanda (*fret markers/inlays*) sebagai patokan koordinat utama Anda:

| Posisi Fret | Penanda | Nada di Senar 6 (E) | Nada di Senar 5 (A) | Karakter Musikal Patokan |
| --- | --- | --- | --- | --- |
| **Fret 3** | Titik 1 | **G** | **C** | Akor terbuka C dan G fundamental |
| **Fret 5** | Titik 2 | **A** | **D** | Nada acuan penyeteman senar berikutnya |
| **Fret 7** | Titik 3 | **B** | **E** | Interval Perfect Fifth (Kuint Murni) dari nada open |
| **Fret 10** | Titik 4 | **D** | **G** | Titik transisi sebelum oktaf penuh |
| **Fret 12** | Titik Ganda | **E** | **A** | Oktaf sempurna (siklus fretboard mengulang dari awal) |

```text
PETA KOORDINAT LANDMARK SENAR 6 & 5:

Senar    Fret 0     Fret 3     Fret 5     Fret 7     Fret 10    Fret 12
6 (E)    [ E ]      [ G ]      [ A ]      [ B ]      [ D ]      [ E ]
5 (A)    [ A ]      [ C ]      [ D ]      [ E ]      [ G ]      [ A ]
Marker:               ●          ●          ●          ●         ●●

```

---

## 🧭 Latihan Harian Bab 2 (Durasi: 15 Menit)

1. **Drill Single-String (5 Menit):** Pilih satu senar (misal senar 5). Sebutkan nama-nama nada natural dari fret 0 hingga 12 secara berurutan sambil menekan fretnya. Perhatikan lompatan 1 fret khusus saat melewati B–C dan E–F.
2. **Drill Berburu Oktaf (5 Menit):** Tunjuk nada acak di senar 6, lalu dalam 2 detik temukan nada oktafnya di senar 4 menggunakan rumus oktaf 2-2. Lakukan hal yang sama dari senar 4 ke senar 2 menggunakan rumus 2-3.
3. **Drill Landmark Blindfold (5 Menit):** Tanpa melihat fretboard, rasakan posisi jari Anda langsung mendarat tepat di fret ke-5 atau fret ke-7 hanya dengan meraba titik penanda leher instrumen.

```
