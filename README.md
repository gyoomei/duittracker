# 💰 DuitTracker

**Catat pendapatan & pengeluaran bulanan — simpan otomatis, export PDF/CSV, 100% client-side.**

---

## ✨ Fitur

- 📥 Input pendapatan (harian / mingguan / bulanan)
- 📤 Input pengeluaran dengan tanggal
- 💰 Hitung total bersih otomatis per bulan
- 📅 Navigasi antar bulan
- 📊 Export CSV (bisa dibuka di Excel / Google Sheets)
- 📄 Export PDF (laporan rapi siap print)
- 💾 Data tersimpan otomatis di browser (localStorage)
- 📱 Responsive — nyaman di HP maupun desktop

## 🚀 Cara Pakai

1. Buka **[gyoomei.github.io/duittracker](https://gyoomei.github.io/duittracker)**
2. Pilih tipe (Pendapatan / Pengeluaran)
3. Isi deskripsi, jumlah, dan tanggal
4. Klik **Tambah**
5. Data otomatis tersimpan di browser kamu
6. Export CSV atau PDF kapan saja

## 🛠 Tech

- **HTML + CSS + JavaScript** vanilla — tanpa framework, tanpa backend
- **jsPDF + autoTable** untuk export PDF
- **localStorage** untuk persistence
- **Zero dependencies** — cukup buka file HTML langsung

## 📦 Deploy Sendiri

```bash
git clone https://github.com/gyoomei/duittracker.git
cd duittracker
# Buka index.html di browser, atau deploy ke Vercel / Netlify / GitHub Pages
```

## 📄 Lisensi

MIT — bebas pakai, modif, sebarin.
