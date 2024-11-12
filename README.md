# Assignment-1-Foundation-for-Artificial-Intelligence-
# Kalkulasi Pecahan Uang Tunai & Analisis Data HRDataset

## Deskripsi Proyek
Proyek ini terdiri dari dua tugas utama yang dikembangkan dalam notebook Python (Jupyter Notebook):

1. **Kalkulasi Pecahan Uang Tunai (01_Kelompok_B_2.ipynb)**  
   Program Python ini menghitung jumlah setiap jenis pecahan uang kertas dan koin Indonesia yang diperlukan untuk penarikan dari simpanan nasabah, dengan rentang simpanan dari Rp 0 hingga Rp 1 miliar.

2. **Analisis Data & Visualisasi (01_Kelompok_B_3.ipynb)**  
   Notebook ini melakukan analisis dan visualisasi data menggunakan dataset HRDataset, dengan statistik deskriptif terkait gaji, pemutusan hubungan kerja (PHK), dan performa karyawan.

---

## Rincian Tugas

### 1. Kalkulasi Pecahan Uang Tunai
**Input**: Integer untuk simpanan nasabah (Rp 0 hingga Rp 1 miliar).  
**Output**: Jumlah setiap pecahan uang yang diperlukan dan informasi jika ada sisa saldo yang tidak bisa dicairkan.

**Aturan:**
- Mengutamakan pecahan terbesar terlebih dahulu.
- Menghitung uang kertas dan koin secara terpisah.
- Menampilkan sisa saldo yang tidak dapat dicairkan (jika ada).

**Struktur Kode:**
- **Penanganan Input**: Memastikan input berada dalam rentang yang valid.
- **Kalkulasi Pecahan**: Menghitung jumlah setiap pecahan yang dibutuhkan menggunakan loop.
- **Output**: Menampilkan rincian uang kertas, koin, dan saldo yang tersisa.

### 2. Analisis Data & Visualisasi HRDataset
**Tujuan**: Menggunakan pustaka *pandas*, *matplotlib*, dan *seaborn* untuk menganalisis dan memvisualisasikan data pada dataset HR.

**Analisis Utama:**
- **Statistik Gaji Berdasarkan Status Pernikahan & Jenis Kelamin**: Menghitung minimum, median, maksimum, dan rata-rata gaji.
- **Top-5 Alasan PHK**: Menghitung alasan PHK terbanyak menggunakan `value_counts`.
- **Skor Kinerja "Exceeds" Berdasarkan Sumber Rekrutmen**: Menghitung kinerja tinggi berdasarkan sumber rekrutmen.
- **Jumlah Manajer di Setiap Departemen**: Menghitung jumlah unik manajer di tiap departemen.
- **Rasio PHK Berdasarkan Jenis Kelamin**: Menggunakan `value_counts` untuk menghitung rasio PHK.

**Visualisasi Data**:
- **Bar Chart**: Rasio PHK berdasarkan jenis kelamin.
- **Scatter Plot**: Hubungan antara *Salary* dan *EngagementSurvey*.
- **Bar Chart**: Jumlah PHK berdasarkan departemen.
- **Pie Chart**: Persentase karyawan yang di-PHK berdasarkan posisi.
- **Boxplot**: Distribusi gaji berdasarkan status pernikahan dan status PHK.
- **Pairplot**: Hubungan antara *Salary*, *EngagementSurvey*, *EmpSatisfaction*, dan *Absences*.

---

## Cara Menjalankan Kode

1. **Buka Google Colab**.
2. **Unggah file notebook**:
   - `01_Kelompok_B_2.ipynb` untuk tugas Kalkulasi Pecahan Uang Tunai.
   - `01_Kelompok_B_3.ipynb` untuk Analisis Data HRDataset.
3. Untuk `01_Kelompok_B_3.ipynb`, pastikan dataset HR dapat diakses melalui URL yang tersedia atau dengan mengunggahnya langsung ke Colab.
