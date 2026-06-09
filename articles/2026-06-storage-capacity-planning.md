# Capacity Planning Storage Backup di Lingkungan Infrastruktur Perbankan

## 1. Latar Belakang Masalah
Storage backup tumbuh setiap hari.

Sulit memperkirakan kapan storage penuh.

Management meminta proyeksi kebutuhan storage tahun depan.

---

## 2. Data Awal
| Parameter | Nilai |
|------------|--------|
| Storage tersedia | 3 TB |
| Backup harian | 8 GB |
| Retention | 365 hari |
| Growth | 4% per bulan |

---

## 3. Perhitungan
### Backup Requirement

Backup harian × retention

8 GB × 365
= 2.92 TB

Growth per bulan

Forecast 1 tahun

---

## 4. Hasil Perhitungan
Storage saat ini tidak cukup.

Diperlukan tambahan 2 TB dalam 12 bulan.

---

## 5. Lesson Learned
Capacity planning harus berbasis growth rate,
bukan kapasitas saat ini.
