# UAS_DATMIN

Anggota Kelompok:
1. 2009016010 Muhammad Akmal Rifad
2. 2009106121 Nurhidayah Anugrah


### Metode Convolutional Neural Network
Convolutional Neural Network (CNN) atau Jaringan Saraf Konvolusi adalah salah satu jenis arsitektur dalam deep learning yang secara khusus dirancang untuk memproses data gambar dan pengenalan pola visual. CNN sangat efektif dalam tugas-tugas seperti klasifikasi gambar, deteksi objek, segmentasi gambar, dan pengenalan wajah. Arsitektur CNN terdiri dari beberapa lapisan yang masing-masing memiliki fungsi khusus dalam memproses data gambar. 

Berikut proses data mining dengan algoritma CNN:
1. Pengumpulan dan Preprocessing Data

   Tahap ini melibatkan pengumpulan dataset gambar yang relevan dengan tujuan analisis. Dataset ini dapat terdiri dari gambar yang telah dilabeli dengan kelas atau kategori yang dituju. Selanjutnya, dilakukan preprocessing data seperti resizing gambar ke ukuran yang seragam, normalisasi intensitas piksel, dan pemisahan dataset menjadi data pelatihan, validasi, dan pengujian.

2. Pembuatan Model CNN

   Langkah selanjutnya adalah membangun model CNN. Model ini terdiri dari beberapa lapisan diantaranya
Konvolusi, Lapisan pertama biasanya adalah lapisan konvolusi, yang menggunakan filter atau kernel untuk mengambil fitur-fitur penting dari gambar. Filter tersebut digeser secara berulang-ulang pada gambar untuk menghasilkan peta fitur atau feature map. Pada lapisan konvolusi, fungsi aktivasi seperti ReLU (Rectified Linear Unit) dapat diterapkan untuk memperkenalkan non-linearitas ke dalam jaringan.
pooling, Lapisan pooling berfungsi untuk mengurangi dimensi peta fitur yang dihasilkan oleh lapisan konvolusi dengan mempertahankan fitur-fitur penting. Hal ini membantu mengurangi jumlah parameter yang perlu diolah oleh jaringan dan mempercepat proses pelatihan.
lapisan fully connected, hasil dari lapisan pooling dilewatkan ke lapisan flatten yang mengubah matriks peta fitur menjadi vektor satu dimensi. Vektor ini kemudian dihubungkan ke lapisan-lapisan fully connected atau densely connected layers. Lapisan-lapisan ini berperan dalam menggabungkan informasi yang lebih abstrak dari peta fitur menjadi representasi akhir yang dapat digunakan untuk klasifikasi atau tugas lainnya.Model juga dilengkapi dengan fungsi aktivasi dan fungsi loss yang sesuai dengan tujuan analisis.

3. Pelatihan Model

   Setelah model CNN dibangun, dilakukan pelatihan model menggunakan data pelatihan. Pada tahap ini, parameter model diperbarui secara iteratif dengan menggunakan metode optimasi seperti gradient descent. Tujuan pelatihan adalah untuk meminimalkan nilai loss dan meningkatkan akurasi model terhadap data pelatihan.
   
4. Validasi Model
  
   Setelah pelatihan selesai, model CNN dievaluasi menggunakan data validasi. Data validasi digunakan untuk memonitor kinerja model dan melakukan penyesuaian parameter jika diperlukan. Evaluasi dilakukan dengan menghitung matrik evaluasi seperti akurasi, presisi, recall, atau F1-score.
   
5. Pengujian Model

   Setelah model dianggap cukup baik, model CNN diuji dengan menggunakan data pengujian yang belum pernah dilihat sebelumnya. Data pengujian digunakan untuk mengukur performa model secara objektif. Hasil pengujian memberikan informasi tentang kemampuan model dalam melakukan klasifikasi atau tugas lainnya pada data yang tidak dikenal.
