# Security Policy

## Supported Versions

Saat ini project masih dalam tahap pengembangan awal.  
Semua perbaikan bug dan pembaruan keamanan hanya akan diberikan pada versi terbaru.

| Version | Supported |
| ------- | ----------|
| 1.x     | ✅        |
| < 1.0   | ❌        |

## Reporting a Vulnerability
Jika kamu menemukan celah keamanan pada project ini, silakan laporkan dengan cara berikut:

1. **Jangan buat issue publik** di GitHub.  
2. Kirim email ke: [nasyiruddin836@gmail.com] dengan subjek **[SECURITY] Laporan Kerentanan**.  
3. Jelaskan secara detail:
   - Deskripsi masalah
   - Langkah untuk mereproduksi bug
   - Potensi dampak (contoh: akses data, bypass login, dll.)
   - Saran solusi (jika ada)

---

## Expected Process

- Kami akan membalas laporan dalam **48 jam**.  
- Jika laporan valid, kami akan memperbaiki masalah dalam **7–14 hari kerja** (atau lebih cepat jika kritis).  
- Setelah patch dirilis, reporter akan diberitahu sebelum publikasi.  
- Nama reporter dapat dicantumkan di *release note* (opsional).

---

## Notes

- Project ini **menggunakan Firebase Authentication & Firestore**, sehingga sebagian besar keamanan juga mengikuti aturan **Firebase Security Rules**.  
- Pastikan laporan hanya terkait **kode project** (frontend, query, UI, dll.) atau **aturan database**.  
Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
