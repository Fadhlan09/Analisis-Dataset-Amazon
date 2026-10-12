# Analisis Dataset Amazon

Halo! saya Fadhlan Bintang Ramadhan, Selamat datang di repository tugas mechine learning saya.

Repository ini dibuat sebagai bagian dari tugas praktikum untuk mempelajari proses analisis data menggunakan Python. Melalui project ini, saya mencoba memahami informasi yang terdapat dalam dataset Amazon, mengolah data, dan mencari pola yang dapat memberikan gambaran mengenai produk yang tersedia.

README ini dibuat untuk menjelaskan isi project, tahapan pengerjaan, tools yang digunakan, serta cara menjalankan notebook agar orang lain dapat memahami proses analisis yang dilakukan.

## Sebenarnya, Project Ini Tentang Apa?

Amazon merupakan salah satu platform e-commerce yang menyediakan berbagai macam produk. Data produk dapat menyimpan informasi yang menarik untuk dianalisis, seperti harga, rating, jumlah ulasan, dan informasi lainnya sesuai kolom yang tersedia di dalam dataset.

Melalui analisis data, informasi tersebut dapat diolah menjadi lebih mudah dipahami. Misalnya, kita dapat mempelajari persebaran harga produk, melihat hubungan antara rating dan jumlah ulasan, serta menemukan pola tertentu dari data yang tersedia.

Project ini berfokus pada proses analisis dataset menggunakan Python. Kesimpulan yang diperoleh didasarkan pada hasil pengolahan dan visualisasi data.

## Dataset yang Digunakan

Dataset yang digunakan dalam project ini adalah `amazon.csv`, yang diperoleh dari sumber Kaggle.

Dataset ini menjadi sumber data utama untuk melakukan proses analisis. Sebelum digunakan, data perlu diperiksa terlebih dahulu untuk mengetahui struktur, jenis kolom, jumlah data, serta kemungkinan adanya data kosong atau duplikat.

Informasi detail mengenai jumlah baris, jumlah kolom, dan nama kolom mengikuti isi dataset yang digunakan dalam project ini.

## Perjalanan Analisis, Tahap demi Tahap

### 1. Data Collecting dan Data Loading

Tahap pertama adalah mempersiapkan dan membaca dataset menggunakan Python. Library Pandas digunakan untuk memuat file CSV ke dalam DataFrame agar data lebih mudah diperiksa dan diolah.

**Kenapa tahap ini penting?**

Sebelum melakukan analisis, kita harus mengetahui data yang digunakan terlebih dahulu. Dengan membaca dataset, kita dapat melihat struktur data dan memastikan file berhasil dimuat dengan benar.

### 2. Data Understanding

Setelah dataset berhasil dimuat, langkah selanjutnya adalah memahami isi data. Pemeriksaan dapat dilakukan menggunakan fungsi seperti `head()`, `info()`, `shape`, dan `describe()`.

Tahap ini membantu kita mengetahui contoh isi data, jumlah baris dan kolom, tipe data, serta ringkasan statistik untuk kolom numerik.

**Kenapa tahap ini penting?**

Dengan memahami struktur data sejak awal, kita dapat menentukan langkah pengolahan yang sesuai dan mengurangi risiko kesalahan saat analisis.

### 3. Data Cleaning

Data cleaning merupakan proses memeriksa dan membersihkan data agar siap digunakan. Pemeriksaan dapat meliputi data kosong (*missing values*), data duplikat, tipe data yang tidak sesuai, dan nilai yang tidak wajar.

Penanganan dilakukan berdasarkan kondisi yang ditemukan pada dataset. Tidak semua data kosong atau nilai ekstrem harus langsung dihapus karena keputusan tersebut perlu mempertimbangkan konteks data.

**Kenapa tahap ini penting?**

Data yang tidak sesuai dapat memengaruhi hasil analisis. Oleh karena itu, proses pembersihan membantu menjaga kualitas data sebelum digunakan pada tahap berikutnya.

### 4. Exploratory Data Analysis (EDA)

Exploratory Data Analysis atau EDA merupakan tahap untuk mengenali pola dan karakteristik data melalui statistik serta visualisasi.

Pada dataset Amazon, analisis dapat diarahkan pada distribusi harga, rating produk, jumlah ulasan, atau hubungan antarvariabel jika informasi tersebut tersedia.

Visualisasi dapat menggunakan Matplotlib dan Seaborn untuk membantu menyajikan data dalam bentuk grafik.

**Kenapa tahap ini penting?**

Grafik membuat informasi lebih mudah dipahami dibandingkan hanya melihat tabel berisi banyak angka. Dari tahap ini, kita juga dapat menemukan pola yang menarik untuk dianalisis lebih lanjut.

### 5. Data Transformation

Data transformation merupakan proses mengubah format atau struktur data agar sesuai dengan kebutuhan analisis.

Contohnya adalah mengubah tipe data, menyesuaikan format angka, atau melakukan encoding dan standardisasi apabila diperlukan oleh metode yang digunakan.

Tidak semua dataset membutuhkan seluruh proses transformasi. Langkah yang dipilih harus mengikuti kondisi data dan tujuan analisis.

**Kenapa tahap ini penting?**

Transformasi membantu memastikan data memiliki format yang sesuai untuk proses pengolahan, visualisasi, maupun pemodelan jika diterapkan.

### 6. Analisis dan Interpretasi Hasil

Setelah data siap, tahap berikutnya adalah menganalisis hasil pengolahan. Hasil dapat berupa ringkasan statistik, grafik, perbandingan antarvariabel, atau pola tertentu yang ditemukan selama proses analisis.

Setiap hasil perlu dijelaskan menggunakan bahasa yang mudah dipahami agar pembaca mengetahui informasi yang disampaikan oleh data.

**Kenapa tahap ini penting?**

Analisis tidak berhenti pada pembuatan grafik. Hal yang lebih penting adalah memahami arti dari hasil yang diperoleh dan menarik kesimpulan berdasarkan data.

### 7. Kesimpulan

Tahap terakhir adalah merangkum hasil analisis dan menjelaskan informasi penting yang berhasil diperoleh dari dataset Amazon.

Kesimpulan akhir disesuaikan dengan hasil yang benar-benar muncul setelah notebook dijalankan. Dengan demikian, informasi yang disampaikan dapat dipertanggungjawabkan dan tidak hanya berdasarkan asumsi.

## Tools dan Teknologi yang Digunakan

Berikut beberapa tools dan library yang dapat digunakan dalam project ini, sesuai implementasi pada notebook:

- **Python** — bahasa pemrograman untuk melakukan analisis data.
- **Pandas** — membaca, mengolah, dan memeriksa data.
- **NumPy** — membantu operasi numerik.
- **Matplotlib** — membuat visualisasi data.
- **Seaborn** — membantu membuat grafik statistik.
- **Jupyter Notebook** — menjalankan kode serta mendokumentasikan proses analisis.

## Isi Repository

```text
Analisis-Dataset-Amazon/
├── Analisis_Dataset_Amazon.ipynb
├── amazon.csv
└── README.md
```

Penjelasan file:

- `Analisis_Dataset_Amazon.ipynb` — notebook utama yang berisi kode dan proses analisis dataset.
- `amazon.csv` — file dataset yang digunakan dalam analisis.
- `README.md` — dokumentasi project yang menjelaskan tujuan, tahapan, dan cara menjalankan analisis.

## Cara Menjalankan Project

Project ini dijalankan menggunakan Jupyter Notebook di komputer lokal.

### 1. Persiapan

Pastikan Python dan Jupyter Notebook sudah terpasang di komputer.

### 2. Download Repository

Buka repository ini di GitHub, pilih **Code → Download ZIP**, kemudian ekstrak file ZIP ke folder yang diinginkan.

### 3. Install Library

Buka Command Prompt atau terminal, kemudian jalankan perintah berikut:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Buka Jupyter Notebook

Masuk ke folder project melalui Command Prompt atau terminal, kemudian jalankan:

```bash
jupyter notebook
```

Setelah browser terbuka, pilih file `Analisis_Dataset_Amazon.ipynb` untuk membuka notebook.

### 5. Jalankan Analisis

Pastikan file `amazon.csv` berada di lokasi yang sesuai dengan kode pada notebook. Selanjutnya, jalankan setiap cell secara berurutan untuk melihat proses pengolahan data, visualisasi, dan hasil analisis.

Jika terdapat library tambahan yang digunakan dalam notebook, instal library tersebut sesuai kebutuhan.

## Catatan Pengembangan

Project ini masih dapat dikembangkan lebih lanjut, misalnya dengan menambahkan visualisasi yang lebih informatif, melakukan analisis hubungan antarvariabel, memperbaiki proses pembersihan data, atau menerapkan model Machine Learning apabila sesuai dengan tujuan project.

Pengembangan berikutnya sebaiknya didasarkan pada hasil analisis dan kebutuhan data yang sebenarnya.

## Sumber Data

Kaggle. (n.d.). *Amazon Sales Dataset*. Kaggle.

https://www.kaggle.com/code/khushipitroda/amazon




Semoga repository ini dapat menjadi dokumentasi proses pembelajaran sekaligus referensi untuk memahami dasar-dasar analisis data menggunakan Python.

Terima kasih sudah mengunjungi repository ini! 