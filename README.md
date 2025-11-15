# Image AutoEncoder – Deep Learning Project

Repository ini berisi notebook berjudul **`Final_UjianKA_Kimi_Sholihudin_Sha_Jahan_Bashori_50423698.ipynb`** yang membahas proses pembangunan dan pelatihan **AutoEncoder** menggunakan dataset gambar untuk melakukan **rekonstruksi gambar** (image reconstruction).

Project ini menampilkan tahapan mulai dari **load data**, **visualisasi**, **pembuatan arsitektur AutoEncoder**, hingga **evaluasi performa model**.

---

## 📁 Struktur File

```
📦 Project
 ┣ 📜 Final_UjianKA...Sha_Jahan_Bashori_50423698.ipynb
 ┗ 📜 README.md
```

---

## 🚀 Tujuan Proyek

- Membangun model **AutoEncoder** dengan Keras/TensorFlow
- Melatih model menggunakan dataset gambar khusus
- Mengamati performa model dalam merekonstruksi gambar
- Melakukan iterasi training (epoch) untuk meningkatkan kualitas output

---

## 🔧 Tools & Dependencies

Pastikan telah menginstal dependensi berikut:

```bash
pip install tensorflow keras numpy matplotlib
```

Tool yang digunakan dalam notebook:

- Python 3
- TensorFlow / Keras
- Matplotlib
- NumPy

---

## 📊 Langkah Eksperimen dalam Notebook

1. **Import library**
2. **Load & preprocessing data**
3. **Visualisasi data input**
4. **Membangun model AutoEncoder**
5. **Training dalam beberapa putaran (epochs iteration)**
6. **Evaluasi & visualisasi hasil rekonstruksi**
7. **Analisis masalah dan perbaikan**

---

## 🧠 Model Training Summary

- Training dilakukan dalam **dua tahap (20 epochs + 20 epochs)**
- Model menunjukkan peningkatan hasil setelah pelatihan tambahan
- Namun terdapat catatan bahwa model **kadang kehilangan informasi spasial**

### Kendala

- Detail gambar belum sepenuhnya tajam
- Masih ada informasi hilang pada beberapa bagian citra

---

## 📷 Hasil Visualisasi

Notebook ini menampilkan perbandingan **input image vs reconstructed image** menggunakan plot bawaan Matplotlib.

---

## 💡 Pengembangan ke Depan

Untuk meningkatkan kualitas rekonstruksi, beberapa opsi:

- Menambah kapasitas model (layer & depth)
- Menggunakan **Convolutional AutoEncoder**
- Menambah dataset
- Melakukan augmentasi data
- Menggunakan optimizer dan loss function alternatif

---

## 👤 Author

**Nama:** Kimi Sholihudin Sha Jahan Bashori  
**NPM:** 50423698  

---

## 📄 Lisensi

Project ini dibuat untuk kebutuhan **final exam / tugas akademik** dan bersifat edukatif.
