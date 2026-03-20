# 🛒 Manual Testing Portfolio: Tokopedia Web (End-to-End)

## 📌 Project Overview
Proyek ini mendokumentasikan proses pengujian manual (*End-to-End*) pada platform e-commerce **Tokopedia**. Pengujian difokuskan pada alur utama pengguna (*User Journey*) mulai dari pendaftaran akun hingga proses pembayaran untuk memastikan fungsionalitas dan pengalaman pengguna yang optimal.

**Objective:**
- Memvalidasi fungsionalitas fitur utama (Register, Search, Cart, Checkout).
- Mengidentifikasi celah sistem melalui *Negative Testing* dan *Boundary Value Analysis*.
- Mendokumentasikan bug temuan dengan standar profesional.

---

## 📊 Test Execution Summary
**Environment:** Windows 11 | Google Chrome v122  
**Testing Period:** Maret 2026

| Module | Test Cases | Passed | Failed | Success Rate |
| :--- | :---: | :---: | :---: | :---: |
| **Register & Login** | 8 | 8 | 0 | 100% |
| **Search & Filter** | 12 | 11 | 1 | 91.6% |
| **Product Detail & Cart** | 15 | 15 | 0 | 100% |
| **Checkout & Payment** | 17 | 16 | 1 | 94.1% |
| **TOTAL** | **52** | **50** | **2** | **96.1%** |

---

## 🐞 Bug Highlights (Major Findings)
Selama pengujian, ditemukan **2 bug** yang terdokumentasi dalam laporan:

1.  **BUG-001 (Major):** Error 404 (Page Not Found) saat mengakses produk melalui hasil pencarian karakter spesial `@#%^`.
2.  **BUG-002 (Minor):** Hasil pencarian tidak relevan (menampilkan produk acak) saat menggunakan simbol tanpa kata kunci yang valid.

---

## 📁 Dokumentasi Lengkap
Seluruh detail skenario pengujian, langkah-langkah (*test steps*), hasil aktual, dan bukti screenshot tersedia dalam file berikut:
- 📑 **[TestcaseTokopedia.xlsx](./TestcaseTokopedia.xlsx)** (Klik untuk mengunduh/melihat detail)

---

## 🛠️ Testing Methodology
- **Black Box Testing:** Menguji fungsionalitas tanpa melihat kode program.
- **Exploratory Testing:** Menjelajahi aplikasi untuk menemukan *edge cases*.
- **Negative Testing:** Menguji bagaimana sistem menangani input yang salah/tidak valid.

---
**Contact:** [Isi dengan Link LinkedIn kamu]
