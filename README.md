**Analisis dan Prediksi Penjualan Produk dengan Kecerdasan Buatan**  
**Muhamad Anwar Sanusi**  

### **Deskripsi Proyek**  
Proyek ini bertujuan untuk menerapkan kecerdasan buatan (AI) dalam menganalisis dan memprediksi penjualan produk. Langkah-langkah yang dilakukan meliputi pembuatan dataset, pembersihan data, pelatihan model AI menggunakan algoritma *Decision Tree Classifier*, serta visualisasi hasil prediksi.  

### **Tahapan Implementasi**  
1. **Pembuatan Dataset**  
   - Dataset dibuat dalam format CSV yang mencakup informasi produk, jumlah penjualan, stok, dan harga satuan.  

2. **Pembersihan dan Pengolahan Data**  
   - Data diperiksa untuk memastikan tidak ada kesalahan atau nilai yang hilang sehingga siap digunakan dalam pelatihan model AI.  

3. **Pelatihan Model AI**  
   - Algoritma *Decision Tree Classifier* digunakan untuk memprediksi apakah suatu produk perlu di-*restock* berdasarkan data penjualan yang tersedia.  

4. **Prediksi dan Visualisasi**  
   - Model yang telah dilatih digunakan untuk membuat prediksi serta menyajikan visualisasi hubungan antara jumlah produk terjual, stok yang tersedia, dan keuntungan yang diperoleh.  

### **Cara Menjalankan Kode di Google Colab**  
1. **Membuka Google Colab**  
   - Akses Google Colab melalui peramban.  
   - Pilih opsi "Unggah" dan unggah file `praktikum_ai.ipynb`.  

2. **Menjalankan Notebook**  
   - Jalankan setiap sel kode secara berurutan.  
   - Jika terdapat dependensi tambahan yang diperlukan, jalankan perintah berikut di dalam sel kode:  
     ```python
     !pip install scikit-learn
     ```  

3. **Mengakses File di Google Drive (Opsional)**  
   - Jika dataset atau model disimpan di Google Drive, hubungkan akun dengan perintah berikut:  
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
