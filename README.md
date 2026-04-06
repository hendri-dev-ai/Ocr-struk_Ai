# 🚀 OCR Expense AI

OCR Expense AI adalah aplikasi berbasis Artificial Intelligence yang digunakan untuk membaca, mengekstrak, dan mengelola data pengeluaran dari nota atau invoice secara otomatis.

Aplikasi ini memanfaatkan teknologi OCR untuk mengubah gambar menjadi data terstruktur (JSON), sehingga mempermudah proses pencatatan dan analisis keuangan.

---

## ✨ Fitur Utama

- 📤 Upload Nota / Invoice (JPG, PNG)
- ⚡ Proses OCR berbasis AI
- 📊 Ekstraksi otomatis ke format JSON
- 🧾 Deteksi data penting:
  - Tanggal
  - Total belanja
  - Vendor / toko
  - Metode pembayaran
  - Diskon
  - Pajak
  - Jumlah bayar & kembalian
- 📚 Riwayat pengeluaran
- 🔍 Filter berdasarkan tanggal
- 💾 Siap integrasi ke database

---

## 🖥️ Tampilan Aplikasi

### 🔹 Upload & Proses AI
User dapat mengupload gambar nota dan langsung memprosesnya dengan AI.

### 🔹 Hasil Ekstraksi
Data hasil OCR ditampilkan dalam format JSON yang clean dan siap digunakan.

### 🔹 Riwayat Pengeluaran
Semua transaksi tersimpan dan dapat difilter berdasarkan tanggal.

---

## 🧠 Cara Kerja

1. User upload gambar nota
2. Sistem mengirim gambar ke model OCR
3. AI mengekstrak teks dan memahami struktur data
4. Output diubah menjadi JSON
5. Data ditampilkan dan disimpan ke database

---

## 🛠️ Teknologi yang Digunakan

- Frontend: HTML, CSS, JavaScript
- Backend: (opsional / sesuai implementasi kamu)
- OCR Engine: AI OCR Model (Upstage / Tesseract / lainnya)
- Database: (MySQL / Firebase / dll)

---

## 📦 Contoh Output JSON

```json
{
  "tanggal": "05.09.17",
  "total": 75300,
  "vendor": "IDM RAMOS SUPER SNO",
  "metode_pembayaran": "BCA PASPOR/SOLITAIRE-TRAID",
  "diskon": 6203,
  "pajak": 2055,
  "jumlah_bayar": 76300,
  "kembalian": 6203
}
