# SPL
# Pemetaan Suhu Permukaan Laut (SPL) Landsat 8 dengan Machine Learning

Repository ini berisi alur kerja pemetaan Suhu Permukaan Laut (SPL) berbasis
citra Landsat 8 Level-2 (ST_B10) dengan bantuan Machine Learning.

Penelitian difokuskan pada wilayah perairan pulau kecil (< 5 km) dan
digunakan untuk analisis temporal SPL tanpa data in-situ.

## Tujuan Penelitian
- Pemetaan SPL secara temporal
- Koreksi bias SPL Landsat 8
- Pengisian data SPL akibat tutupan awan (gap filling)
- Klasifikasi zona suhu laut

## Data yang Digunakan
- Landsat 8 Collection 2 Level-2 (ST_B10)
- MODIS Sea Surface Temperature (SST)

## Metodologi Singkat
1. Preprocessing citra Landsat 8 di QGIS
2. Konversi suhu dari Kelvin ke Celcius
3. Masking laut dan awan
4. Ekstraksi nilai SPL
5. Machine Learning (Random Forest Regression)
6. Pemetaan SPL terkoreksi

## Software
- QGIS
- Python (scikit-learn, pandas, numpy)

## Catatan Akademik
Model Machine Learning digunakan sebagai pendekatan koreksi dan estimasi
spasio-temporal, bukan sebagai validasi absolut lapangan.

## Author
Nama Anda  
Program Studi Ilmu Kelautan
TEST SPL
