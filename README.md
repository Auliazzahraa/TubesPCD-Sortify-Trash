# 🚮 Deteksi Jenis Sampah Organik dan Anorganik Menggunakan Algoritma Decision Tree

## 📘 Deskripsi Proyek

Proyek ini merupakan bagian dari tugas mata kuliah **Pengolahan Citra Digital** di Program Studi Informatika, Telkom University. Sistem ini bertujuan untuk **mendeteksi dan mengklasifikasikan jenis sampah rumah tangga** ke dalam dua kategori utama, yaitu **organik** dan **anorganik**, menggunakan pendekatan **pengolahan citra digital** dan **algoritma Decision Tree**.

Pengelolaan sampah yang kurang optimal seringkali menjadi penyebab rendahnya efektivitas daur ulang. Sistem klasifikasi otomatis ini dirancang untuk membantu masyarakat dan lembaga pengelola lingkungan dalam menyortir sampah secara efisien, cepat, dan akurat.

---

## 🎯 Tujuan Proyek

- Mengembangkan model klasifikasi citra sampah menjadi dua kategori: organik dan anorganik.
- Mengevaluasi performa algoritma Decision Tree dalam klasifikasi berdasarkan fitur visual.
- Menyediakan antarmuka web sederhana sebagai prototipe aplikasi klasifikasi.

---

## 🧪 Metodologi

1. **Pra-pemrosesan Citra**
   - Menggunakan filter Gaussian dan median untuk mengurangi noise.
   - Peningkatan kualitas citra dengan histogram equalization dan contrast stretching.

2. **Ekstraksi Fitur**
   - Warna dominan (color histogram)
   - Tekstur (GLCM, LBP)
   - Bentuk objek (shape descriptors)

3. **Klasifikasi**
   - Pelatihan model menggunakan algoritma Decision Tree dari dataset terlabel.
   - Evaluasi dengan metrik: akurasi, precision, recall, F1-score.

4. **Antarmuka Web**
   - Upload gambar sampah → klasifikasi → tampilkan hasil dan penjelasan.
   - Tampilan minimalis hijau khas ikon tempat sampah.

---

## 📁 Struktur Folder

