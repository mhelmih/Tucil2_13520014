# Tugas Kecil II IF2211 Strategi Algoritma
> Sebuah program untuk mencari *convex hull* dari kumpulan data titik pada bidang dua dimensi menggunakan algoritma *divide and conquer*.

## Daftar Isi
* [Informasi Umum](#informasi-umum)
* [Setup](#setup)
* [Struktur File](#struktur-file)
* [Penggunaan](#penggunaan)

## Informasi Umum
Program ini dibuat untuk memenuhi tugas Mata Kuliah IF2211 Strategi Algoritma

*Program Studi Teknik Informatika* <br />
*Sekolah Teknik Elektro dan Informatika* <br />
*Institut Teknologi Bandung* <br />

*Semester II Tahun 2021/2022*

Secara umum program ini membuka dataset yang diminta pengguna (sesuai dengan dataset yang disediakan program). Kemudian program akan mencari himpunan titik yang dapat membentuk *convex hull* dengan pendekatan *divide and conquer* lalu memvisualisasikannya dengan diagram.

## Setup
- Persyaratan dasar
    - Unduh repository ini dalam bentuk zip, kemudian ekstrak.
    - Jika ingin menjalankan program secara offline,
      - Install code editor [VSCode](https://code.visualstudio.com/download) beserta plugins [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) untuk men-support file dengan ekstensi .ipynb.
      - Install [Python 3.X](https://www.python.org/downloads/).
      - Install [Jupyter Notebook](https://jupyter.org/install).
      - Install library pandas, numpy, sklearn, dan matplotlib dengan menjalankan command di bawah ini satu per satu ke terminal windows.
      ```
      pip install pandas
      pip install numpy
      pip install -U scikit-learn
      pip install -U matplotlib
      ```
    - Jika ingin menjalankan program secara online, program dapat dibuka dengan [Google Colab](https://research.google.com/colaboratory/).
- Cara Eksekusi Program
    - Untuk mengeksekusi program secara offline,
      - Buka VSCode, kemudian buka myConvexHull.ipynb pada folder src.
      - Klik "Run All".
    - Untuk mengeksekusi program secara online,
      - Ketika sudah membuka Google Colab, pilih "Create New Notebook".
      - Kemudian pilih File > Open notebook.
      - Setelah itu pilih file myConvexHull.ipynb pada folder src.
      - Untuk menjalankan programnya, pilih Runtime > Run all.

## Struktur File
- **doc**
Laporan pengerjaan tugas.
- **src**
File program dengan ekstensi .ipynb.
- **test**
Berisi file berekstensi *.txt* yang berisi daftar dataset yang sudah disediakan pada program.

## Penggunaan
1. Eksekusi program.
2. Pada beberapa sel kode, pengguna diminta untuk memasukkan input pilihan dataset dan fitur apa yang ingin dibandingkan.
3. Tidak lama setelahnya akan muncul hasil grafik yang memvisualisasikan bentuk *convex hull* yang dicari.
4. Jika ingin mencoba dengan dataset lain yang sudah disediakan, lakukan run ulang pada programnya.

## Author
Dibuat oleh [Muhammad Helmi Hibatullah](https://github.com/mhelmih) - 13520014
