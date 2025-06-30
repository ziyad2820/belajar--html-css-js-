#DIsini aku sedang belajar mengembangkan website pertama saya dari 0
my-website-project/            <-- Ini adalah folder ROOT repositori GitHub kamu
├── index.html                 <-- Halaman utama website kamu (akan dicari Vercel di sini)
├── style.css                  <-- CSS utama untuk seluruh situs
├── script.js                  <-- JavaScript utama untuk seluruh situs
├── assets/                    <-- Folder untuk semua aset media
│   ├── images/                <-- Gambar-gambar (JPG, PNG, SVG)
│   │   ├── 
│   │   └── logo.pnghero-bg.jpg
│   ├── videos/                <-- File video
│   │   └── intro.mp4
│   └── fonts/                 <-- Font kustom
│       └── Poppins-Regular.ttf
├── components/                <-- (Opsional) Jika punya HTML/CSS yang bisa dipakai ulang (misal: header.html, footer.html)
│   ├── header.html
│   └── footer.html
├── pages/                     <-- (Opsional) Jika punya halaman lain selain index.html
│   ├── about.html
│   └── contact.html
└── [README.md](http://readme.md/)                  <-- Deskripsi proyek (penting untuk GitHub)
└── .gitignore                 <-- File yang memberitahu Git apa yang tidak perlu dilacak

1. Properti untuk Ukuran dan Ruang
Ini krusial banget untuk mengatur ukuran elemen dan jarak antar elemen di halamanmu.

width & height:

Apa itu: Mengatur lebar dan tinggi suatu elemen.

Contoh: width: 100%; (lebar penuh), h width: 50vw; (50% lebar viewport).

padding:
eight: 200px;,
Apa itu: Memberikan ruang di dalam batas elemen, antara konten dan batas elemen itu sendiri.

Contoh: padding: 20px; (semua sisi 20px), padding: 10px 20px; (atas-bawah 10px, kiri-kanan 20px).

margin:

Apa itu: Memberikan ruang di luar batas elemen, antara elemen itu sendiri dengan elemen di sekitarnya.

Contoh: margin: 20px; (semua sisi 20px), margin: 0 auto; (untuk menengahkan elemen blok secara horizontal).

box-sizing:

Apa itu: Ini properti penting banget! Menentukan bagaimana width dan height dihitung.

Nilai penting: border-box; (Paling sering dipakai dan disarankan). Ini memastikan padding dan border dihitung ke dalam width dan height yang kamu tentukan, jadi layout lebih mudah diprediksi.

Contoh: box-sizing: border-box; (biasanya diterapkan di selector universal *).

2. Properti untuk Teks dan Tipografi
Membuat teksmu terlihat jelas dan menarik.

font-family:

Apa itu: Mengatur jenis font yang digunakan (misalnya Arial, Helvetica, "Times New Roman").

Contoh: font-family: Arial, sans-serif; (Jika Arial tidak ada, akan pakai font sans-serif default).

font-size:

Apa itu: Mengatur ukuran teks.

Contoh: font-size: 16px;, font-size: 1.2em;, font-size: 2rem;.

font-weight:

Apa itu: Mengatur ketebalan teks (normal, bold, atau angka seperti 400, 700).

Contoh: font-weight: bold;, font-weight: 700;.

color:

Apa itu: Mengatur warna teks.

Contoh: color: #333;, color: blue;.

text-align:

Apa itu: Meratakan teks di dalam elemen (kiri, kanan, tengah, rata kiri-kanan).

Contoh: text-align: center;.

text-decoration:

Apa itu: Menambah atau menghilangkan dekorasi teks, paling sering garis bawah pada link.

Contoh: text-decoration: none; (untuk menghilangkan garis bawah link).

line-height:

Apa itu: Mengatur tinggi baris teks (jarak antar baris).

Contoh: line-height: 1.6; (1.6 kali ukuran font).

3. Properti untuk Latar Belakang dan Warna
Membuat elemenmu terlihat dengan warna dan gambar latar.

background-color:

Apa itu: Mengatur warna latar belakang elemen.

Contoh: background-color: #f0f0f0;, background-color: lightblue;.

background-image:

Apa itu: Mengatur gambar sebagai latar belakang.

Contoh: background-image: url('gambar.jpg');.

background-size:

Apa itu: Mengatur ukuran gambar latar belakang agar sesuai atau menutupi area.

Contoh: background-size: cover; (menutupi seluruh area), background-size: contain; (memuat seluruh gambar tanpa terpotong).

background-position:

Apa itu: Mengatur posisi gambar latar belakang.

Contoh: background-position: center center; (di tengah).

4. Properti untuk Tata Letak (Layout) - INI SANGAT PENTING!
Ini adalah kunci untuk mengatur posisi elemen di halaman.

display:

Apa itu: Properti yang menentukan bagaimana elemen ditampilkan. Ini adalah properti paling dasar untuk layout.

Nilai penting:

block: Menempati seluruh lebar yang tersedia, memulai di baris baru (misal div, p, h1).

inline: Hanya menempati ruang yang dibutuhkan, tidak memulai baris baru (misal span, a, img).

inline-block: Gabungan keduanya (bisa diatur width/height tapi tetap sejajar).

flex: (Flexbox) INI SANGAT KRUSIAL UNTUK LAYOUT MODERN. Membuat elemen di dalamnya menjadi flex items yang bisa diatur posisinya dengan mudah (sejajar, menengahkan, dll.).

grid: (CSS Grid) Untuk layout dua dimensi yang lebih kompleks.

Contoh: display: flex;

Properti Flexbox (jika display: flex;):

justify-content: Meratakan flex items secara horizontal (misal center, space-between).

align-items: Meratakan flex items secara vertikal (misal center, flex-start).

flex-direction: Mengatur arah flex items (default row, bisa column).

Contoh: display: flex; justify-content: center; align-items: center; (untuk menengahkan konten seperti di Hero Section).

5. Properti untuk Efek Visual Sederhana
Membuat elemenmu lebih menarik secara visual.

border:

Apa itu: Menambahkan garis batas di sekitar elemen.

Contoh: border: 1px solid #ccc; (1px tebal, solid, warna abu-abu).

border-radius:

Apa itu: Membuat sudut elemen membulat.

Contoh: border-radius: 5px;, border-radius: 50%; (untuk membuat elemen jadi lingkaran).

box-shadow:

Apa itu: Menambahkan bayangan pada elemen.

Contoh: box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

transition:

Apa itu: Membuat perubahan properti CSS menjadi halus (animasi sederhana).

Contoh: transition: background-color 0.3s ease; (Saat background-color berubah, animasinya 0.3 detik).

opacity:

Apa itu: Mengatur tingkat transparansi elemen.

Contoh: opacity: 0.7; (70% terlihat, 30% transparan).

6. Media Queries (Untuk Responsif)
Ini adalah kunci untuk membuat website-mu terlihat bagus di berbagai ukuran layar (desktop, tablet, handphone).

Apa itu: Aturan yang memungkinkanmu menerapkan CSS berbeda berdasarkan kondisi tertentu, paling umum ukuran layar.

Contoh:

CSS

@media (max-width: 768px) { /* Jika lebar layar <= 768px */
    .my-element {
        font-size: 1em; /* Ubah ukuran font */
        flex-direction: column; /* Ubah layout flexbox menjadi kolom */
    }
}