# Portofolio Tanaya Awang Ranumeru

Website portofolio pribadi yang memperkenalkan siapa saya, kegiatan di luar kuliah, cita-cita, dan bidang IT yang ingin saya dalami.

**Lihat website:** https://awang-dev.github.io/

## Isi halaman

- **Tentang saya**: nama, NIM, dan tahun angkatan
- **Selain kuliah**: belajar programming, hangout bersama teman-teman, dan mengikuti intern
- **Cita-cita**: PNS dengan side job Web Dev
- **Bidang IT yang ingin diperdalam**: Web Development

## Teknologi

- HTML dan CSS (versi website yang tayang di GitHub Pages)
- PHP (versi sumber, `index.php`)

## Cara menjalankan di komputer

**Versi HTML:** buka file `index.html` langsung di browser.

**Versi PHP:**

1. Pastikan PHP sudah terpasang (bisa lewat XAMPP atau Laragon).
2. Clone repo ini, lalu masuk ke foldernya:

   ```bash
   git clone https://github.com/Awang-dev/awang-dev.github.io.git
   cd awang-dev.github.io
   ```

3. Jalankan server bawaan PHP:

   ```bash
   php -S localhost:8000
   ```

4. Buka `http://localhost:8000/index.php` di browser.

## Mengubah isi

Semua data pada versi PHP ada di bagian atas `index.php`, yaitu array `$profil`, `$kegiatan`, dan `$tech`. GitHub Pages tidak menjalankan PHP, jadi setelah mengubah `index.php`, perbarui juga `index.html` agar tampilan website ikut berubah.

## Struktur project

```
awang-dev.github.io/
├── index.html   # versi statis yang tampil di website
├── index.php    # versi sumber berbasis PHP
└── README.md
```

## Penulis

**Tanaya Awang Ranumeru**
NIM 2505090037, Akt 25
GitHub: [@Awang-dev](https://github.com/Awang-dev)
