# Evaluation of _Levelearn_ Gamification Elements using _HEART Framework_

Repository ini berisi serangkaian file **Jupyter Notebook** (file `.ipynb`) yang digunakan untuk melakukan uji statistik pada hasil kuesioner survei mengenai pengaruh elemen gamifikasi terhadap user experience. Penelitian ini menggunakan **HEART Framework** dengan lima metrik utama: **Happiness**, **Engagement**, **Adoption**, **Retention**, dan **Task Success**.

## Struktur Repository

- `analisis_korelasi.ipynb`: Jupyter Notebook untuk menghitung dan menganalisis korelasi antara elemen gamifikasi dan aspek HEART.
- `pengujian_hipotesis.ipynb`: Jupyter Notebook yang digunakan untuk melakukan uji hipotesis statistik untuk menguji hubungan signifikan antara elemen gamifikasi dan user experience berdasarkan HEART.
- `visualisasi_hasil.ipynb`: Notebook untuk visualisasi hasil analisis statistik dan korelasi menggunakan grafik dan tabel.
- `data`: Folder yang berisi dataset hasil kuesioner survei yang digunakan dalam analisis.
- `README.md`: Dokumentasi repository ini.

## Deskripsi Penelitian

Penelitian ini bertujuan untuk menganalisis bagaimana elemen gamifikasi mempengaruhi pengalaman pengguna dalam konteks lima metrik **HEART**:

1. **Happiness**: Ukuran seberapa bahagia pengguna dengan pengalaman yang diberikan.
2. **Engagement**: Ukuran keterlibatan atau interaksi pengguna dengan elemen gamifikasi.
3. **Adoption**: Sejauh mana pengguna mengadopsi elemen gamifikasi dalam pengalaman mereka.
4. **Retention**: Kemampuan elemen gamifikasi untuk mempertahankan pengguna dalam jangka panjang.
5. **Task Success**: Kemampuan pengguna untuk menyelesaikan tugas dengan sukses menggunakan elemen gamifikasi.

Untuk mengukur pengaruh elemen gamifikasi terhadap aspek-aspek ini, analisis statistik dilakukan menggunakan berbagai metode seperti **korelasi Spearman** dan **uji hipotesis**.

## Cara Menggunakan Repository

1. **Clone Repository**  
   Untuk meng-clone repository ini ke mesin lokal Anda, jalankan perintah berikut:
   ```bash
   git clone https://github.com/username/repository_name.git

2. **Data Preparation**
   Pastikan data kuesioner survei berada dalam format yang benar dan dimuat ke dalam folder data. Data yang digunakan dalam penelitian ini adalah hasil kuesioner yang mencakup pertanyaan terkait lima metrik HEART.

3. **Run Notebook**
   Setelah menyiapkan data, Anda dapat menjalankan file-file `.ipynb` menggunakan **Jupyter Notebook** atau **Google Colab**. Berikut adalah langkah-langkah umum untuk menjalankan notebook di lokal:
   - Install **Jupyter** dengan perintah:
     ```bash
     pip install notebook
   - Jalankan server Jupyter
     ```bash
     jupyter notebook
   - Buka file `.ipynb` di browser dan jalankan sel-sel kode.
  
4. **Memahami Hasil**
   Setelah menjalankan notebook, Anda akan mendapatkan hasil analisis berupa:
   - Korelasi antara elemen gamifikasi dan aspek HEART.
   - Hasil uji hipotesis statistik untuk mengidentifikasi pengaruh yang signifikan.
   - Visualisasi grafik dan tabel untuk membantu memahami data lebih lanjut.
  
## Metode Statistik

1. **Uji Validitas**
2. **Uji Reliabilitas**
3. **Uji Korelasi Spearman**
4. **Uji Regresi Linear Berganda**
5. **Uji Perbandingan**
6. **Analisis Kualitatif**

## Prasyarat

Sebelum menjalankan notebook, pastikan Anda memiliki lingkungan Python dengan pustaka berikut yang terinstal:
- `pandas` untuk manipulasi data
- `numpy` untuk perhitungan numerik
- `scipy` untuk analisis statistik (termasuk korelasi Spearman)
- `matplotlib` dan seaborn untuk visualisasi data

Jika pustaka ini belum terinstal, Anda dapat menginstalnya menggunakan pip:

```bash
pip install pandas numpy scipy matplotlib seaborn
