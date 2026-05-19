# Siena Music Entertainment - Official Website

Repositori ini berisi kode sumber (*source code*) untuk landing page resmi **Siena Music Entertainment**, sebuah grup musik profesional asal Yogyakarta yang menghadirkan pengalaman musik premium dan elegan untuk berbagai acara seperti pernikahan (*wedding*), *corporate gathering*, hingga acara formal lainnya.

Website ini didesain dengan konsep **Luxury Dark & Gold** untuk merepresentasikan citra eksklusif dan berkelas dari Siena Music.

## 🚀 Demo Langsung
Website ini telah di-deploy menggunakan GitHub Pages dan dapat diakses secara publik melalui tautan berikut:
👉 **[https://mirfaktito.github.io/SienaBand/](https://mirfaktito.github.io/SienaBand/)**

---

## ✨ Fitur Utama Website

* **Desain Premium & Responsif:** Tampilan elegan dengan perpaduan warna gelap dan emas yang sepenuhnya responsif di semua perangkat (Desktop, Tablet, dan HP/Ponsel).
* **Smart Background Music Player:** Musik latar belakang otomatis berputar (*autoplay*) dengan volume halus (5%) yang terpicu secara cerdas melalui interaksi pertama pengguna (klik/sentuhan). Dilengkapi dengan tombol kontrol putar/jeda (*play/pause*) melayang yang estetis di pojok kiri bawah.
* **Facebook Reels Video Embed:** Integrasi pemutar video langsung dari Facebook Reels milik Siena Entertainment menggunakan Meta JavaScript SDK yang dikonfigurasi dengan rasio vertikal (9:16) yang pas tanpa terpotong.
* **Infinite Experiences Marquee:** Teks berjalan horizontal (*seamless looping marquee*) yang menampilkan daftar *venue* prestisius yang pernah bekerja sama dengan Siena.
* **Interactive Custom Cursor:** Efek interaksi penunjuk kursor (*custom cursor & ring*) yang halus pada perangkat desktop, dan otomatis disembunyikan pada layar sentuh ponsel demi kenyamanan navigasi pengguna.
* **Direct WhatsApp CTA Integration:** Tombol "Book Now" dan opsi "Tanya Harga" pada paket layanan yang langsung terhubung ke WhatsApp manajemen Siena dengan teks pesan otomatis yang rapi.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5** – Struktur semantik dasar halaman web.
* **CSS3 (Media Queries & Animations)** – Pengaturan tata letak (*Grid & Flexbox*), animasi *fade-up*, efek *marquee*, serta penanganan responsivitas *mobile*.
* **Vanilla JavaScript (ES6)** – Logika interaksi kursor kustom, navigasi dinamis saat di-scroll, *smart autoplay* audio, dan *Intersection Observer API* untuk efek *reveal* saat halaman digeser.
* **Meta JavaScript SDK** – Digunakan untuk merender pemutar video Reels Facebook secara langsung di dalam website.

---

## 📁 Struktur Berkas

```text
SienaBand/
│
├── index.html                           # Halaman utama website (Landing Page)
├── README.md                            # Dokumentasi repositori
│
└── [File Media Lokal]
    ├── favicon.png                      # Ikon untuk tab browser (Rasio 1:1)
    └── Gege Grisel - Layakkah Ku Dicintai.mp3  # File audio musik latar belakang
