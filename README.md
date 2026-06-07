# 🏘️ SiRT Pintar - Sistem Informasi RT 06 Cemani

**SiRT Pintar** adalah aplikasi web portal warga digital modern berbasis *single-page application* (SPA) yang dirancang untuk mendigitalkan administrasi, transparansi keuangan, dan kebersamaan warga di lingkungan RT 06 / RW 17 Ngruki, Cemani, Grogol, Sukoharjo.

---

## ✨ Fitur Utama

### 📱 Layanan Publik Warga
* **Portal Informasi Mandiri:** Akses cepat ke pengumuman terbaru, agenda RT, dan profil kepengurusan RT.
* **Ajukan Surat Online:** Permohonan Surat Domisili, SKTM, Pengantar RT, dan Surat Pindah secara online.
* **Cek Iuran Bulanan:** Transparansi status pembayaran iuran warga per kepala keluarga.
* **Musyawarah & Polling Digital:** Wadah jajak pendapat digital untuk pengambilan keputusan bersama secara demokratis.
* **Jadwal Ronda Malam:** Informasi pembagian giliran ronda malam berkala.
* **Galeri Kegiatan RT:** Dokumentasi foto momen kebersamaan warga yang terintegrasi langsung dengan Google Photos Shared Albums.

### 🔐 Panel Pengurus & Bendahara RT
* **Dashboard Statistik Real-time:** Ringkasan jumlah KK, jiwa, serta status iuran bulanan berjalan.
* **Manajemen Keuangan & Kas RT:** Pencatatan pemasukan/pengeluaran kas daerah dengan grafik visualisasi Chart.js.
* **Matriks Iuran Tahunan:** Visualisasi status pembayaran iuran 12 bulan (Jan-Des) dalam satu tahun berjalan dengan fitur klik-untuk-bayar (*Click-to-Pay*).
* **Ekspor Laporan PDF Resmi:** Ekspor laporan iuran bulanan dan matriks tahunan dengan format siap cetak (Kop Surat Resmi RT 06 & kolom tanda tangan basah pengurus).

---

## 🛠️ Stack Teknologi

* **Frontend:** HTML5 (Semantic), Vanilla CSS3 (Custom Variables, Glassmorphism, Premium Dark & Light Themes), Vanilla JavaScript (ES6+).
* **Database & Auth:** Supabase (PostgreSQL, Realtime Client SDK).
* **Grafik:** Chart.js (Visualisasi Keuangan & Partisipasi Iuran).

---

## 🚀 Cara Menjalankan

Aplikasi ini didesain sebagai *Serverless SPA*. Anda hanya perlu membuka file `index.html` langsung di browser Anda:

1. Clone repositori ini:
   ```bash
   git clone https://github.com/dany29326-prog/sirt.rt6rw7cemani.git
   ```
2. Buka berkas `index.html` menggunakan browser pilihan Anda (atau gunakan ekstensi *Live Server* di VS Code).