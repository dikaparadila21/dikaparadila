# Website Portofolio - Dika Paradila

Website portofolio sederhana dan responsif yang dibangun dengan HTML, CSS, dan JavaScript vanilla.

## 📁 Struktur Folder

```
dikaparadila/
├── index.html       # File HTML utama
├── style.css        # File CSS untuk styling
├── script.js        # File JavaScript untuk interaktivitas
└── README.md        # Dokumentasi proyek
```

## ✨ Fitur

- ✅ **Responsif** - Optimal di desktop, tablet, dan mobile
- ✅ **Smooth Scrolling** - Navigasi yang halus dan menyenangkan
- ✅ **Mobile Menu** - Menu hamburger untuk perangkat mobile
- ✅ **Animasi** - Animasi modern dan menarik
- ✅ **Portfolio Showcase** - Menampilkan project dengan cards yang elegan
- ✅ **Contact Info** - Informasi kontak dan social media links
- ✅ **SEO Friendly** - Structure HTML yang semantik

## 🎨 Bagian-bagian Website

### 1. **Navigation Bar**
- Logo/nama di sebelah kiri
- Menu navigasi yang sticky
- Hamburger menu untuk mobile

### 2. **Hero Section**
- Welcome message yang menarik
- Background gradient yang cantik
- Call-to-action button

### 3. **About Section**
- Deskripsi personal
- Skill bars dengan persentase
- Layout grid yang responsif

### 4. **Portfolio Section**
- Grid tampilan project cards
- Gambar dengan hover effect
- Tags teknologi untuk setiap project

### 5. **Contact Section**
- Email dan telepon
- Social media links (GitHub, LinkedIn, Twitter, Instagram)
- Styling gradient yang menarik

### 6. **Footer**
- Copyright information
- Minimal dan clean

## 🚀 Cara Menggunakan

### 1. **Setup Awal**
Tidak memerlukan instalasi atau build process. Hanya buka file `index.html` di browser:

```bash
# Buka di browser
open index.html

# Atau gunakan live server (jika menggunakan VS Code)
# Install extension "Live Server" kemudian right-click > Open with Live Server
```

### 2. **Kustomisasi Konten**

#### Edit informasi personal di `index.html`:
- Ganti "Dika Paradila" dengan nama Anda
- Update email di section contact
- Ubah nomor telepon
- Edit deskripsi "About" section

#### Contoh:
```html
<!-- Ubah ini -->
<h2>Halo, Saya Dika Paradila</h2>

<!-- Menjadi -->
<h2>Halo, Saya [Nama Anda]</h2>
```

### 3. **Tambah/Edit Portfolio Projects**

Tambahkan project baru dengan menambah elemen berikut di section portfolio:

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="url-image-anda" alt="Project Name">
    </div>
    <div class="portfolio-info">
        <h3>Project Title</h3>
        <p>Deskripsi project Anda...</p>
        <div class="portfolio-tags">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
    </div>
</div>
```

### 4. **Update Social Media Links**

Di section contact, ubah URL social media:

```html
<a href="https://github.com/username-anda" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

## 🎨 Customisasi Warna

Warna gradient utama dapat diubah di `style.css`. Cari dan edit:

```css
/* Warna gradient utama (ungu) */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Ganti dengan warna pilihan Anda */
background: linear-gradient(135deg, #FF6B6B 0%, #FF8E72 100%);
```

### Palet warna yang direkomendasikan:
- **Biru**: `#667eea` hingga `#764ba2`
- **Merah**: `#FF6B6B` hingga `#FF8E72`
- **Hijau**: `#11998e` hingga `#38ef7d`
- **Oranye**: `#FF9A56` hingga `#FF6A88`

## 📱 Responsive Breakpoints

Website responsif pada breakpoints:
- **Desktop**: 1200px dan lebih
- **Tablet**: 768px - 1199px
- **Mobile**: Kurang dari 768px
- **Mobile kecil**: Kurang dari 480px

## 🔧 Teknologi yang Digunakan

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Animations
- **JavaScript Vanilla** - Interaktivitas tanpa framework
- **Font Awesome** - Icons

## 📚 Library CDN yang Digunakan

- Font Awesome Icons: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`
- Placeholder Images: `https://via.placeholder.com`

## 🚀 Deploy Website

### Opsi 1: GitHub Pages (Gratis)
1. Buat repository di GitHub
2. Push files ke repository
3. Settings → Pages → Pilih main branch
4. Website akan live di `https://username.github.io/repository-name`

### Opsi 2: Netlify (Gratis)
1. Buka https://netlify.com
2. Drag & drop folder ke Netlify
3. Website akan instant live

### Opsi 3: Vercel (Gratis)
1. Buka https://vercel.com
2. Import repository GitHub
3. Deploy otomatis

## 📝 Tips & Trik

1. **Gunakan Foto Berkualitas** - Ganti placeholder images dengan foto asli
2. **Optimize Gambar** - Compress gambar sebelum upload untuk performa lebih baik
3. **SEO Meta Tags** - Tambahkan meta description di `<head>`:
   ```html
   <meta name="description" content="Portofolio profesional Dika Paradila - Web Developer">
   ```
4. **Google Analytics** - Tambahkan GA untuk tracking visitors
5. **SSL Certificate** - Pastikan website menggunakan HTTPS

## 🐛 Troubleshooting

### Menu hamburger tidak bekerja
- Pastikan `script.js` ter-load dengan benar
- Cek console browser untuk error

### Gambar tidak tampil
- Pastikan URL gambar benar
- Cek format gambar support (jpg, png, webp)
- Gunakan images dengan ukuran yang tepat

### Styling tidak benar
- Clear browser cache (Ctrl+Shift+Delete)
- Pastikan `style.css` ter-load
- Cek CSS syntax di browser DevTools

## 📄 Lisensi

Project ini bebas untuk digunakan dan dimodifikasi. Sesuaikan dengan kebutuhan Anda!

## 🤝 Kontribusi

Jika Anda ingin menambahkan fitur atau memperbaiki bug, silakan buat pull request!

---

**Selamat membuat portofolio yang luar biasa! 🎉**
