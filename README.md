# ✒️ Aplikasi Tanda Tangan PDF Sederhana

<p align="center">
  <a href="https://img.shields.io/badge/license-MIT-blue.svg"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Lisensi MIT"></a>
  <a href="https://img.shields.io/badge/made%20with-HTML%2CSS%2CJS-orange.svg"><img src="https://img.shields.io/badge/made%20with-HTML%2CSS%2CJS-orange.svg" alt="Dibuat dengan HTML, CSS, JS"></a>
  <a href="https://img.shields.io/badge/deployment-GitHub%20Pages-brightgreen.svg"><img src="https://img.shields.io/badge/deployment-GitHub%20Pages-brightgreen.svg" alt="Deploy di GitHub Pages"></a>
</p>

Aplikasi web ringan untuk membubuhkan tanda tangan digital ke dokumen PDF secara cepat. Aplikasi ini sepenuhnya berjalan di sisi klien (browser) dan tidak memerlukan server backend, membuatnya sangat ringan, aman, dan mudah untuk di-deploy.

## Demo

<a href="#"><strong>Lihat Demo Langsung »</strong></a>

![Pratinjau Aplikasi](https://placehold.co/800x450/e2e8f0/4a5568?text=Animasi+Cara+Kerja+Aplikasi+(GIF))
*(Disarankan untuk mengganti gambar di atas dengan GIF yang menunjukkan cara kerja aplikasi)*

## ⚠️ Peringatan & Tanggung Jawab

Aplikasi ini dibuat untuk mempermudah alur kerja dan efisiensi. Namun, karena aplikasi ini menyangkut tanda tangan yang memiliki implikasi hukum, pengguna diharapkan untuk:

- **Menggunakan aplikasi dengan bijak dan penuh tanggung jawab.**
- **Memastikan bahwa Anda memiliki otorisasi penuh** untuk membubuhkan tanda tangan yang Anda gunakan.

**Disclaimer:** Penulis aplikasi tidak bertanggung jawab atas segala bentuk penyalahgunaan yang dilakukan oleh pihak yang tidak bertanggung jawab. Seluruh risiko dan tanggung jawab penggunaan aplikasi ini sepenuhnya ada pada pengguna.

## ✨ Fitur

- **🔐 Login Lokal:** Sistem login sederhana berbasis browser untuk membatasi akses.
- **📄 Tampilan Multi-Halaman:** Navigasi antar halaman pada dokumen PDF.
- **🪄 Penghapusan Latar Belakang Otomatis:** Latar belakang putih pada gambar tanda tangan akan otomatis dibuat transparan.
- **💾 Penyimpanan di Browser:** Tanda tangan disimpan di `localStorage`, sehingga tidak perlu diunggah berulang kali.
- **🖐️ Interaksi Drag-and-Drop:** Pindahkan dan ubah ukuran tanda tangan dengan mudah.
- **📥 Unduh Hasil:** Simpan dokumen yang sudah ditandatangani sebagai file PDF baru.

## 🚀 Cara Menggunakan

1.  Buka aplikasi melalui URL yang sudah di-deploy.

2.  Login menggunakan kredensial yang telah ditentukan:
    ```
    Username: admin
    Password: admin123
    ```
3.  Unggah tanda tangan dan dokumen PDF Anda, lalu sesuaikan posisinya.

4.  Unduh hasilnya.

## 🔧 Deployment

Aplikasi ini adalah situs statis dan dapat di-deploy dengan sangat mudah menggunakan layanan seperti GitHub Pages.

1.  **Fork/Clone Repository** ini.
2.  Buka `Settings` > `Pages` di repository Anda.
3.  Pilih `Deploy from a branch` dan gunakan branch `main` dengan folder `/root`.
4.  Aplikasi Anda akan tersedia di `https://<username>.github.io/aplikasi-ttd-pdf/`.

## 🤝 Kontribusi

Kontribusi selalu diterima! Jika Anda memiliki ide untuk perbaikan atau menemukan bug, silakan buka *issue* atau buat *pull request*.

## 🙏 Ucapan Terima Kasih

Aplikasi ini dapat terwujud berkat library open-source yang luar biasa:

- [pdf.js](https://mozilla.github.io/pdf.js/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [Tailwind CSS](https://tailwindcss.com/)

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat file `LICENSE` untuk detail lebih lanjut.
