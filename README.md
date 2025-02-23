# 🌊 Final Assessment - Amarine Vision 2025  
**Pendeteksian Objek pada Gambar Biota Laut**  

## 📖 Latar Belakang  
Pada tahun 2010, Gondrong Jenius Tekkom ditunjuk sebagai researcher di Amegakurine, khususnya dalam bidang pendeteksian objek pada gambar biota laut. Namun, dengan latar belakang yang bukan berasal dari bidang tersebut, ia harus belajar dari awal bagaimana cara mendeteksi objek gambar dengan benar.  

Saat itu, riset terkait pendeteksian objek, sistem cerdas, dan pemodelan algoritma masih sangat minim. Kebanyakan penelitian hanya mengandalkan riset paper serta sumber kode yang belum terdokumentasi dengan baik.  

Hingga akhirnya, Gondrong Jenius mendapatkan inspirasi dari penelitian tahun 1967 oleh **J. McQueen**, yang memperkenalkan metode **K-Means Clustering**. Metode ini mampu mengelompokkan objek berdasarkan kesamaan tanpa harus memberi label terlebih dahulu (*no labeling before preprocessing*).  

Pada suatu hari, ketika sedang beristirahat di bawah pohon rektorat, sebuah kardus apel jatuh dari atas pohon dan mengenai kepalanya. Dari kejadian tersebut, ia mendapatkan ide untuk mendeteksi objek dengan teknik **bounding box**, yaitu dengan cara mengotakkan suatu objek dalam gambar. Dengan semangat baru, Gondrong Jenius kembali ke ruang kerja untuk mulai merancang sistem pendeteksian objek biota laut.

---

## 🎯 **Tujuan Proyek**  
Proyek ini bertujuan untuk membangun model pendeteksian objek berbasis visi komputer (Computer Vision) yang mampu:  
✅ Mengenali dan mengklasifikasikan objek biota laut dari citra bawah air.  
✅ Mengimplementasikan metode bounding box untuk anotasi data.  
✅ Melatih model dengan dataset yang telah dianotasi.  
✅ Menguji akurasi model dengan berbagai parameter evaluasi.  
✅ Menerapkan model dalam lingkungan produksi.  

---

## 🏗 **Teknologi yang Digunakan**  
Proyek ini menggunakan berbagai teknologi dan pustaka pemrograman, antara lain:  

- **Python** 🐍 - Bahasa pemrograman utama.  
- **OpenCV** 📷 - Pemrosesan gambar dan deteksi objek.  
- **TensorFlow/Keras** 🤖 - Model deep learning untuk pendeteksian objek.  
- **LabelImg** 🏷 - Alat anotasi bounding box.  
- **YOLO (You Only Look Once)** 🚀 - Algoritma deteksi objek yang cepat dan efisien.  
- **Matplotlib & Seaborn** 📊 - Visualisasi hasil deteksi dan evaluasi model.  

---

## 📌 **Struktur Proyek**  
```bash
Final-Assessment-Amarine-Vision-2025/
│── dataset/                # Dataset gambar biota laut
│── annotations/            # Hasil anotasi bounding box
│── models/                 # Model yang telah dilatih
│── src/                    # Kode utama proyek
│   ├── data_preprocessing.py  # Pra-pemrosesan dataset
│   ├── model_training.py      # Skrip pelatihan model
│   ├── object_detection.py    # Skrip deteksi objek
│   ├── evaluation.py          # Evaluasi model
│── results/                # Hasil uji coba model
│── README.md               # Dokumentasi proyek
└── requirements.txt        # Daftar pustaka yang dibutuhkan
