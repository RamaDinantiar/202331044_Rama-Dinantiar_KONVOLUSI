# Praktikum Pengolahan Citra Digital - Konvolusi Gambar

**Rama Dinantiar**
**202331044**
**Pengolahan Citra Digital C**

## Deskripsi

Repositori ini merupakan bagian dari laporan praktikum mata kuliah **Pengolahan Citra Digital** dengan topik **Konvolusi**. Laporan ini terdiri dari dua bagian utama, yaitu:

- Laporan Teori
- Laporan Praktikum (dalam format Jupyter Notebook)

## Tujuan Praktikum

1. Menerapkan operasi konvolusi pada citra digital menggunakan berbagai jenis filter, yaitu:
   - Filter Rata-rata (Mean Filter)
   - Filter Median
   - Filter Batas (Edge Detection)
2. Menerapkan filter 2D pada citra yang mengandung noise (salt & pepper, gaussian, dan speckle).
3. Membandingkan efektivitas masing-masing filter dalam mereduksi noise pada gambar.

## Ringkasan Praktikum

### 1. Persiapan Gambar

Gambar yang digunakan adalah gambar boneka (`boneka.jpg`) yang dikonversi menjadi grayscale. Gambar kemudian diberikan tiga jenis noise: **Salt & Pepper**, **Gaussian**, dan **Speckle**.

### 2. Filter 2D (Konvolusi)

Dilakukan konvolusi menggunakan kernel 3x3 untuk menampilkan efek edge detection (filter batas) pada gambar grayscale.

### 3. Penambahan Noise

Menggunakan pustaka `skimage.util.random_noise`, tiga jenis noise ditambahkan ke gambar:
- Salt & Pepper
- Gaussian
- Speckle

### 4. Penerapan Filter

Untuk masing-masing gambar noisy, diterapkan dua jenis filter:
- **Filter Rata-rata** menggunakan `cv.filter2D()`
- **Filter Median** menggunakan `cv.medianBlur()`

### 5. Visualisasi Hasil

Perbandingan antara gambar noisy, hasil filter rata-rata, dan hasil filter median ditampilkan untuk masing-masing jenis noise.

## File yang Disertakan

- `LAPORAN03_202331044_RamaDinantiar_C.ipynb` – Notebook berisi seluruh proses praktikum
- `LAPORAN03_202331044_RamaDinantiar_C.pdf` – Versi PDF dari notebook untuk keperluan pengumpulan

---

