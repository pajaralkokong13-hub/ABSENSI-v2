# 📋 Sistem Absensi 10 Kegiatan Harian & Laporan Wali Kelas (Kelas 10)

Aplikasi web ringan berbasis HTML, CSS, dan JavaScript untuk mencatat kehadiran siswa **Kelas 10** (11 murid) hingga **10 sesi kegiatan per hari**, dilengkapi tanda tangan digital guru pengisi serta rekapitulasi laporan bulanan otomatis untuk wali kelas.

## ✨ Fitur Utama
* **10 Sesi Kegiatan Per Hari (`Keg 1` – `Keg 10`):** Setiap hari mendukung 10 tabel absensi terpisah untuk mata pelajaran maupun kegiatan harian kelas.
* **Detail Kegiatan & Waktu:** Dilengkapi kolom input **Nama Kegiatan / Mata Pelajaran**, **Jam Kegiatan**, dan **Nama Guru / Pengisi** pada setiap sesi.
* **Tanda Tangan Digital Guru (TTD):** Kanvas tanda tangan interaktif berbasis layar sentuh agar guru pengajar/pengisi kegiatan dapat menandatangani absensi langsung dari HP.
* **Absensi Cepat:** Pencatatan status kehadiran (**Hadir**, **Sakit**, **Izin**, **Alpa**) dengan tombol **Hadir Semua** dalam satu klik.
* **Rekap Bulanan Otomatis:** Menghitung total sesi kegiatan dan persentase kehadiran (%) setiap siswa secara otomatis selama satu bulan penuh.
* **Generator Keterangan & Pengesahan Wali Kelas:** Menyusun narasi evaluasi bulanan secara otomatis lengkap dengan kolom **Nama Wali Kelas** dan **Nama Sekretaris/Ketua Kelas**.
* **Laporan WhatsApp Instan:** Mengirimkan rekap per kegiatan maupun laporan bulanan resmi langsung ke WhatsApp Wali Kelas atau grup kelas.

## 🚀 Cara Penggunaan
1. Buka tautan website aplikasi melalui browser HP atau laptop.
2. Pilih **Tanggal** di bagian atas, lalu pilih tombol sesi (**Keg 1** s/d **Keg 10**).
3. Isi **Nama Kegiatan**, **Jam Kegiatan**, dan **Nama Guru**, lalu catat kehadiran siswa (**H / S / I / A**).
4. Minta guru pengisi membubuhkan tanda tangan pada kotak **Tanda Tangan Guru**.
5. Di akhir bulan, buka tab **Rekap Bulanan & Wali Kelas** untuk menyalin atau mengirim laporan bulanan otomatis ke WhatsApp Wali Kelas.

## 🛠️ Teknologi yang Digunakan
* HTML5 (`Canvas API` untuk Tanda Tangan Digital)
* CSS3 (Responsive Mobile-First Design)
* Vanilla JavaScript (`LocalStorage API`)
