# Deteksi Penyakit Gigi dengan Computer Vision

## Deskripsi
Proyek ini mendeteksi 4 jenis penyakit gigi:
- Caries (Karies)
- Gingivitis
- Tooth Discoloration (Perubahan Warna Gigi)
- Ulcer (Sariawan)

## Ekstraksi Fitur (Sesuai PPT Computer Vision)
- **Fitur Warna**: RGB Histogram (768 fitur) + HSV Mean/Std (6 fitur)
- **Fitur Tekstur**: GLCM (5 fitur) + Statistik Histogram (6 fitur)
- **Fitur Bentuk**: Area, Perimeter, Circularity, Aspect Ratio, Extent, Solidity, Centroid

## Model yang Digunakan
- SVM (Akurasi: 64.20%)
- KNN (Akurasi: 50.00%)
- Random Forest (Akurasi: 69.32%)
