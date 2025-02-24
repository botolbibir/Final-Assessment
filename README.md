# Final Assessment - Amarine Vision 2025  
**TEKNIK MENGOTAKKAN SUATU OBJEK (BOUNDING BOX)**  

# Latar Belakang  
Pada tahun 2010, Gondrong Jenius Tekkom ditunjuk sebagai researcher di Amegakurine, khususnya dalam bidang pendeteksian objek pada gambar biota laut. Namun, dengan latar belakang yang bukan berasal dari bidang tersebut, ia harus belajar dari awal bagaimana cara mendeteksi objek gambar dengan benar.  

Saat itu, riset terkait pendeteksian objek, sistem cerdas, dan pemodelan algoritma masih sangat minim. Kebanyakan penelitian hanya mengandalkan riset paper serta sumber kode yang belum terdokumentasi dengan baik.  

Hingga akhirnya, Gondrong Jenius mendapatkan inspirasi dari penelitian tahun 1967 oleh **J. McQueen**, yang memperkenalkan metode **K-Means Clustering**. Metode ini mampu mengelompokkan objek berdasarkan kesamaan tanpa harus memberi label terlebih dahulu (*no labeling before preprocessing*).  

Pada suatu hari, ketika sedang beristirahat di bawah pohon rektorat, sebuah kardus apel jatuh dari atas pohon dan mengenai kepalanya. Dari kejadian tersebut, ia mendapatkan ide untuk mendeteksi objek dengan teknik **bounding box**, yaitu dengan cara mengotakkan suatu objek dalam gambar. Dengan semangat baru, Gondrong Jenius kembali ke ruang kerja untuk mulai merancang sistem pendeteksian objek biota laut.

---

# *Tujuan Proyek*
Proyek ini bertujuan untuk membangun model pendeteksian objek berbasis visi komputer (Computer Vision) yang mampu:  
✅ Mengenali dan mengklasifikasikan objek biota laut dari citra bawah air.  
✅ Mengimplementasikan teknik bounding box untuk anotasi dataset.  
✅ Melatih model dengan dataset yang telah dianotasi.  
✅ Menguji akurasi model.  
✅ Menerapkan model dalam real time.  
