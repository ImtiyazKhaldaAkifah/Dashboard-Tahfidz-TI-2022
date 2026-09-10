# 📊 Dashboard Analisis Absensi Karantina Tahfidz TI 2022

## Deskripsi Proyek
Proyek ini adalah tugas Sains Data yang bertujuan untuk mengubah data mentah log absensi kegiatan Karantina Tahfidz mahasiswa Teknik Informatika angkatan 2022 menjadi sebuah dashboard interaktif yang mudah dibaca dan dianalisis.

Tujuan utamanya adalah untuk memberikan gambaran visual mengenai tingkat partisipasi (kehadiran) dan ketidakhadiran mahasiswa dalam kegiatan tersebut per semesternya.

## 🚀 Live Demo
Anda dapat melihat dashboard yang sudah di-deploy melalui GitHub Pages di sini:
👉 **https://imtiyazkhaldaakifah.github.io/Dashboard-Tahfidz-TI-2022/**

## 🛠️ Teknologi yang Digunakan
*   **HTML5 & CSS3** (Struktur dan Styling)
*   **Tailwind CSS** (Utility-first CSS framework)
*   **Three.js** (Perpustakaan JavaScript untuk visualisasi 3D)
*   **OrbitControls.js** (Interaksi kamera pada grafik 3D)
*   **Lucide Icons** (Kumpulan ikon modern)
*   **Vanilla Tilt.js** (Efek kartu melayang)
*   **GitHub Pages** (Hosting gratis)

## 📂 Struktur Data
Data mentah absensi diolah (pre-processing) dan disaggregation menjadi struktur JSON sederhana dalam kode JavaScript (`rawData`), dengan format:
- `semester`: Label Semester
- `total`: Jumlah Mahasiswa Terdaftar
- `hadir`: Jumlah Mahasiswa Hadir
- `absen`: Jumlah Mahasiswa Absen

## 📈 Fitur Dashboard
1.  **Visualisasi 3D Bar Chart:** Menampilkan perbandingan jumlah hadir dan absen secara visual. Grafik dapat diputar, di-zoom, dan memiliki efek *glow* saat disorot (*hover*).
2.  **Tooltip Interaktif:** Menampilkan detail angka persentase kehadiran saat mouse diarahkan ke balok 3D.
3.  **Filter Semester:** Memungkinkan pengguna memfilter data berdasarkan semester tertentu.
4.  **Kartu KPI:** Ringkasan statistik total mahasiswa, total hadir, total absen, dan rata-rata persentase kehadiran.
5.  **Tabel Rekapitulasi:** Data lengkap dalam bentuk tabel dengan indikator warna (Kategori: Sangat Tinggi, Sedang, Kritis).
6.  **UI Modern & Responsif:** Tampilan antarmuka yang bersih menggunakan Glassmorphism style.

## 👨‍💻 Cara Menjalankan Secara Lokal
1.  Clone repositori ini:
    ```bash
    git clone https://github.com/usernamemu/nama-repositori-kalian.git
    ```
2.  Masuk ke direktori proyek.
3.  Buka file `index.html` langsung di browser Anda.

---
Dibuat sebagai tugas mata kuliah Sains Data oleh: **[Nama Kamu/NIM]**
