# Geovani Giesan — Cybersecurity Portfolio

Website portofolio personal responsif menggunakan HTML, CSS, dan JavaScript murni.

## Fitur
- Desain modern gelap dengan aksen biru.
- Navigasi responsif dengan menu mobile.
- Bagian profil, proyek, CTF write-ups, skill, dan kontak.
- Form kontak membuat draft email melalui aplikasi email pengguna (tidak memerlukan backend).
- SEO dasar, aksesibilitas, dan dukungan `prefers-reduced-motion`.

## Menjalankan secara lokal

### Cara paling mudah
1. Ekstrak ZIP.
2. Buka folder `geovani-cybersecurity-portfolio`.
3. Buka `index.html` di browser.

### Dengan server lokal (opsional)
Jika Python terpasang, buka terminal di folder proyek lalu jalankan:

```bash
python3 -m http.server 8000
```

Buka `http://127.0.0.1:8000`.

## Deploy gratis dengan GitHub Pages
1. Buat repository GitHub baru, misalnya `cybersecurity-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu tekan **Save**.
6. Tunggu proses publikasi selesai. URL biasanya berbentuk `https://USERNAME.github.io/cybersecurity-portfolio/`.

## Sebelum dipublikasikan
- Pastikan alamat email `geovani.giesan@gmail.com` benar dan memang ingin ditampilkan secara publik.
- Ganti link GitHub generik pada setiap kartu dengan URL repository spesifik.
- Tautan CTF saat ini menuju profil GitHub/halaman resmi. Ubah ke write-up milikmu yang benar-benar tersedia.
- Kartu proyek merupakan contoh ide, bukan klaim bahwa proyek tersebut telah selesai. Bangun proyeknya, isi repository, tambahkan screenshot dan hasil pengujian sebelum menyatakan selesai.
- Periksa kembali setiap skill agar sesuai dengan kemampuan yang bisa didemonstrasikan.
- Jangan mempublikasikan flag, kredensial, data pribadi, atau detail yang dilarang aturan platform CTF.

## Struktur folder

```text
geovani-cybersecurity-portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Kustomisasi cepat
- Edit teks dan tautan di `index.html`.
- Ubah warna utama melalui variabel CSS `--blue` dan `--blue-strong` di `style.css`.
- Perilaku menu, tahun footer, navigasi aktif, dan form email ada di `script.js`.

## Batasan
Ini website statis. Form kontak tidak menyimpan atau mengirim data ke server; ia hanya membuka draft email. Untuk menerima pesan tanpa aplikasi email, integrasikan backend atau layanan form pihak ketiga setelah meninjau privasi dan keamanannya.
