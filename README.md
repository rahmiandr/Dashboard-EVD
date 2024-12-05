<p align="center" style="width: 800px; height: 400px;">
  <img idth="500" height="300" src="https://raw.githubusercontent.com/rahmiandr/Dashboard-EVD/refs/heads/main/gambar/337933820_d0ed2598-ff69-459f-830e-f1a1469973ab.jpg">
</p>

<div align="center">

# Emisi CO2 Kendaraan di Kanada


[Tentang](#scroll-tentang)
•
[Informasi](#pushpin-informasi)
•
[Screenshot](#desktop_computer-screenshot)
•
[Demo](#dvd-demo)

</div>

## :bookmark_tabs: Menu

- [Tentang](#scroll-tentang)
- [Informasi](#pushpin-informasi)
- [Screenshot](#desktop_computer-screenshot)
- [Demo](#dvd-demo)
- [Deskripsi Data](#heavy_check_mark-dataset)
- [Analisis Data](mag_right-analisis)
- [Tim Pengembang](#busts_in_silhouette-tim-pengembang)

## :scroll: Tentang

<p align="justify">
Selamat datang di proyek analisis emisi CO2 Kendaraan.
Proyek ini bertujuan untuk memberikan wawasan mendalam mengenai emisi CO2 yang dihasilkan oleh kendaraan berdasarkan berbagai fitur teknisnya. Kami menggabungkan eksplorasi data dan pemodelan statistik untuk menganalisis faktor-faktor yang mempengaruhi variasi emisi CO2, seperti jenis bahan bakar, konsumsi bahan bakar, transmisi, dan lainnya. Dengan informasi yang diperoleh dari dataset yang berasal dari situs data terbuka Pemerintah Kanada, kami berharap dapat menghasilkan temuan yang bermanfaat dalam mengurangi dampak negatif kendaraan terhadap lingkungan.

Kami berkomitmen untuk menyediakan analisis yang akurat dan dapat digunakan untuk memahami emisi CO2 yang dihasilkan oleh kendaraan, serta mengembangkan model yang dapat digunakan dalam pengambilan keputusan yang lebih ramah lingkungan. Dengan pendekatan yang berbasis data, kami berupaya memberikan solusi yang lebih baik dan lebih berkelanjutan untuk sektor transportasi di masa depan. Temukan lebih banyak tentang bagaimana kendaraan mempengaruhi emisi CO2 dan bagaimana kita dapat mencapainya dengan cara yang lebih efisien dan ramah lingkungan.
</p>


## :pushpin: Informasi
<div align="justify">
Projek ini merupakan tugas akhir mata kuliah Eksplorasi dan Visualisasi Data, Program Magister Statistika dan Sains Data, IPB University. Projek ini mengambil topik tentang Emisi CO2 Kendaraan. Tugas akhir ini membahas terkait visualisasi serta menganalisis emisi CO2 pada kendaraan dengan menggunakan berbagai fitur kendaraan (seperti jenis bahan bakar, konsumsi bahan bakar, dan jenis transmisi). Hasil yang diharapkan adalah berupa adanya pemahaman lebih mendalam mengenai faktor-faktor yang mempengaruhi emisi CO2 pada kendaraan dan mengembangkan model analisis untuk memberikan wawasan yang dapat digunakan untuk mengurangi dampak lingkungan di sektor transportasi.
</div>

## :desktop_computer: Screenshot

<p align="center">
  <img width="900" height="500" src="https://raw.githubusercontent.com/rahmiandr/Dashboard-EVD/refs/heads/main/gambar/Screenshot_5.png">
</p>

## :dvd: Demo

Berikut merupakan link untuk shinnyapps atau dashboard dari projek kami: 

## :heavy_check_mark: Dataset
<div align="justify">
  
**Deskripsi Data:**
Dataset ini mencatat rincian mengenai bagaimana emisi CO2 pada kendaraan dapat bervariasi dengan berbagai fitur yang ada. Dataset ini diambil dari situs data terbuka resmi Pemerintah Kanada dan merupakan versi yang telah disusun. Data ini mencakup periode 7 tahun.

Dataset ini memiliki total 7385 baris dan 12 kolom. Terdapat beberapa singkatan yang digunakan untuk menggambarkan fitur-fitur dalam dataset ini, dan informasi lebih lanjut mengenai hal tersebut dapat ditemukan dalam link dibawah ini. Fitur-fitur dalam dataset ini mencakup model kendaraan, jenis transmisi, jenis bahan bakar, konsumsi bahan bakar, dan emisi CO2, yang memungkinkan analisis mengenai faktor-faktor yang mempengaruhi emisi CO2 kendaraan.

**Deskripsi Variabel:**
- **Model**: Menyediakan informasi tentang jenis kendaraan, termasuk:
  - 4WD/4X4: Kendaraan dengan penggerak empat roda.
  - AWD: All-wheel drive (penggerak semua roda).
  - FFV: Kendaraan fleksibel yang dapat menggunakan berbagai jenis bahan bakar.
  - SWB: Short wheelbase (jarak roda pendek).
  - LWB: Long wheelbase (jarak roda panjang).
  - EWB: Extended wheelbase (jarak roda lebih panjang).
  
- **Transmission**: Jenis transmisi kendaraan, termasuk:
  - A: Otomatis
  - AM: Manual otomatis
  - AS: Otomatis dengan pemilihan gigi
  - AV: Variabel terus-menerus
  - M: Manual
  - 3-10: Jumlah gigi transmisi kendaraan.
  
- **Fuel Type**: Jenis bahan bakar yang digunakan oleh kendaraan, antara lain:
  - X: Gasoline reguler (bensin)
  - Z: Premium gasoline (bensin premium)
  - D: Diesel
  - E: Etanol (E85)
  - N: Gas alam
  
- **Fuel Consumption**: Mengukur konsumsi bahan bakar kendaraan dalam liter per 100 km (L/100 km) dengan rating gabungan untuk kota dan jalan raya (55% kota, 45% jalan raya). Nilai ini juga dihitung dalam satuan mil per galon (mpg).
  
- **CO2 Emissions**: Emisi CO2 kendaraan yang dikeluarkan melalui knalpot, diukur dalam gram per kilometer (g/km) untuk kombinasi kota dan jalan raya.

**Sumber:** [Kaggle - CO2 Emission by Vehicles](https://www.kaggle.com/datasets/athenalan/co2-emission-by-vehicles)
</div>

## :mag_right: Analisis Data
### Korelasi
<div align="justify">
Metode korelasi digunakan untuk mengukur sejauh mana hubungan antara dua peubah. Korelasi ini dihitung menggunakan koefisien korelasi yang berkisar antara -1 dan 1. Nilai ini menunjukkan arah dan kekuatan hubungan antara dua peubah, apakah positif atau negatif.

Dalam konteks emisi CO2, korelasi dapat digunakan untuk mengukur hubungan antara konsumsi bahan bakar dan emisi CO2. Misalnya, apakah kendaraan dengan konsumsi bahan bakar yang lebih tinggi menghasilkan lebih banyak emisi CO2. Korelasi membantu kita mengetahui apakah ada pola yang dapat digunakan untuk mengurangi emisi.
</div>

### Regresi
<div align="justify">
Regresi adalah metode statistik yang digunakan untuk memodelkan hubungan antara satu atau lebih peubah independen dengan peubah dependen. Dalam analisis regresi, kita mencoba untuk memprediksi nilai peubah dependen (emisi CO2) berdasarkan peubah independen (misalnya, konsumsi bahan bakar, jenis kendaraan, dll). Regresi yang digunakan adalah regresi linear sederhana dan juga regresi linear berganda.
</div>

### ANOVA
<div align="justify">
ANOVA (Analysis of Variance) adalah metode statistik yang digunakan untuk membandingkan rata-rata dari lebih dari dua kelompok. Dengan menggunakan ANOVA, kita dapat mengetahui apakah ada perbedaan yang signifikan antara kelompok yang diuji.

Jika nilai F besar dan signifikan, ini menunjukkan bahwa ada perbedaan yang signifikan antara rata-rata kelompok. Hal ini membantu kita memahami bagaimana kelompok-kelompok dalam dataset memiliki pengaruh terhadap variabel tertentu (misalnya, emisi CO2).
</div>

## :busts_in_silhouette: Tim Pengembang
### Dosen Pengampu :
1. Dr. Anwar Fitrianto, S.Si., M.Sc
2. Dr. Ir. Erfiani, M.Si
3. L.M Risman Dwi Jumansyah S.Stat 
### Anggota Tim :
1. Rahmi Anadra - G1501231051
2. Fida Fariha Amatullah - G1501231064
3. Ghardapaty Ghaly Ghiffary - G1501231086
