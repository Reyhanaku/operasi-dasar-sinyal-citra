# Eksperimen Operasi Dasar pada Sinyal dan Citra
Hardi Yusuf Turyasa

## Deskripsi Singkat Project
Project ini adalah implementasi berbasis Python untuk menerapkan operasi dasar pada sinyal 1D dan citra 2D. Eksperimen ini mencakup operasi penjumlahan, penggeseran (shift), dan amplifikasi, serta pengujian sifat homogenitas dan additivitas untuk menentukan apakah suatu sistem bersifat linier. Tujuan utamanya adalah untuk menganalisis efek operasi-operasi tersebut secara teknis dan konseptual dalam konteks Pengolahan Sinyal Digital.

## Library yang Digunakan
* **NumPy:** Untuk komputasi numerik dan pembuatan matriks sinyal diskrit.
* **Matplotlib:** Untuk visualisasi plot sinyal 1D dan histogram citra.
* **OpenCV:** Untuk membaca, memanipulasi, melakukan *resizing*, dan memproses citra 2D.

## Cara Menjalankan Notebook
1. Pastikan Python 3.x sudah terinstal di sistem.
2. Clone repository ini: `git clone https://github.com/Reyhanaku/operasi-dasar-sinyal-citra`
3. Instal semua library yang dibutuhkan dengan menjalankan perintah: `pip install -r requirements.txt`
4. Buka Jupyter Notebook.
5. Buka dan jalankan seluruh *cell* secara berurutan pada file `notebook/operasi_sinyal_citra.ipynb`.

## Struktur Folder Project
```text
operasi-dasar-sinyal-citra/
|-- notebook/
|   |-- operasi_sinyal_citra.ipynb
|-- images/
|   |-- citra_yang_digunakan.jpg
|   |-- citra_kedua.jpg
|-- report/
|   |-- laporan.pdf
|-- README.md
|-- requirements.txt
