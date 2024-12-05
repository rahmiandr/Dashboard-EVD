# Asosiasi Dua Peubah Kategorik

[Tentang](#scroll-tentang)
•
[Demo](#dvd-demo)
•
[Dokumentasi](#blue_book-dokumentasi)
•
[Sumber Data](#heavy_check_mark-deskripsi-data)
•
[Tim Pengembang](#smiley_cat-tim-pengembang)
•

</div>

## :scroll: Tentang
Asosiasi dua variabel kategorik adalah hubungan antara dua variabel yang masing-masing memiliki dua atau lebih kategori. Hubungan ini dapat berupa hubungan searah, berlawanan arah, atau tidak berhubungan sama sekali.

Untuk menguji ada atau tidaknya asosiasi antara dua variabel kategorik, dapat dilakukan dengan menggunakan uji statistik, seperti uji chi-square. Uji chi-square digunakan untuk menguji apakah frekuensi observasi pada tabel kontingensi berbeda secara signifikan dari frekuensi harapan.

Jika hasil uji chi-square signifikan, maka dapat disimpulkan bahwa terdapat asosiasi antara dua variabel kategorik tersebut. Untuk mengukur kekuatan asosiasi tersebut, dapat digunakan berbagai ukuran asosiasi, seperti odds ratio, relative risk, atau koefisien gamma.

Berikut adalah beberapa contoh asosiasi antara dua variabel kategorik:

* Hubungan antara jenis kelamin dan pekerjaan.
* Hubungan antara tingkat pendidikan dan penghasilan.
* Hubungan antara ras dan tingkat kriminalitas.

Berikut adalah beberapa ukuran asosiasi yang dapat digunakan untuk mengukur asosiasi antara dua variabel kategorik:

* **Odds ratio** (OR) adalah ukuran asosiasi yang mengukur perbandingan peluang terjadinya suatu kejadian pada satu kelompok dengan peluang terjadinya kejadian tersebut pada kelompok lain.
* **Relative risk** (RR) adalah ukuran asosiasi yang mengukur perbandingan risiko terjadinya suatu kejadian pada satu kelompok dengan risiko terjadinya kejadian tersebut pada kelompok lain.

Ukuran asosiasi yang digunakan akan tergantung pada jenis asosiasi yang ingin diukur.

## :dvd: Demo

Berikut merupakan link untuk shinnyapps atau dashboard dari project kami:

https://rismandwij.shinyapps.io/AsosiasiDuaPeubahKategorik/

## :blue_book: Dokumentasi 

## Penjelasan singkat masing-masing library yang digunakan:

**1. shiny:**

* Paket shiny digunakan untuk membuat aplikasi web interaktif dengan R. Anda dapat membuat berbagai macam aplikasi, seperti dashboard, visualisasi data, dan alat interaktif lainnya.

**2. sjPlot:**

* Paket sjPlot adalah extension dari ggplot2 untuk membuat grafik dan visualisasi data statistik yang lebih spesifik. Sangat berguna untuk membuat publikasi ilmiah, presentasi, dan laporan.

**3. plotly:**

* Paket plotly digunakan untuk membuat visualisasi data interaktif menggunakan JavaScript library. Grafik yang dihasilkan dapat di-zoom, dipan, dan diputar untuk melihat data dari berbagai sudut.

**4. rhandsontable:**

* Paket rhandsontable menyediakan fungsi untuk membuat spreadsheet interaktif yang dapat digunakan dalam aplikasi web shiny. Spreadsheet ini dapat diedit oleh pengguna, dan perubahan yang dibuat akan direfleksikan di data yang diproses oleh aplikasi.

**5. tidyverse:**

* Tidyverse adalah kumpulan paket yang bekerja bersama-sama untuk manipulasi, cleaning, dan analisis data. Paket ini menyediakan berbagai fungsi untuk membuat kode R lebih ringkas dan mudah dibaca.

**6. epitoools:**

* Paket epitoools adalah kumpulan fungsi untuk epidemiologi dan statistik kesehatan. Paket ini menyediakan berbagai fungsi untuk menghitung ukuran asosiasi, uji hipotesis, dan analisis data epidemiologi.

**7. markdown:**

* Paket markdown digunakan untuk menulis dokumen yang dapat dikonversi ke berbagai format, seperti HTML, PDF, dan Word. Ini berguna untuk membuat laporan, presentasi, dan dokumentasi.

**8. knitr:**

* Paket knitr adalah ekstensi dari markdown untuk menulis dokumen yang menggabungkan kode R dan teks. Kode R akan dieksekusi dan hasilnya akan ditampilkan dalam dokumen output. Ini berguna untuk membuat laporan, presentasi, dan blog yang berisi kode R dan hasil eksekusi.

## :heavy_check_mark: Dataset
**Deskripsi Data:**
Dataset ini mencatat rincian mengenai bagaimana emisi CO2 pada kendaraan dapat bervariasi dengan berbagai fitur yang ada. Dataset ini diambil dari situs data terbuka resmi Pemerintah Kanada dan merupakan versi yang telah disusun. Data ini mencakup periode 7 tahun.

Dataset ini memiliki total 7385 baris dan 12 kolom. Terdapat beberapa singkatan yang digunakan untuk menggambarkan fitur-fitur dalam dataset ini, dan informasi lebih lanjut mengenai hal tersebut dapat ditemukan dalam link dibawah ini. Fitur-fitur dalam dataset ini mencakup model kendaraan, jenis transmisi, jenis bahan bakar, konsumsi bahan bakar, dan emisi CO2, yang memungkinkan analisis mengenai faktor-faktor yang mempengaruhi emisi CO2 kendaraan.

**Sumber:** [Kaggle - CO2 Emission by Vehicles](https://www.kaggle.com/datasets/athenalan/co2-emission-by-vehicles)


## :smiley_cat: Tim Pengembang
### Dosen Pengampu :
1. Dr. Anwar Fitrianto, S.Si., M.Sc
2. Dr. Ir. Erfiani, M.Si
3. L.M Risman Dwi Jumansyah S.Stat 
### Anggota Tim :
1. Rahmi Anadra - G1501231051
2. Fida Fariha Amatullah - G1501231064
3. Ghardapaty Ghaly Ghiffary - G1501231086
