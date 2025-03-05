
## Deskripsi Proyek
Proyek ini menggunakan algoritma Decision Tree Classifier untuk memprediksi apakah suatu produk perlu restock berdasarkan jumlah terjual dan stok yang tersedia. Dengan dataset giars_collections yang mengandung informasi tentang penjualan, stok, dan keuntungan. Selain itu, proyek ini juga menyertakan analisis data dan visualisasi hubungan jumlah terjual serta stok terhadap keuntungan.

## Cara Menjalankan Kode di Google Colab
1. Buka Google Colab pada chrome.
2. Unggah dataset `giars_collections.csv` ke Google Colab.
3. install pustaka yang di perlukan dengan perintah berikut:
   ```python
   !pip install pandas scikit-learn matplotlib
   ```
4. Jalankan setiap sel kode secara berurutan :
   - Membaca dataset dan menampilkan informasi awal.
   - Menangani data yang hilang dengan pengisian nilai default.
   - Menambahkan kolom baru Total Terjual dan Keuntungan.
   - Membagi dataset menjadi data training dan testing.
   - Melatih model Decision Tree Classifier.
   - Mengevaluasi model dengan akurasi dan classification report.
   - Melakukan prediksi pada data baru.
   - Menampilkan visualisasi hubungan jumlah terjual dan stok terhadap keuntungan.
5. memperiksa kembali hasil output pada setiap sel untuk memastikan model berjalan dengan baik.

