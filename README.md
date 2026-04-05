# Deteksi Penyakit Gigi dengan Computer Vision

## Deskripsi
Proyek ini mendeteksi 4 jenis penyakit gigi:
- Caries (Karies)
- Gingivitis
- Tooth Discoloration (Perubahan Warna Gigi)
- Ulcer (Sariawan)

## Ekstraksi Fitur
- **Fitur Warna**: RGB Histogram (768 fitur) + HSV Mean/Std (6 fitur)
- **Fitur Tekstur**: GLCM (5 fitur) + Statistik Histogram (6 fitur)
- **Fitur Bentuk**: Area, Perimeter, Circularity, Aspect Ratio, Extent, Solidity, Centroid

## Model yang Digunakan
- SVM (Akurasi: 64.20%)
- KNN (Akurasi: 50.00%)
- Random Forest (Akurasi: 69.32%)

## link dataset
https://drive.google.com/drive/folders/1JR1-UTfKChRBCorDIBbX9JloA0mRgPFP?usp=sharing
