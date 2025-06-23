# 🏛️ Portal Layanan – Kemenag Jawa Timur

**Portal Layanan** adalah aplikasi berbasis web yang dirancang untuk memudahkan akses publik terhadap berbagai layanan di lingkungan Kementerian Agama Kabupaten/Kota Provinsi Jawa Timur. Website ini merupakan bagian dari inisiatif transparansi dan digitalisasi layanan publik.

## 🗂️ Struktur Proyek

```
Portal-Layanan/
├── assets/
│   ├── css/                  # Gaya dan tema tampilan
│   ├── icons/                # Ikon antarmuka
│   ├── images/               # Gambar statis
│   └── js/                   # Skrip JavaScript kustom
├── modules/
│   ├── app/                  # Modul inti aplikasi
│   ├── calendar/             # Fitur kalender
│   ├── echarts/              # Visualisasi data dengan ECharts
│   ├── fancybox/             # Popup image viewer
│   ├── flickity/             # Carousel slider
│   ├── fonts/                # Font dan ikon
│   ├── jquery/               # Library jQuery
│   ├── masonry/              # Layout grid responsif
│   ├── materialize/          # Framework Materialize CSS
│   ├── pace/                 # Progress bar
│   └── perfect-scrollbar/    # Scrollbar kustom
├── index.html                # Halaman utama portal
├── alamat.html               # Informasi alamat dan kontak
├── layanan.html              # Daftar layanan publik
├── tblayanan.json            # Data layanan dalam format JSON
├── tbmainmenu.json           # Struktur menu utama
├── pwabuilder-sw.js          # Service worker untuk PWA
```

## 🚀 Fitur Unggulan

* **Layanan Digital**: Akses berbagai layanan keagamaan tanpa harus datang langsung ke kantor.
* **Desain Responsif**: Tampilan optimal di desktop dan perangkat mobile.
* **Progressive Web App (PWA)**: Dukungan offline dan instalasi layaknya aplikasi native.
* **Visualisasi dan Navigasi Modern**: Termasuk ECharts, carousel Flickity, dan layout dinamis masonry.

## 🛠️ Cara Menjalankan Secara Lokal

1. **Clone atau unduh repositori**

   ```bash
   git clone https://github.com/namamu/portal-layanan.git
   cd portal-layanan
   ```

2. **Buka file `index.html` di browser**
   Tidak memerlukan backend; cukup buka di browser:

   * Buka `index.html` langsung di browser
   * Atau gunakan live server:

     ```bash
     npx serve .
     ```

3. **PWA Support (opsional)**
   Untuk testing *offline mode* dan PWA:

   * Pastikan file `pwabuilder-sw.js` aktif
   * Jalankan di server (bukan `file://`) agar service worker berfungsi

## 📦 Ketergantungan (Built-in)

* [Materialize CSS](https://materializecss.com/)
* [jQuery](https://jquery.com/)
* [ECharts](https://echarts.apache.org/)
* [Flickity](https://flickity.metafizzy.co/)
* [Masonry.js](https://masonry.desandro.com/)
* [Pace.js](http://github.hubspot.com/pace/)

## 🤝 Kontribusi

Silakan fork proyek ini dan kirim Pull Request untuk:

* Penambahan fitur
* Perbaikan tampilan
* Optimalisasi PWA
* Validasi data JSON

## 📄 Lisensi

Proyek ini berada di bawah lisensi **MIT** – silakan digunakan, dimodifikasi, dan disebarluaskan sesuai kebutuhan.

---

Silakan ganti bagian URL GitHub atau bagian kontribusi sesuai dengan siapa yang akan mengelola repositori ini. Jika perlu ditambahkan badge, CI/CD, atau dokumentasi API (jika nanti ada backend), README ini bisa diperluas. Mau sekalian saya buatkan versi markdown siap tempel di GitHub?
