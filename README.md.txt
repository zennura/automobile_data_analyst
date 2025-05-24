# 🚗 Analisis Korelasi Harga Mobil Berdasarkan Engine Size dan Highway-MPG

Proyek ini merupakan tugas dari bisa.ai yang bertujuan untuk menganalisis hubungan antara spesifikasi teknis mobil (engine size dan highway-mpg) terhadap harga jual kendaraan. Analisis dilakukan menggunakan Microsoft Excel dan divisualisasikan melalui scatter plot serta dilengkapi insight bisnis.

---

## 📊 Dataset
dataset bersumber dari 
File: `Automobile_data.xlsx`

Dataset berisi berbagai fitur mobil, termasuk:
- `engine-size` (ukuran mesin)
- `highway-mpg` (efisiensi bahan bakar di jalan tol)
- `price` (harga mobil)

---

## 🎯 Tujuan Analisis

- Mengetahui apakah terdapat **korelasi** antara:
  - `engine-size` dan `price`
  - `highway-mpg` dan `price`
- Memberikan insight bisnis dari visualisasi data
- Menyusun presentasi profesional untuk mendukung pengambilan keputusan

---

## 📌 Insight Utama

1. **Engine Size vs Price**  
   - Korelasi **positif kuat (+0.86)**, semakin besar ukuran mesin, harga mobil semakin mahal
   - Terdapat beberapa outlier pada segmen mobil sport atau mewah, yang memiliki engine besar dan harga sangat tinggi.
   - Mobil dengan mesin besar cenderung diposisikan sebagai produk premium. Produsen dapat menargetkan pasar kelas atas dengan menawarkan fitur mewah pada mobil bermesin besar
   - Insight: Tawarkan varian mesin besar dengan fitur eksklusif untuk meningkatkan margin keuntungan. 
   - Gunakan engine size sebagai parameter penentu dalam strategi bundling (misal: "Premium Package" untuk mesin >3.0L)

2. **Highway-MPG vs Price**  
   - Korelasi **negatif sedang-kuat (–0.69)**, semakin tinggi efisiensi bahan bakar (mpg), harga mobil cenderung lebih rendah.
   - Mobil dengan highway-mpg tinggi umumnya adalah kendaraan kecil atau hemat energi, yang menyasar segmen entry-level atau ramah lingkungan.
   - Podusen bisa menawarkan 2 lini produk seperti High-performance low-MPG untuk segmen atas dan High-efficiency high-MPG untuk segmen menengah/bawah.
   - Kembangkan lini eco-friendly atau hybrid untuk pasar sensitif harga dan efisiensi bahan bakar.

3. **Rata-Rata Variabel**  
   - Engine size: 126.91 cc  
   - Highway-mpg: 30.75 mpg  
   - Price: \$13,207.13  
   - Menunjukkan dominasi mobil kelas menengah dengan performa & efisiensi seimbang

---

## 🛠 Tools Digunakan

- Microsoft Excel (visualisasi dan analisis)
- PowerPoint (penyusunan presentasi)
- Git & GitHub (versi kontrol dan dokumentasi)

---

## 
Proyek ini bersifat pembelajaran. Jika Anda memiliki ide, insight tambahan, atau ingin menyempurnakan visualisasi, kontribusi sangat dipersilakan.