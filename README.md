# 🧾 Aplikasi Kasir Web dengan Flask

Aplikasi kasir sederhana berbasis web menggunakan Python Flask. Mendukung fitur transaksi dengan barcode, laporan penjualan, laporan stok, akun karyawan, dan export ke Excel.

## 🚀 Fitur Utama

- 🔐 Login sistem dengan role (admin & kasir)
- 📦 Input dan manajemen stok barang
- 🔍 Scan barcode produk otomatis
- 💰 Transaksi penjualan + cetak struk
- 📊 Laporan penjualan dan stok barang
- 📥 Export laporan ke Excel (.xlsx)
- ✨ Antarmuka responsive dengan Bootstrap

---

## 🧰 Teknologi

- Python 3
- Flask
- SQLite (bisa diganti MySQL)
- Pandas + OpenPyXL (untuk export Excel)
- Bootstrap 5 (tampilan UI)

---

## 📦 Instalasi & Menjalankan Aplikasi

1. **Clone repositori:**
```bash
git clone https://github.com/username/aplikasi_kasir.git
cd aplikasi_kasir
```

2. **Buat virtual environment & install dependensi:**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. **Jalankan server:**
```bash
python app.py
```

4. **Akses di browser:**
```
http://127.0.0.1:5000/
```

---

## 🧪 Akun Default (Manual Tambah Lewat /akun)

| Username | Password | Role   |
|----------|----------|--------|
| admin    | admin123 | admin  |
| kasir1   | kasir123 | kasir  |

---

## 📤 Export Laporan

- Export laporan penjualan: `/export/penjualan`
- Export laporan stok: `/export/stok`

---

## 🖨️ Cetak Struk

Setelah transaksi, struk otomatis tampil dan langsung dicetak dengan `window.print()`.

---

## ✍️ Lisensi

Open-source, silakan dimodifikasi sesuai kebutuhan. Butuh bantuan? Buka issue atau hubungi saya!
