# Analisis Dataset Produk Amazon

Proyek ini berisi notebook Python untuk eksplorasi dan persiapan dataset produk Amazon. Analisis mencakup pemeriksaan struktur data, missing values, statistik deskriptif, visualisasi, deteksi duplikasi/outlier, encoding fitur, serta percobaan model regresi untuk memprediksi rating produk.

## Dataset

File: `amazon.csv`

- Jumlah baris: 1.465
- Jumlah kolom: 16
- Target yang dicoba pada notebook: `rating`
- Contoh kolom: `product_name`, `category`, `discounted_price`, `actual_price`, `discount_percentage`, `rating`, `rating_count`, dan informasi ulasan.

> Catatan: beberapa kolom harga, persentase diskon, dan jumlah rating tersimpan sebagai teks. Kolom tersebut perlu dibersihkan dan dikonversi ke tipe numerik sebelum digunakan dalam pemodelan. Hasil model juga perlu dievaluasi setelah preprocessing yang benar.

## Struktur Repository

```text
Analisis-Dataset-Amazon/
├── amazon.csv
├── Analisis_Dataset_Amazon.ipynb
├── requirements.txt
└── README.md
```

## Cara Menjalankan

1. Unduh atau clone repository ini.
2. Pastikan Python sudah terpasang.
3. Instal library yang diperlukan:

   ```bash
   pip install -r requirements.txt
   ```

4. Buka notebook `Analisis_Dataset_Amazon.ipynb` melalui Jupyter Notebook, JupyterLab, atau Google Colab.
5. Pastikan `amazon.csv` berada di folder yang sama dengan notebook, lalu jalankan sel dari atas ke bawah.

## Library

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Tujuan

Notebook ini dibuat untuk latihan analisis data dan machine learning menggunakan dataset produk Amazon. Hasil analisis bersifat edukatif dan bukan sistem rekomendasi atau prediksi produksi.

## Author

Fadhlan Bintang Ramadhan  
NIM: 241011400759  
Program Studi: Teknik Informatika
