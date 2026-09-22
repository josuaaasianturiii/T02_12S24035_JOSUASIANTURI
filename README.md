# Tugas Mandiri Minggu 03 - PPAW (Bootstrap 5 & Custom CSS)

Nama: Josua Sianturi
NIM: 12S22035
Prodi: S1 Sistem Informasi IT Del  

## Deskripsi Singkat
Proyek ini adalah hasil refactoring dan modernisasi dari **Tugas Mandiri Minggu 2 (Personal Portfolio & Service Portal)** menjadi berstandar industri menggunakan **Bootstrap 5.3 CDN**, **Bootstrap Icons**, **CSS Custom Properties (:root)**, serta **Advanced Custom CSS Overrides & Micro-interactions**.

---

## Tabel Komparasi: Sebelum (Minggu 2) vs Sesudah (Minggu 3)

| Area Evaluasi | Minggu 2 (CSS Murni & Layout Manual) | Minggu 3 (Bootstrap 5 & Advanced CSS) |
| :--- | :--- | :--- |
| **Fondasi & Framework** | HTML5 semantik murni dengan `style.css` custom tanpa framework eksternal. | Integrasi **Bootstrap 5.3 CDN** (CSS & JS Bundle) + **Bootstrap Icons** dengan struktur semantik tetap terjaga (`header`, `nav`, `main`, `section`, `aside`, `footer`). |
| **Navigasi & Hero** | Navbar Flexbox statis biasa, tanpa tombol hamburger untuk layar mobile. | Navbar **sticky-top** responsif dengan tombol hamburger toggle collapse yang interaktif & lancar di perangkat mobile, serta **Hero Section** bergradien dengan CTA. |
| **Grid & Portofolio** | Penataan kartu menggunakan CSS Grid / Block standar manual. | Grid 12-kolom responsif (`row-cols-1 row-cols-md-2 row-cols-g-4`) dengan 4 kartu proyek interaktif terhubung ke **Bootstrap Modal (.modal)**. |
| **Formulir Layanan** | Formulir kontak standar dengan fieldset dan input dasar tanpa state validasi visual. | Formulir kontak modern dengan **Floating Labels (`.form-floating`)**, **Input Groups berikon**, Select category, Checkbox, dan umpan balik validasi visual (`.invalid-feedback`). |
| **Theming & Custom CSS** | Penggunaan warna kustom langsung di berbagai rule tanpa arsitektur terpusat. | Arsitektur **CSS Custom Properties (`:root`)** mendefinisikan 6+ variabel (`--primary-brand`, `--surface-bg`, `--card-radius`, `--shadow-lift`, dll.) dengan mikro-interaksi hover halus dan bebas dari `!important` berlebih. |
| **Deployment & Git** | Repositori lokal Minggu 2 dengan branch `main`. | Branch terstruktur `week3-bootstrap`, commit pesan deskriptif, dan siap publikasi GitHub Pages. |

---

## Fitur Utama Minggu 3
1. **Responsive Navbar & Hero Section**: Navigasi sticky dengan toggle collapse dan Call-to-Action.
2. **Bootstrap Grid & Modals**: 4 kartu proyek responsif dengan popup detail modal interaktif.
3. **Modern Forms & Validation**: Floating labels, input groups dengan ikon, dan client-side validation feedback.
4. **CSS Custom Properties & Theming**: Variabel `:root` terpusat dan efek transisi hover modern.

## Cara Menjalankan
1. Clone repositori ini atau buka folder proyek.
2. Buka file `index.html` menggunakan **Live Server** di Visual Studio Code atau browser web modern.
