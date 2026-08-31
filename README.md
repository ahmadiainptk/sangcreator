# SANGCREATOR · Studio Guru AI

Aplikasi web single-file untuk **guru** — menghasilkan prompt AI (melalui Google Gemini) untuk membuat ringkasan materi, poster edukasi, soal, dan banyak lagi (13+ tools).

> 💡 Semua prompt di-generate oleh AI. Cukup tempel API key Gemini, langsung pakai.

## ✨ Demo

Setelah repo ini di-push, aplikasi otomatis live di:

```
https://<username>.github.io/sangcreator/
```

## 🚀 Cara Menjalankan

### Di GitHub Pages (gratis, tanpa instalasi)

1. Repo ini sudah siap. Pastikan **GitHub Pages** aktif:
   - Buka tab **Settings → Pages** di repo.
   - **Source** → pilih **Deploy from a branch**.
   - **Branch** → pilih `main` dan folder `/ (root)` → **Save**.
2. Tunggu ±1 menit, buka URL yang ditampilkan.

### Secara lokal

Cukup buka `index.html` di browser (klik dua kali), atau:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```

## 🔑 Mengisi API Key Gemini

Aplikasi ini **tidak menyimpan API key di kode** — key dimasukkan langsung dari halaman web dan disimpan di `localStorage` browser Anda (aman, tidak terlihat orang lain).

1. Dapatkan API key gratis di: **https://aistudio.google.com/app/apikey**
2. Buka aplikasinya.
3. Di panel kiri (sidebar), temukan kolom **🔑 API Key Gemini**.
4. Tempel key → klik **Simpan** (atau tekan Enter).
5. Status berubah jadi **✅ Gemini API siap digunakan** — selesai!

> Catatan: key hanya tersimpan di browser perangkat yang Anda pakai. Jika ganti perangkat/browser, tempel ulang key-nya.

## 📦 Fitur

- 13+ tools untuk pembuatan prompt materi pembelajaran
- Tema terang/gelap
- Hasil langsung bisa disalin (copy)

## ⚠️ Keamanan

Jangan commit API key asli ke repo publik. Di proyek ini key **tidak pernah** tersimpan di kode — hanya di `localStorage` browser masing-masing pengguna.
