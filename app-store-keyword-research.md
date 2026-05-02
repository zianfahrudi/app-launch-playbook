# App Store Keyword Research

## Tujuan

Riset keyword dipakai untuk memastikan ide app punya demand di App Store sebelum mulai build.

Fokus utamanya:

- Cari keyword yang benar-benar dicari user.
- Pilih keyword yang masih realistis untuk dimenangkan.
- Validasi apakah niche punya kompetitor, tetapi belum terlalu berat.
- Tentukan keyword utama untuk nama app, subtitle, dan metadata.

## Tools Riset

Gunakan salah satu atau kombinasikan beberapa tool berikut:

- TryAstro
- AppKittie
- AppSprint

Yang perlu dicek dari tool:

- Popularity
- Difficulty
- Competitor
- Keyword competitor
- Jumlah rating/review competitor
- Ranking app untuk keyword tertentu

## Rule Utama

Gunakan filter awal seperti ini:

```text
Popularity minimal: 40
Difficulty maksimal: 60
```

Artinya:

- Keyword dengan popularity di bawah 40 biasanya kurang menarik karena demand kecil.
- Keyword dengan difficulty di atas 60 biasanya terlalu kompetitif untuk app baru.
- Keyword ideal adalah yang popularity-nya cukup tinggi, tetapi difficulty-nya masih masuk akal.

## Step-by-Step

### 1. Tentukan Ide App

Mulai dari satu ide app yang jelas.

Contoh:

```text
Stamp Identifier
```

Jangan mulai dari nama brand. Mulai dari masalah yang ingin diselesaikan user.

### 2. Ubah Ide Menjadi Keyword

Buat keyword yang kemungkinan besar diketik user di App Store.

Contoh pola keyword:

- `[object] identifier`
- `[object] scanner`
- `[object] tracker`
- `[problem] app`
- `[task] helper`

Contoh:

```text
stamp identifier
stamp scanner
stamp value
postage stamp identifier
```

### 3. Masukkan Keyword Ke Tool

Masukkan keyword utama ke TryAstro, AppKittie, atau AppSprint.

Catat:

- Popularity
- Difficulty
- Competitor yang muncul
- Jumlah rating competitor

Gunakan rule:

```text
Popularity >= 40
Difficulty <= 60
```

Kalau keyword tidak lolos rule ini, simpan sebagai ide cadangan atau cari variasi lain.

### 4. Cek Competitor

Buka daftar app yang ranking untuk keyword tersebut.

Perhatikan:

- Berapa banyak app yang punya rating tinggi.
- Apakah top competitor terlalu kuat.
- Apakah masih ada app baru yang bisa masuk.
- Apakah kualitas app competitor masih bisa dikalahkan.
- Apakah screenshot, rating, dan positioning mereka bagus.

Keyword masih menarik jika:

- Ada competitor, berarti market terbukti.
- Tidak semua competitor punya ribuan rating.
- Ada app baru yang masih bisa ranking.
- Kualitas competitor terlihat masih bisa diperbaiki.

### 5. Ambil Keyword Dari Competitor

Lihat keyword apa saja yang dipakai competitor.

Ambil keyword yang:

- Relevan dengan app.
- Popularity minimal 40.
- Difficulty maksimal 60.
- Tidak terlalu generik.
- Tidak terlalu mirip brand/nama app competitor.

Buang keyword yang:

- Tidak relevan.
- Popularity rendah.
- Difficulty terlalu tinggi.
- Search intent-nya beda dengan fitur app.

### 6. Buat Shortlist Keyword

Kumpulkan keyword yang lolos filter ke tabel.

| Keyword | Popularity | Difficulty | Competitor | Keputusan |
|---|---:|---:|---|---|
| stamp identifier | 40+ | <= 60 | Ada | Kandidat utama |
| stamp scanner | 40+ | <= 60 | Ada | Kandidat pendukung |
| stamp value | 40+ | <= 60 | Ada | Kandidat pendukung |

Pilih:

- 1 keyword utama.
- 3 sampai 10 keyword pendukung.

### 7. Tentukan Keyword Utama

Keyword utama harus:

- Paling relevan dengan fungsi app.
- Punya popularity minimal 40.
- Punya difficulty maksimal 60.
- Tidak memakai nama brand competitor.
- Bisa dipakai secara natural di app name atau subtitle.

Contoh:

```text
stamp identifier
```

### 8. Buat Keputusan

Lanjut build jika:

- Keyword utama lolos filter.
- Ada demand yang cukup.
- Kompetisi masih bisa dilawan.
- App bisa dibuat lebih baik dari competitor.
- Positioning app jelas.

Jangan lanjut dulu jika:

- Keyword utama popularity-nya rendah.
- Difficulty terlalu tinggi.
- Competitor terlalu dominan.
- Keyword tidak cocok dengan fitur app.
- Tidak ada keyword pendukung yang menarik.

## Output Akhir

Setelah riset, minimal harus punya:

- Keyword utama.
- Keyword pendukung.
- Daftar competitor.
- Alasan keyword ini layak ditarget.
- Keputusan lanjut build atau cari ide lain.

## Template Riset

| Keyword | Popularity | Difficulty | Top Competitor | Rating Competitor | Catatan | Keputusan |
|---|---:|---:|---|---:|---|---|
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |

## Ringkasan

Cari keyword yang popularity-nya minimal 40, difficulty maksimal 60, relevan dengan masalah user, dan kompetisinya masih bisa dimenangkan.
