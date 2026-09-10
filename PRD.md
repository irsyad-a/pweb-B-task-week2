# PRODUCT REQUIREMENTS DOCUMENT (PRD)

## Website CV & Portofolio Irsyad Akbar

| Item | Keterangan |
|---|---|
| Nama Produk | Website CV & Portofolio Irsyad Akbar |
| Jenis Produk | Static Website / Personal Portfolio |
| Pemilik Produk | Irsyad Akbar |
| Teknologi Utama | HTML5 dan CSS3 |
| Platform | Web Browser — Desktop & Mobile |
| Target Pengguna | Dosen, recruiter, teman/komunitas, dan pengunjung umum |
| Bahasa Website | Bahasa Indonesia |
| Status Website | Website portofolio personal |

---

## 1. Latar Belakang

Irsyad Akbar (saya) membutuhkan media digital untuk memperkenalkan identitas, latar belakang pendidikan, pengalaman organisasi, kemampuan, dan hasil karya di bidang web development serta UI/UX design. Website CV & Portofolio ini dibuat sebagai halaman personal yang dapat diakses melalui browser dan menjadi representasi profesional bagi pengguna yang ingin mengenal profil, kompetensi, serta proyek yang pernah dikerjakan.

Website ini juga menjadi sarana dokumentasi pembelajaran dan praktik penerapan HTML5, CSS3, struktur halaman, navigasi anchor, layout visual, serta penyajian informasi personal secara terstruktur dan komunikatif.

---

## 2. Tujuan Produk

Website ini bertujuan untuk:

1. Menampilkan profil Irsyad Akbar (saya) secara profesional.
2. Menyajikan biografi, identitas, dan kontak secara ringkas.
3. Menampilkan pengalaman organisasi dan pendidikan.
4. Menampilkan kemampuan di bidang desain dan pengembangan web.
5. Menampilkan proyek portofolio yang pernah dikerjakan.
6. Menyediakan akses untuk mengunduh CV.
7. Memudahkan pengunjung menghubungi pemilik website melalui formulir kontak dan informasi kontak.

---

## 3. Konsep Produk

Website CV & Portofolio Irsyad Akbar (saya) merupakan website statis berbasis HTML dan CSS yang memiliki struktur satu halaman dengan beberapa section utama. Navigasi menggunakan anchor link untuk berpindah ke bagian Depan, Biografi, Portofolio, dan Kontak.

Konsep desain menekankan tampilan personal, modern, dan profesional dengan elemen visual seperti foto profil, kartu pengalaman, daftar kemampuan, galeri portofolio, ikon media sosial, serta tombol call-to-action.

---

## 4. Target Pengguna

### 4.1 Primary User — Dosen / Penilai

Dosen atau penilai menggunakan website untuk mengevaluasi kemampuan mahasiswa dalam membuat website CV dan portofolio menggunakan HTML5 dan CSS3. Aspek yang dilihat meliputi struktur halaman, kelengkapan konten, konsistensi UI, navigasi, dan kualitas implementasi.

### 4.2 Secondary User — Recruiter / Perusahaan

Recruiter menggunakan website untuk melihat profil, kemampuan, pengalaman, pendidikan, serta proyek yang pernah dikerjakan oleh Irsyad Akbar, khususnya di bidang web development dan UI/UX design.

### 4.3 Tertiary User — Teman, Komunitas, dan Pengunjung Umum

Pengunjung umum menggunakan website untuk mengenal identitas, karya, dan informasi kontak Irsyad Akbar.

---

## 5. Struktur Informasi

Struktur informasi website terdiri dari:

```text
WEBSITE PORTOFOLIO IRSYAD AKBAR
│
├── Depan / Hero
│   ├── Foto profil
│   ├── Profesi
│   └── Deskripsi singkat
│
├── Biografi
│   ├── Deskripsi diri
│   ├── Identitas personal
│   ├── Download CV
│   ├── Pengalaman
│   ├── Pendidikan
│   └── Kemampuan
│
├── Portofolio
│   ├── Deskripsi portofolio
│   ├── CTA kontak
│   └── Daftar proyek
│
└── Kontak
    ├── Formulir kontak
    ├── Alamat
    ├── Telepon
    └── Email
```

---

## 6. Requirement Fitur

### 6.1 Navigasi Samping

Navigasi harus membantu pengguna berpindah antarbagian utama website.

**Komponen:**

- Depan
- Biografi
- Portofolio
- Kontak
- Ikon media sosial: Instagram, Twitter, YouTube

**Requirement:**

- Setiap menu menggunakan anchor link menuju section terkait.
- Menu aktif memiliki visual state yang jelas.
- Navigasi mudah ditemukan dan konsisten di seluruh halaman.
- Ikon media sosial mengarah ke akun yang sesuai.

---

### 6.2 Hero / Depan

Hero menjadi bagian pertama yang dilihat pengguna saat membuka website.

**Konten:**

- Foto profil Irsyad Akbar.
- Profesi: Website Developer.
- Informasi status sebagai mahasiswa Teknik Informatika ITS.
- Deskripsi singkat tentang bidang web development dan UI/UX design.

**Requirement:**

- Foto profil tampil jelas.
- Deskripsi singkat mudah dibaca.
- Link ke Teknik Informatika ITS dapat diklik.
- Layout hero harus menarik dan memberikan kesan profesional.

---

### 6.3 Biografi

Section biografi menjelaskan profil singkat pemilik website.

**Konten:**

- Deskripsi diri sebagai mahasiswa Teknik Informatika ITS.
- Pengalaman di bidang Web Development dan UI/UX Design selama 2+ tahun.
- Ketertarikan pada pemecahan masalah dan solusi inovatif.

**Requirement:**

- Teks biografi singkat, jelas, dan komunikatif.
- Informasi ditampilkan dalam section khusus dengan judul “Biografi”.
- Konten harus mendukung personal branding sebagai web developer dan UI/UX designer.

---

### 6.4 Identitas & Kontak Ringkas

Bagian identitas menampilkan data personal penting.

**Konten:**

- Nama: Irsyad Akbar
- Tanggal lahir: 21 Juni 2007
- Usia: 18 Tahun
- Alamat: Surabaya, ID
- Nomor telepon
- Instagram: @syad.hs
- Email: irsyadakbarg@gmail.com

**Requirement:**

- Data identitas ditampilkan dalam format daftar.
- Link email menggunakan `mailto:`.
- Link telepon menggunakan `tel:`.
- Link Instagram membuka akun terkait.

---

### 6.5 Download CV

Website menyediakan tombol untuk mengunduh CV.

**Konten:**

- Tombol “Download CV”.
- File tujuan: `pdf/cv.pdf`.

**Requirement:**

- Tombol mudah dikenali sebagai call-to-action.
- Tombol memiliki atribut download.
- File CV tersedia di folder yang sesuai.

---

### 6.6 Pengalaman

Bagian pengalaman menampilkan riwayat organisasi atau pekerjaan yang relevan.

**Konten:**

1. Lembaga Minat Bakat ITS  
   - Periode: 2026 - Sekarang  
   - Posisi: Media Kreatif  
   - Deskripsi: Membuat aset desain untuk kebutuhan organisasi Lembaga Minat Bakat ITS.

2. Jamaah Masjid Manarul Ilmi ITS  
   - Periode: 2026 - Sekarang  
   - Posisi: Digital Production  
   - Deskripsi: Membuat aset desain untuk kebutuhan organisasi Jamaah Masjid Manarul Ilmi ITS.

**Requirement:**

- Setiap pengalaman ditampilkan dalam bentuk kartu.
- Setiap kartu memuat nama organisasi, periode, posisi, dan deskripsi.
- Layout antar kartu konsisten.

---

### 6.7 Pendidikan

Bagian pendidikan menampilkan riwayat pendidikan formal.

**Konten:**

1. Institut Teknologi Sepuluh Nopember  
   - Periode: 2025 - Sekarang  
   - Program: Teknik Informatika

2. MAN IC Bangka Tengah  
   - Periode: 2022 - 2025  
   - Program: Jurusan Umum

**Requirement:**

- Informasi pendidikan ditampilkan secara kronologis atau dalam format kartu.
- Setiap item memuat institusi, periode, dan program/jurusan.
- Desain konsisten dengan kartu pengalaman.

---

### 6.8 Kemampuan

Bagian kemampuan menampilkan skill yang dimiliki pemilik website.

**Konten:**

- Figma
- HTML5 & CSS3
- Adobe Photoshop
- Adobe Illustrator

**Requirement:**

- Setiap kemampuan memiliki nama skill.
- Skill ditampilkan dengan visual indicator atau elemen pendukung.
- Terdapat deskripsi singkat mengenai kemampuan di bidang desain grafis dan pengembangan perangkat lunak.

---

### 6.9 Portofolio

Bagian portofolio menampilkan proyek yang pernah dikerjakan.

**Konten:**

1. Website LMB ITS  
   - Kategori: Web Design, UI/UX, Web Development  
   - Gambar: `img/portfolio/1.png`

2. Web Landing Page IBL  
   - Kategori: UI/UX Design  
   - Gambar: `img/portfolio/2.png`

3. Web Form MBMT LMB ITS  
   - Kategori: UI/UX, Implement Design  
   - Gambar: `img/portfolio/3.png`

**Requirement:**

- Minimal tiga proyek portofolio ditampilkan.
- Setiap proyek memiliki judul, kategori, dan gambar.
- Gambar proyek dapat diperbesar atau dibuka melalui link gambar.
- CTA “Tertarik? Hubungi saya!” mengarah ke section kontak.

---

### 6.10 Kontak

Bagian kontak menyediakan cara bagi pengunjung untuk menghubungi pemilik website.

**Konten Formulir:**

- Nama
- Email
- No. Telp
- Pesan
- Tombol Kirim Pesan

**Informasi Kontak:**

- Alamat: Jln. Teknik Komputer III, Surabaya, Indonesia
- Telepon
- Email: irsyadakbarg@gmail.com

**Requirement:**

- Formulir memiliki label yang jelas.
- Input email menggunakan tipe `email`.
- Input telepon menggunakan tipe `tel`.
- Tombol kirim mudah dikenali.
- Informasi kontak ditampilkan di bawah atau di samping formulir.

---

## 7. Functional Requirement

Meskipun website bersifat statis, elemen berikut harus berfungsi:

| Fitur | Requirement |
|---|---|
| Navigasi | Link Depan, Biografi, Portofolio, dan Kontak menuju section yang benar |
| Link eksternal | Link Teknik Informatika ITS dan media sosial dapat dibuka |
| Download CV | Tombol mengunduh file CV dari `pdf/cv.pdf` |
| Email | Link email menggunakan format `mailto:` |
| Telepon | Link telepon menggunakan format `tel:` |
| Portofolio | Gambar/proyek dapat dibuka melalui link gambar |
| CTA | Tombol ajakan kerja sama mengarah ke section kontak |

---

## 8. Non-Functional Requirement

### 8.1 Performance

- Website harus ringan dan cepat dimuat.
- Gambar perlu dioptimalkan agar tidak memperlambat loading.
- File CSS dipisahkan dalam `css/style.css`.

### 8.2 Accessibility

- Gambar memiliki atribut `alt` yang relevan.
- Link dan tombol dapat dikenali secara visual.
- Kontras warna cukup untuk keterbacaan.
- Label formulir harus terhubung dengan input.

### 8.3 Responsiveness

- Website harus dapat dibuka pada desktop dan mobile.
- Layout tidak boleh rusak pada ukuran layar kecil.
- Navigasi tetap dapat digunakan pada berbagai ukuran layar.

### 8.4 Maintainability

- Struktur HTML harus rapi dan mudah dibaca.
- Penamaan class konsisten.
- Aset disusun dalam folder yang jelas seperti `img`, `svg`, `css`, dan `pdf`.

---

## 9. Requirement UI/UX

Website harus memenuhi prinsip UI/UX berikut:

1. **Consistency** — gaya visual, spacing, warna, dan kartu konten konsisten.
2. **Hierarchy** — judul section, isi, dan CTA memiliki hierarki visual yang jelas.
3. **Readability** — teks mudah dibaca pada desktop dan mobile.
4. **Accessibility** — link, tombol, dan formulir mudah dipahami.
5. **Usability** — pengguna dapat menemukan profil, portofolio, dan kontak tanpa kebingungan.

---

## 10. Content Requirement

| Komponen | Status / Minimum |
|---|---|
| Foto profil | Tersedia |
| Identitas | Tersedia |
| Biografi | Tersedia |
| Pengalaman | Minimal 2 item, tersedia |
| Pendidikan | Minimal 2 item, tersedia |
| Kemampuan | Tersedia 4 skill |
| Portofolio | Minimal 3 proyek, tersedia |
| Social media | Instagram, Twitter, YouTube |
| CTA | Download CV dan Hubungi Saya |
| Kontak | Formulir, alamat, telepon, email |

---

## 11. User Flow

```text
Pengunjung membuka website
        ↓
Melihat hero dan foto profil
        ↓
Membaca biografi dan identitas
        ↓
Melihat pengalaman, pendidikan, dan kemampuan
        ↓
Melihat proyek portofolio
        ↓
Memilih action:
- Download CV
- Membuka proyek/gambar
- Menghubungi melalui formulir/email/telepon
```

---

## 12. Information Architecture

```text
WEBSITE
│
├── PROFILE
│   ├── Hero
│   ├── Biografi
│   └── Identitas
│
├── CAREER & EDUCATION
│   ├── Pengalaman
│   └── Pendidikan
│
├── SKILLS
│   └── Kemampuan
│
├── PORTFOLIO
│   ├── Website LMB ITS
│   ├── Web Landing Page IBL
│   └── Web Form MBMT LMB ITS
│
└── CONTACT
    ├── Formulir kontak
    ├── Alamat
    ├── Telepon
    └── Email
```

---

## 13. Acceptance Criteria

Website dianggap memenuhi requirement apabila:

### Struktur

- HTML5 digunakan.
- CSS eksternal digunakan melalui `css/style.css`.
- Struktur halaman memiliki section utama: Depan, Biografi, Portofolio, dan Kontak.
- Setiap section memiliki `id` yang dapat diakses melalui navigasi.

### UI

- Layout konsisten di seluruh halaman.
- Typography mudah dibaca.
- Warna dan elemen visual konsisten.
- Kartu pengalaman, pendidikan, kemampuan, dan portofolio tampil rapi.
- Tombol Download CV dan CTA Kontak terlihat jelas.

### UX

- Navigasi berfungsi dengan benar.
- Informasi profil mudah ditemukan.
- Pengunjung dapat memahami keahlian dan proyek dalam waktu singkat.
- CTA mengarahkan pengguna ke tindakan yang jelas.
- Website dapat diakses pada desktop dan mobile tanpa layout rusak.

### Content

- Foto profil tersedia.
- Biografi tersedia.
- Identitas personal tersedia.
- Pengalaman tersedia.
- Pendidikan tersedia.
- Kemampuan tersedia.
- Tiga proyek portofolio tersedia.
- Kontak tersedia.
- Link media sosial tersedia.

---

## 14. Deliverables

File dan aset yang perlu tersedia:

```text
portfolio/
├── index.html
├── css/
│   └── style.css
├── img/
│   ├── thumb/
│   │   └── fotoself.jpeg
│   └── portfolio/
│       ├── 1.png
│       ├── 2.png
│       └── 3.png
├── svg/
│   ├── right-arrow.svg
│   ├── inbox.svg
│   ├── arrow.svg
│   └── social/
│       ├── instagram.svg
│       ├── twitter.svg
│       └── youtube.svg
├── pdf/
│   └── cv.pdf
└── README.md
```

---

## 15. Rubrik Penilaian

| Aspek | Bobot |
|---|---:|
| Struktur HTML & semantic section | 20% |
| CSS & layout | 20% |
| UI/UX | 20% |
| Responsive design | 15% |
| Kelengkapan konten | 10% |
| Portofolio & dokumentasi | 10% |
| Code quality | 5% |
| **Total** | **100%** |

---

## 16. Learning Outcome

Setelah menyelesaikan website ini, mahasiswa diharapkan mampu:

1. Menyusun struktur dasar website menggunakan HTML5.
2. Menghubungkan stylesheet CSS eksternal ke halaman HTML.
3. Membuat layout website CV dan portofolio yang terstruktur.
4. Menggunakan anchor link untuk navigasi antar section.
5. Menampilkan data personal, pengalaman, pendidikan, kemampuan, dan proyek secara komunikatif.
6. Menerapkan prinsip dasar UI/UX pada website personal.
7. Mengelola aset gambar, ikon, dan file CV dalam struktur folder yang rapi.
8. Membuat website yang dapat digunakan sebagai media personal branding.

---

## 17. Catatan Pengembangan Lanjutan

Beberapa peningkatan yang dapat dilakukan pada versi berikutnya:

1. Menambahkan validasi formulir kontak.
2. Menghubungkan formulir dengan layanan email atau backend sederhana.
3. Menambahkan section gallery jika diperlukan.
4. Menambahkan detail studi kasus untuk setiap proyek portofolio.
5. Meningkatkan semantic HTML dengan penggunaan elemen seperti `<header>`, `<main>`, `<section>`, `<article>`, dan `<footer>` secara lebih eksplisit.
6. Mengoptimalkan ukuran gambar agar performa website lebih baik.
7. Menambahkan metadata SEO dan Open Graph untuk kebutuhan sharing link.

---
