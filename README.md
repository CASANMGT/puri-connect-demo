# Puri Connect — Demo Suite

Demo statis (tanpa server, tanpa backend) untuk Puri Apartment Connect — **satu sistem, tiga permukaan**:

| Permukaan | File | Isi |
|---|---|---|
| 🧑 Aplikasi Warga | `puri_connect_prototype.html` | Tiket, SOS, pembayaran, booking, tamu/kiriman, komunitas, olahraga (mabar & kompetisi), petisi, bursa 2.0 — v3.3-sport-organizer |
| 🖥️ Operator App | `puri_console.html` | Console pengelola + tata kelola RT–RW: kotak masuk, SOS, verifikasi bayar, laporan → pekerjaan, kerja bakti, kegiatan, pengumuman, moderasi |
| 📊 Dashboard Kinerja | `puri_console.html#i-kinerja` | SLA, CSAT, volume per jenis, log aktivitas |

Mulai dari hub: **`index.html`**.

## Catatan

- **Semua data adalah contoh.** Tidak ada server, WhatsApp, OTP, atau pembayaran nyata.
- Data tersimpan di `localStorage` perangkat kamu (`puri_v2` / `puri_console_v1`); tombol **Reset data demo** mengembalikan ke kondisi awal.
- Dibangun vanilla JS + CSS dengan satu bahasa desain (Lontar Modern: Fraunces · Karla · Spline Sans Mono).
- PRD & dokumen produk: lihat `PRD_Puri_Apartment_Connect.md` dan `PRD_Admin_Operator_Dashboard.md` di repo kerja lokal.
