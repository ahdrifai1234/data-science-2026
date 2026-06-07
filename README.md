# Belajar Data Science - 2026

Selamat datang di repository portofolio Data Science saya. Repository ini mendokumentasikan perjalanan belajar, eksperimen, dan tugas-tugas yang saya selesaikan sepanjang semester ini.

---

## 1. Identitas Mahasiswa
* **Nama Lengkap:** Ahmad Rifai
* **NIM:** 240401010260
* **Kelas:** IF403
* **Program Studi:** PJJ Informatika

---

## 2. Deskripsi Repository
Halo! Saya adalah seorang mahasiswa Informatika yang sedang mendalami dunia *Data Science*. Di era keterbukaan data saat ini, kemampuan untuk mengekstrak informasi, menemukan pola tersembunyi, dan membangun model prediktif adalah keterampilan yang sangat krusial. Tujuan saya mempelajari *Data Science* adalah untuk menjembatani data mentah menjadi wawasan (*insights*) yang bernilai strategis bagi pengambilan keputusan.

Repository ini berisi kumpulan *Jupyter Notebook* dari materi perkuliahan Pertemuan 1 hingga Pertemuan 7. Di dalamnya, Anda akan menemukan proses *end-to-end* proyek data berskala kecil, mulai dari tahap awal pembersihan data (*data cleaning*), eksplorasi data secara visual (*Exploratory Data Analysis*), hingga implementasi algoritma *Machine Learning* dasar untuk menyelesaikan masalah klasifikasi maupun regresi.

---

## 3. Struktur Pembelajaran (Pertemuan 1–7)

Berikut adalah daftar topik materi per pertemuan beserta tautan langsung ke berkas *notebook* masing-masing:

| Pertemuan | Topik / Pembahasan | Tautan Notebook |
| :---: | :--- | :--- |
| **01** | Pengantar Data Science & Setup Environment | [Buka Notebook](./Pertemuan_01/Notebook_01.ipynb) |
| **02** | Data Preprocessing & Manipulasi Data dengan Pandas | [Buka Notebook](./Pertemuan_02/Notebook_02.ipynb) |
| **03** | Exploratory Data Analysis (EDA) & Statistika Deskriptif | [Buka Notebook](./Pertemuan_03/Notebook_03.ipynb) |
| **04** | Visualisasi Data (Matplotlib & Seaborn) | [Buka Notebook](./Pertemuan_04/Notebook_04.ipynb) |
| **05** | Pengantar Machine Learning & Supervised Learning | [Buka Notebook](./Pertemuan_05/Notebook_05.ipynb) |
| **06** | Evaluasi Model Klasifikasi & Regresi | [Buka Notebook](./Pertemuan_06/Notebook_06.ipynb) |
| **07** | Studi Kasus Terintegrasi / Review UTS | [Buka Notebook](./Pertemuan_07/Notebook_07.ipynb) |

> *Catatan: Silakan sesuaikan nama folder dan file `.ipynb` di atas dengan struktur aktual di dalam repository Anda.*

---

## 4. Tools dan Library yang Digunakan

Proyek dan latihan di dalam repository ini dibangun menggunakan ekosistem **Python** dengan beberapa *library* utama sebagai berikut:

* **Bahasa Pemrograman:** Python 3.x
* **Manipulasi & Analisis Data:** Pandas, NumPy
* **Visualisasi Data:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Environment:** Jupyter Notebook / Google Colab

---

## 5. Cara Menjalankan Notebook

Anda dapat menjalankan *notebook* di repository ini dengan dua cara:

### Opsi A: Menjalankan Secara Lokal
1. Clone repository ini ke komputer Anda:
```bash
   git clone [https://github.com/ahdrifai1234/data-science-2026.git](https://github.com/ahdrifai1234/data-science-2026.git)

    Masuk ke Folder:
    Pindah ke direktori repository yang telah di-clone:
    
    Bash
       cd data-science-2026
    Instalasi Pustaka (Libraries):
    Pastikan Python sudah terinstal, lalu pasang semua dependensi yang diperlukan dengan perintah berikut:
    
    Bash
       pip install pandas numpy matplotlib seaborn scikit-learn notebook
    Jalankan Jupyter Notebook:
    Aktifkan server Jupyter Notebook melalui terminal:
    
    Bash
       jupyter notebook
    Setelah halaman browser terbuka, pilih folder pertemuan dan klik pada file .ipynb yang ingin Anda jalankan.
    
    Opsi B: Menjalankan Menggunakan Google Colab
    Jika Anda ingin mengeksekusi kode secara instan tanpa proses instalasi di komputer lokal:
    
    Buka layanan Google Colab.
    
    Pada jendela pop-up yang muncul, pilih tab GitHub.
    
    Masukkan URL repository Anda: https://github.com/ahdrifai1234/data-science-2026 lalu tekan tombol pencarian (Enter).
    
    Pilih branch utama (main atau master), kemudian klik pada file notebook (.ipynb) dari pertemuan yang ingin Anda pelajari.
    
    Notebook akan terbuka secara otomatis di cloud environment Google Colab dan siap dijalankan langkah demi langkah (cell-by-cell).
```





## 6. Kesimpulan Perjalanan Belajar (Pertemuan 1–7)

Rangkaian materi pada Pertemuan 1 hingga 7 memberikan pemahaman menyeluruh mengenai alur kerja (*data science workflow*) yang sistematis, mulai dari penyiapan lingkungan kerja hingga evaluasi model. Berikut adalah poin-poin penting dari perjalanan pembelajaran paruh pertama ini:

### A. Fondasi dan Eksplorasi Data (Pertemuan 1–4)
* **Setup Environment & Tools:** Membangun ekosistem kerja menggunakan Python, Jupyter Notebook, dan Google Colab sebagai perangkat utama dalam mengolah data.
* **Data Preprocessing & Manipulation:** Mempelajari cara membersihkan dataset dari *missing values*, duplikasi, atau data pencilan (*outliers*), serta melakukan transformasi data menggunakan pustaka Pandas dan NumPy.
* **Exploratory Data Analysis (EDA):** Menggunakan statistika deskriptif untuk memahami distribusi data, mendeteksi korelasi antar-variabel, dan menyajikan temuan tersebut secara visual melalui grafik interaktif menggunakan Matplotlib dan Seaborn.

### B. Implementasi Pemodelan Dasar (Pertemuan 5–7)
* **Pengenalan Machine Learning:** Memahami perbedaan mendasar antara pendekatan berbasis aturan konvensional dengan pendekatan berbasis data (*machine learning*).
* **Supervised Learning:** Mengimplementasikan algoritma dasar untuk menyelesaikan dua tipe masalah utama:
  * **Klasifikasi:** Memprediksi kategori atau label diskret pada data.
  * **Regresi:** Memprediksi nilai kontinu atau angka numerik.
* **Evaluasi Performa Model:** Memanfaatkan pustaka Scikit-Learn untuk mengukur kinerja model menggunakan metrik standar seperti *Accuracy*, *Precision*, *Recall*, *F1-Score*, maupun *Mean Squared Error* (MSE) guna memastikan model yang dibangun memiliki validitas yang baik.

### Kesimpulan Umum
Proses belajar selama tujuh pertemuan ini menegaskan bahwa *Data Science* bukan sekadar tentang penerapan algoritma yang rumit, melainkan proses iteratif yang sangat bergantung pada kualitas data (*garbage in, garbage out*). Paruh pertama ini berhasil memberikan fondasi analitis yang kuat untuk mentransformasikan data mentah menjadi informasi yang objektif demi mendukung pengambilan keputusan berbasis data (*data-driven decision making*).
