![Logo](https://github.com/Jodisetiawann/Dataset-Narkotika_280_294/blob/main/Direktori%20Putusan%20MA.png)

## Authors

- [@Jodisetiawann](https://github.com/Jodisetiawann)
- [@Wildanamru](https://github.com/wildanamru)

# Proyek Data Putusan Pengadilan Negeri Jakarta Barat

Proyek ini mengumpulkan data putusan pengadilan negeri Jakarta Barat dari direktori pidana khusus yang diklasifikasikan berdasarkan jenis kasus narkotika dan psikotropika. Data ini mencakup putusan tahun 2023 dan 2024. Data ini diambil dari direktori putusan Mahkamah Agung Republik Indonesia menggunakan teknik Scraping dengan total 50 data.

## Daftar Isi
- [Latar Belakang](#latar-belakang)
- [Fitur Proyek](#fitur-proyek)
- [Data Sumber](#data-sumber)
- [Struktur Direktori](#struktur-direktori)
- [Cara Pengambilan Data](#cara-pengambilan-data)
- [Cara Penggunaan](#cara-penggunaan)
- [Lisensi](#lisensi)

## Latar Belakang
Dokumen putusan pengadilan adalah salah satu dokumen yang dapat dijadikan sebagai sumber pengetahuan sekaligus dapat dimanfaatkan sebagai dataset dalam domain Temu Kembali Informasi (TKI). Sifat dokumen ini terbuka dan tidak terikat hak atas kekayaan intelektual (HaKI).

## Fitur Proyek
- *Pengambilan Data*: Data putusan dari [direktori putusan Mahkamah Agung](https://putusan3.mahkamahagung.go.id/direktori.html) diakses dan dieksplorasi melalui Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1F08ozvpDBw4DVQTH9X835984Ig3JJv76?usp=sharing)
- *Klasifikasi Kasus*: Narkotika dan Psikotropika.
- *Periode Pengambilan Data*: Data mencakup putusan dari tahun 2023 hingga 2024, dengan total 50 putusan.
- *Penyimpanan Data*: Menyimpan data dalam bentuk PDF di direktori terstruktur dan file Excel untuk ringkasan.

## Data Sumber
Data diperoleh dari situs resmi Mahkamah Agung pada direktori berikut:  
[Direktori Putusan Pengadilan](https://putusan3.mahkamahagung.go.id/direktori.html)
Jumlah data berdasarkan tahun:
- *Tahun 2023*: 21 data putusan
- *Tahun 2024*: 29 data putusan

## Struktur Direktori
Berikut struktur direktori untuk penyimpanan data hasil pengumpulan:

## Cara Pengambilan Data
1. *Akses Situs Putusan*  
   Buka [Direktori Putusan Mahkamah Agung](https://putusan3.mahkamahagung.go.id/direktori.html).
2. *Filter dan Pilih Data*
   - Pilih direktori kasus Pidana Khusus.
   - Gunakan klasifikasi kasus narkotika dan psikotropika.
   - Pilih peradilan yang diinginkan, dalam hal ini Pengadilan Negeri Jakarta Barat (PN Jakarta Barat).
   - Tentukan tahun putusan yang sesuai, yaitu 2023 dan 2024.
3. *Jalankan Kode Berikut*
   Salin dan jalankan kode Python di lingkungan pengembangan atau gunakan Google Colab dengan menekan tombol berikut:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1F08ozvpDBw4DVQTH9X835984Ig3JJv76?usp=sharing)

## Cara Penggunaan
1. *Buka File PDF*  
   Data PDF putusan dapat diakses pada direktori Narkotika.zip.
2. *Lihat Ringkasan*  
   File overview.xlsx menyediakan ringkasan dari seluruh data yang diambil.

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE). Anda bebas untuk menggunakan, menyalin, dan memodifikasi proyek ini sesuai kebutuhan Anda, selama tetap menyertakan lisensi yang sama.

---

*Catatan*: Harap mengikuti aturan dan etika penggunaan data, serta mematuhi regulasi dari Mahkamah Agung dalam penggunaan data putusan yang diperoleh dari situs resmi mereka.
