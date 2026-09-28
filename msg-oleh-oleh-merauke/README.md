# MSG Oleh-Oleh Khas Papua-Merauke

Website katalog dan profil toko untuk tugas kelompok mata kuliah Sistem Informasi Manajemen.
Website statis biasa (HTML dan CSS), tanpa database dan tanpa proses build.

## Isi folder

```
index.html        halaman utama (semua teks ada di sini)
css/style.css     tampilan (warna, huruf, tata letak)
images/           foto toko dan produk
```

## Cara membuka di VS Code

1. Ekstrak file zip, lalu di VS Code pilih File > Open Folder dan buka folder `msg-oleh-oleh-merauke`.
2. Pasang ekstensi **Live Server** (Ritwick Dey), lalu klik kanan `index.html` dan pilih **Open with Live Server**. Setiap kamu simpan perubahan, halaman di browser ikut terbarui.

## Yang masih perlu diisi

- **Link Facebook dan TikTok**: cari `href="#"` di bagian `class="social"` pada `index.html`, lalu ganti dengan link asli.
- **Nomor WhatsApp**: sekarang `0812-4048-2585` (dibaca dari papan toko, perlu dikonfirmasi). Ganti di dua tempat: teks nomor di bagian kontak dan angka `6281240482585` pada link `wa.me` (format 62, tanpa 0 di depan).
- **Link Google Maps**: sekarang berupa pencarian nama toko. Kalau sudah punya link lokasi toko, ganti pada tombol "Buka di Google Maps".

## Mengubah isi

- Teks: langsung edit di `index.html`.
- Foto: taruh file baru di folder `images/`, lalu ubah nama file pada tag `<img src="images/...">`.
- Warna: ada di bagian paling atas `css/style.css` (blok `:root`).

## Menghubungkan ke GitHub

Buat repository kosong di github.com, lalu di terminal VS Code (Ctrl+`) jalankan:

```
git init
git add .
git commit -m "Website MSG Oleh-Oleh"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

Ganti `USERNAME` dan `NAMA-REPO` dengan milikmu. Untuk perubahan berikutnya: `git add .`, `git commit -m "pesan"`, `git push`.

## Tayang online lewat GitHub Pages (opsional)

Di repository GitHub buka Settings > Pages, pilih deploy dari branch `main` dengan folder `/ (root)`. Setelah beberapa menit websitenya bisa dibuka lewat link yang ditampilkan di halaman itu.
