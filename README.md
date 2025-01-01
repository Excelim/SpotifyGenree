# ✨ Analisis Big Data pada Dataset Spotify

## 👤 Anggota Kelompok
- **Excel Bima Evansyah** (NIM: 202110370311006)
- **Muhammad Daffa** (NIM: 202110370311047)

---

## 📋 Daftar Isi
1. [Pendahuluan](#pendahuluan)
2. [Dataset yang Digunakan](#dataset-yang-digunakan)
3. [Langkah-Langkah Analisis](#langkah-langkah-analisis)
4. [Statistik dan Temuan Utama](#statistik-dan-temuan-utama)
   - [Persebaran Tingkat Popularitas](#persebaran-tingkat-popularitas)
   - [Rata-rata Popularitas Berdasarkan Genre](#rata-rata-popularitas-berdasarkan-genre)
   - [Tren Popularitas Berdasarkan Tahun Rilis](#tren-popularitas-berdasarkan-tahun-rilis)
5. [Wawasan Penting](#wawasan-penting)
6. [Keterbatasan Analisis](#keterbatasan-analisis)
7. [Saran Pengembangan](#saran-pengembangan)
8. [Kontak](#kontak)

---

## 🔍 Pendahuluan

### Pengantar: Mengapa Analisis Ini Penting?
Bayangkan dunia tanpa musik: membosankan, bukan? Musik adalah bagian penting dalam hidup kita, dan dengan kemajuan teknologi streaming seperti Spotify, kini kita dapat memahami pola mendengarkan musik lebih baik. Tapi dengan jutaan lagu di ujung jari, bagaimana kita tahu lagu mana yang paling relevan dan diminati?

### Rencana: Bagaimana Kita Mengatasi Masalah Ini?
Dalam proyek ini, kita akan menyelami data Spotify untuk menemukan pola menarik. Apa yang membuat lagu menjadi populer? Bagaimana karakteristik genre memengaruhi popularitas? Jawaban atas pertanyaan ini bisa membantu dalam membangun rekomendasi musik yang lebih baik dan playlist yang sempurna.

---

## 🔢 Dataset yang Digunakan

Dataset mencakup informasi lagu-lagu Spotify, termasuk:
- Metadata: nama lagu, artis, album, popularitas.
- Fitur audio: tempo, energy, danceability, dll.

Dataset ini diunduh dari Dropbox dan dianalisis menggunakan berbagai teknik eksplorasi data.

---

## ⚡ Langkah-Langkah Analisis

1. **Pembersihan Data**
   - Menangani nilai kosong dan data tidak valid.
   - Menghapus kolom dan data duplikat.

2. **Eksplorasi Data**
   - Statistik deskriptif dan visualisasi distribusi variabel.
   - Analisis pola popularitas berdasarkan genre, artis, dan tahun.

3. **Transformasi Data**
   - Membuat variabel baru seperti `popularity_level` dan `release_year`.

4. **Visualisasi Data**
   - Heatmaps, scatter plots, histogram, bar charts, dan line charts.

5. **Analisis Tren dan Pola**
   - Rata-rata popularitas berdasarkan genre.
   - Tren popularitas berdasarkan tahun rilis.

---

## 🔢 Statistik dan Temuan Utama

### Persebaran Tingkat Popularitas:
| Popularitas | Jumlah Lagu |
|-------------|-------------|
| Medium      | 18,295      |
| Low         | 7,237       |
| High        | 4,328       |

### Rata-rata Popularitas Berdasarkan Genre:
| Genre | Popularitas Rata-rata |
|-------|-----------------------|
| EDM   | 35.04                |
| Latin | 46.34                |
| Pop   | 47.74                |
| R&B   | 41.22                |
| Rap   | 43.22                |
| Rock  | 41.97                |

### Tren Popularitas Berdasarkan Tahun Rilis:
Lagu-lagu yang dirilis lebih baru cenderung memiliki tingkat popularitas yang lebih tinggi dibandingkan lagu lama.

---

## 🔄 Wawasan Penting
1. **Popularitas Berdasarkan Genre**: Genre "Pop" memiliki popularitas tertinggi dibanding genre lain.
2. **Tren Popularitas Berdasarkan Tahun**: Lagu baru lebih populer dibandingkan lagu lama.
3. **Korelasi Fitur Musik**: Danceability dan energy berkontribusi signifikan terhadap popularitas lagu.

---

## 🚫 Keterbatasan Analisis
1. **Keterbatasan Dataset**: Hanya mencakup lagu tertentu dari Spotify.
2. **Fokus Popularitas**: Popularitas lagu dapat dipengaruhi faktor eksternal seperti promosi.
3. **Penanganan Data Hilang**: Menggunakan median mungkin tidak sepenuhnya mencerminkan nilai sebenarnya.

---

## 🎯 Saran Pengembangan
1. **Memperkaya Dataset**:
   - Tambahkan data wilayah pendengar dan strategi promosi.
   - Sertakan informasi dari platform streaming lain.
2. **Analisis Sentimen**:
   - Gunakan lirik lagu untuk memahami dampaknya terhadap popularitas.
3. **Penerapan Machine Learning**:
   - Gunakan algoritma pembelajaran mesin untuk menemukan pola kompleks dan membangun rekomendasi lebih baik.

---

## 🌎 Kontak
Terima kasih telah membaca analisis ini! Jika ada pertanyaan atau saran, silakan hubungi kami melalui email atau repositori GitHub kami.

