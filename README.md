# Studi Statistik: Hubungan Sumber Informasi dengan Karakteristik Usia dan Kelas Peserta

## Deskripsi
Repositori ini berisi analisis statistik mengenai hubungan antara sumber informasi dengan karakteristik usia dan kelas peserta. Studi ini mencakup berbagai metode statistik untuk mengevaluasi distribusi data, normalitas, serta perbedaan dan hubungan antara variabel menggunakan uji statistik yang sesuai.

## Struktur Repositori
- `Uji Statistik.ipynb` - Notebook Jupyter yang berisi seluruh proses analisis statistik.
- `README.md` - Dokumentasi mengenai proyek ini.

## Metode Analisis
### 1. **Data Cleaning**
Sebelum analisis dilakukan, proses pembersihan data dilakukan untuk memastikan validitas hasil. Langkah-langkah yang dilakukan meliputi:
- Menghapus data duplikat
- Memeriksa outlier pada usia peserta menggunakan boxplot

### 2. **Uji Normalitas (Shapiro-Wilk Test)**
Untuk menentukan apakah distribusi usia peserta mengikuti distribusi normal, dilakukan uji Shapiro-Wilk. Hasil menunjukkan bahwa data berdistribusi normal karena p-value lebih besar dari 0.05.

### 3. **Uji ANOVA**
Dilakukan untuk menguji perbedaan rata-rata usia peserta berdasarkan sumber informasi. Hasil menunjukkan bahwa tidak terdapat perbedaan signifikan dalam rata-rata usia peserta berdasarkan sumber informasi yang digunakan (p-value > 0.05).

### 4. **Uji Chi-Square**
Uji ini dilakukan untuk melihat hubungan antara sumber informasi dan kelas peserta. Hasil menunjukkan bahwa tidak terdapat hubungan yang signifikan antara kedua variabel tersebut (p-value > 0.05).

## Kesimpulan
Berdasarkan hasil analisis:
1. Usia peserta berdistribusi normal.
2. Tidak ada perbedaan signifikan dalam rata-rata usia peserta berdasarkan sumber informasi yang digunakan.
3. Tidak ada hubungan signifikan antara sumber informasi dan kelas peserta.

Hasil ini menunjukkan bahwa sumber informasi yang digunakan oleh peserta tidak dipengaruhi oleh usia atau kelas mereka.

## Cara Menjalankan Notebook
1. Clone repositori ini:
   ```sh
   git clone <repo-url>
   ```
2. Install dependensi yang diperlukan:
   ```sh
   pip install -r requirements.txt
   ```
3. Jalankan notebook menggunakan Jupyter:
   ```sh
   jupyter notebook Uji Statistik.ipynb
   ```

## Lisensi
Proyek ini dilisensikan di bawah MIT License.

