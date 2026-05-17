# AksaraFonik 🎉
**Belajar Membaca Seru!** — Website interaktif belajar membaca untuk anak-anak.

## 📁 Struktur File

```
aksarafonik/
├── index.html        ← File utama website
├── vercel.json       ← Konfigurasi Vercel
├── .gitignore        ← File yang diabaikan Git
└── README.md         ← Dokumentasi ini
```

---

## 🚀 Cara Deploy ke GitHub + Vercel

### Langkah 1 — Buat Repository di GitHub

1. Buka [github.com](https://github.com) dan login
2. Klik tombol **"New"** (repository baru)
3. Beri nama repository, misalnya: `aksarafonik`
4. Set ke **Public** (agar bisa diconnect Vercel gratis)
5. Klik **"Create repository"**

### Langkah 2 — Upload File ke GitHub

**Cara termudah (lewat browser):**
1. Di halaman repository yang baru dibuat, klik **"uploading an existing file"**
2. Drag & drop semua file ini ke browser
3. Klik **"Commit changes"**

**Atau lewat terminal (Git):**
```bash
git init
git add .
git commit -m "Initial commit - AksaraFonik"
git branch -M main
git remote add origin https://github.com/USERNAME/aksarafonik.git
git push -u origin main
```
> Ganti `USERNAME` dengan username GitHub kamu.

---

### Langkah 3 — Deploy ke Vercel

1. Buka [vercel.com](https://vercel.com) dan login (bisa pakai akun GitHub)
2. Klik **"Add New Project"**
3. Pilih repository `aksarafonik` dari daftar
4. Vercel otomatis mendeteksi sebagai **Static Site**
5. Klik **"Deploy"** — selesai! 🎉

Website akan live di URL seperti:
`https://aksarafonik.vercel.app`

---

## 🔄 Update Website

Setiap kali kamu push perubahan ke GitHub, Vercel otomatis re-deploy.

```bash
git add .
git commit -m "Update konten"
git push
```

---

## 🌐 Custom Domain (Opsional)

Jika ingin pakai domain sendiri (misal `aksarafonik.com`):
1. Beli domain di Niagahoster, Domainesia, dll.
2. Di dashboard Vercel → **Settings → Domains**
3. Tambahkan domain dan ikuti instruksi DNS-nya

---

## 📞 Bantuan

- Dokumentasi Vercel: [vercel.com/docs](https://vercel.com/docs)
- Dokumentasi GitHub: [docs.github.com](https://docs.github.com)
