# **Pemodelan Klasifikasi Status Akademik Mahasiswa Menggunakan Analisis Diskriminan dan Regresi Logistik Multinomial**

## Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasikan status akademik mahasiswa ke dalam tiga kategori, yaitu **Dropout**, **Enrolled**, dan **Graduate** menggunakan pendekatan statistik klasik. Metode yang digunakan adalah **Analisis Diskriminan** dan **Regresi Logistik Multinomial**.
Dataset yang digunakan berasal dari *UCI Machine Learning Repository* dengan judul *Predict Students Dropout and Academic Success*.

## Tujuan
- Mengimplementasikan Analisis Diskriminan dalam klasifikasi status akademik mahasiswa  
- Mengimplementasikan Regresi Logistik Multinomial untuk klasifikasi multikelas  
- Membandingkan performa kedua metode  
- Mengidentifikasi variabel yang berpengaruh terhadap keberhasilan akademik mahasiswa  

## Dataset
- Sumber: UCI Machine Learning Repository  
- Jumlah data: ± 4.424 mahasiswa  
- Variabel target:
  - Dropout  
  - Enrolled  
  - Graduate  

## Variabel yang Digunakan
- Age at enrollment  
- Admission grade  
- Previous qualification grade  
- Curricular units 1st semester approved  
- Curricular units 2nd semester approved 

## Metodologi
1. Preprocessing (standarisasi data)  
2. Uji asumsi:
   - Normalitas multivariat  
   - Homogenitas kovarians (Box’s M Test)  
   - Multikolinearitas (VIF)  
3. Pemodelan:
   - Analisis Diskriminan  
   - Regresi Logistik Multinomial  
4. Evaluasi:
   - Confusion Matrix  
   - Akurasi  

## Hasil Utama
- Tidak ditemukan multikolinearitas (VIF < 10)  
- Variabel performa semester awal paling berpengaruh  
- Model mampu mengklasifikasikan status akademik dengan baik  

## Tools & Library
- R / RStudio  
- Packages:
```r
MASS
nnet
MVN
car
biotools
ggplot2
dplyr
GGally
broom
marginaleffects
pscl
