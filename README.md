# Kalkulator Nilai Perolehan Tanah

Kalkulator Nilai Perolehan Tanah adalah sebuah aplikasi web sederhana yang memungkinkan pengguna untuk menghitung nilai perolehan tanah berdasarkan dua metode: NJOP (Nilai Jual Objek Pajak) dan Manual. Aplikasi ini berguna bagi mereka yang membutuhkan perkiraan biaya pembuatan surat tanah.
Ini berbeda dengan Repo Kalkulator-Tanah-Umum karena ini memiliki fitur Custom NJOP Persen

## Hitung Manual

![image](https://github.com/MRizkiMaulana/Kalkulator-Tanah/assets/100768439/17c8cd64-1631-4003-96cf-25ec667ca715)


## Hitung NJOP

![image](https://github.com/MRizkiMaulana/Kalkulator-Tanah/assets/100768439/9544aec2-af45-4629-8584-93077661f318)


## Teknologi yang Digunakan

- **HTML**: Digunakan untuk membangun struktur dan konten halaman web.
- **CSS**: Digunakan untuk mengatur tata letak dan gaya visual halaman web.
- **JavaScript**: Digunakan untuk mengatur logika perhitungan dan interaksi pengguna pada halaman web.
- **Radio Button dan Form Handling**: Menggunakan elemen radio button dan form handling dalam HTML untuk memungkinkan pengguna memilih metode perhitungan dan mengirimkan data ke JavaScript untuk diproses.
- **Event Listeners**: Menggunakan event listeners dalam JavaScript untuk menangani aksi pengguna seperti pengiriman formulir dan mencetak hasil.
- **Print Functionality**: Menambahkan fungsi untuk mencetak hasil perhitungan menggunakan JavaScript dan `window.print()`.


## Fitur

- **Metode Hitung**: Pengguna dapat memilih antara dua metode perhitungan: NJOP atau Manual.
- **Input Data**: Pengguna diminta untuk memasukkan informasi seperti nama penjual, nama pembeli, alamat, nomor NOP SPPT, NJOP, luas tanah, dan luas bangunan.
- **Perhitungan Otomatis**: Berdasarkan input pengguna, kalkulator akan melakukan perhitungan otomatis dan menampilkan hasilnya.
- **Cetak Hasil**: Pengguna dapat mencetak hasil perhitungan untuk referensi.

## Struktur File

- **index.html**: Halaman utama yang memuat pilihan untuk menggunakan kalkulator NJOP atau Manual.
- **njop.html**: Halaman untuk kalkulator nilai perolehan tanah menggunakan metode NJOP dan juga memilih perhitungan htung-ajb atau hitung-segel.
- **nonnjop.html**: Halaman untuk kalkulator nilai perolehan tanah menggunakan metode manual dan juga memilih perhitungan htung-ajb atau hitung-segel.
- **animasi1.html**: Halaman untuk animasi Manual.
- **animasi2.html**: Halaman untuk animasi NJOP.
- **src**: Folder yang berisi file-file sumber seperti JavaScript dan CSS.
  - **js**: Folder yang berisi file JavaScript untuk logika perhitungan.
  - **css**: Folder yang berisi file CSS untuk gaya halaman.

## Cara Menggunakan

1. Buka file `index.html` menggunakan peramban web (browser) Anda.
2. Pilih metode hitung yang diinginkan (NJOP atau Manual).
3. Isi formulir dengan informasi yang diminta.
4. Pilih hitung-ajb atau hitung-segel, secara otomatis akan terpilih hitung-ajb
5. Klik tombol "Hitung" untuk melihat hasil perhitungan.
6. Opsional: Klik tombol "Cetak Hasil" untuk mencetak hasil perhitungan.

## Demo

Anda dapat melihat demo langsung dari aplikasi ini di [tautan](https://mrizkimaulana.github.io/Kalkulator-Tanah/).


