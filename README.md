# 📚 Perpustakaan SD Muhammadiyah 01 Kukusan

Website resmi perpustakaan **SD Muhammadiyah 01 Kukusan**, Depok, Jawa Barat.  
Dibangun sebagai aplikasi web statis berbasis HTML, CSS, dan JavaScript — siap di-*deploy* gratis via **GitHub Pages**.

---

## 🌐 Demo Langsung

> 🔗 **[https://[username-github].github.io/perpustakaan-sdm01-kukusan](https://github.com)**  
> *(Ganti `[username-github]` dengan username GitHub Anda setelah deploy)*

---

## ✨ Fitur Website

| Fitur | Keterangan |
|---|---|
| 🏠 Beranda | Sambutan, statistik koleksi, dan hero banner |
| 📚 Koleksi Buku | Tampilan buku terbaru dan terpopuler |
| 🔍 Cari Buku | Form pencarian buku berdasarkan judul / kategori |
| 📢 Pengumuman | Informasi kegiatan dan berita perpustakaan |
| 🕐 Jam Operasional | Tabel jadwal buka-tutup perpustakaan |
| 📍 Kontak | Alamat, telepon, email, dan informasi pustakawan |

---

## 🗂️ Struktur Repository

```
perpustakaan-sdm01-kukusan/
│
├── index.html          ← Halaman utama website
├── README.md           ← Dokumentasi repository ini
│
├── assets/             ← (Opsional) Folder untuk aset tambahan
│   ├── css/            ← File CSS terpisah (jika dipisah dari HTML)
│   ├── js/             ← File JavaScript terpisah
│   └── img/            ← Gambar / foto perpustakaan
│
└── pages/              ← (Opsional) Halaman tambahan
    ├── katalog.html    ← Halaman katalog lengkap
    ├── peminjaman.html ← Halaman formulir peminjaman
    └── kontak.html     ← Halaman kontak detail
```

---

## 🚀 Cara Deploy ke GitHub Pages

### Langkah 1 — Buat Repository Baru

1. Login ke [github.com](https://github.com)
2. Klik tombol **"New"** / **"New repository"**
3. Isi nama repository, contoh: `perpustakaan-sdm01-kukusan`
4. Pilih **Public**
5. Klik **"Create repository"**

### Langkah 2 — Upload File

**Cara A — Via Browser (mudah):**
1. Di halaman repository, klik **"uploading an existing file"**
2. Drag & drop file `index.html` dan `README.md`
3. Klik **"Commit changes"**

**Cara B — Via Git (terminal):**
```bash
git clone https://github.com/[username]/perpustakaan-sdm01-kukusan.git
cd perpustakaan-sdm01-kukusan
# Salin file index.html dan README.md ke folder ini
git add .
git commit -m "Inisialisasi website perpustakaan"
git push origin main
```

### Langkah 3 — Aktifkan GitHub Pages

1. Masuk ke **Settings** repository
2. Pilih menu **Pages** di sidebar kiri
3. Pada **Source**, pilih branch **`main`**
4. Folder pilih **`/ (root)`**
5. Klik **Save**
6. Tunggu 1–3 menit, website akan aktif di:  
   `https://[username].github.io/perpustakaan-sdm01-kukusan/`

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** — Struktur halaman
- **CSS3** — Tampilan & animasi (tanpa framework eksternal)
- **Google Fonts** — Font `Nunito` & `Playfair Display`
- **GitHub Pages** — Hosting gratis & otomatis

---

## 📋 Rencana Pengembangan

- [ ] Halaman katalog buku lengkap
- [ ] Form peminjaman buku online
- [ ] Fitur pencarian buku yang fungsional (JavaScript)
- [ ] Halaman login anggota & pustakawan
- [ ] Database buku dengan Google Sheets / Airtable
- [ ] Notifikasi batas waktu pengembalian
- [ ] Versi mobile yang lebih optimal

---

## 📞 Informasi Sekolah

| | |
|---|---|
| **Sekolah** | SD Muhammadiyah 01 Kukusan |
| **Alamat** | Jl. Kukusan Teknik, Kukusan, Kec. Beji, Kota Depok, Jawa Barat |
| **Email** | perpustakaan@sdmuh01kukusan.sch.id |
| **Jam Buka** | Senin–Kamis 07.30–13.00 · Jumat 07.30–11.00 |

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan internal **SD Muhammadiyah 01 Kukusan**.  
Hak cipta © 2026 Perpustakaan SD Muhammadiyah 01 Kukusan.

---

> 💡 *"Membaca adalah Jendela Dunia"* — Perpustakaan SDM 01 Kukusan
