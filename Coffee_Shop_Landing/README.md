# BrewBeans - Website Kopi Premium

## 📋 Struktur Project

Website multi-page BrewBeans kini telah diorganisir menjadi halaman-halaman terpisah untuk pengalaman navigasi yang lebih baik.

### 📁 File-file:

```
Coffee_Shop_Landing/
├── index.html           # Halaman Beranda (Hero + Features + Newsletter)
├── products.html        # Halaman Produk (Koleksi Kopi + Filter)
├── about.html          # Halaman Tentang (Tentang Brand + Testimonial)
├── contact.html        # Halaman Kontak (Form Kontak + FAQ)
├── style.css           # Styling untuk semua halaman
├── script.js           # JavaScript untuk interaksi
└── README.md           # File ini
```

## 🎯 Halaman-Halaman:

### 1. **Beranda (index.html)**
- Hero Section dengan call-to-action
- Features Section (4 keunggulan BrewBeans)
- Newsletter Signup
- Footer dengan link ke halaman lain

### 2. **Produk (products.html)**
- Page Header yang menarik
- Filter produk (Semua, Arabika, Robusta, Specialty)
- 6 Product Cards dengan detail lengkap
- Rating dan harga produk
- Tombol "Tambah ke Keranjang"

### 3. **Tentang (about.html)**
- Kisah BrewBeans
- Nilai-Nilai Perusahaan (4 nilai utama)
- Testimonial dari 4 pelanggan
- Footer

### 4. **Kontak (contact.html)**
- Page Header
- Informasi Kontak (Alamat, Telepon, Email, Jam Operasional, Media Sosial)
- Form Kontak lengkap dengan validasi
- FAQ Section (6 pertanyaan umum)
- Footer

## 🎨 Fitur Desain:

✨ **Responsive Design** - Bekerja sempurna di semua ukuran layar
🎭 **Modern Styling** - Color scheme cokelat & beige sesuai tema kopi
🔄 **Smooth Navigation** - Link navigasi bekerja sempurna antar halaman
💫 **Animasi** - Card animations saat di-scroll
📱 **Mobile Friendly** - Optimized untuk perangkat mobile

## 🔧 Fitur Interaktif:

1. **Shopping Cart Counter** - Menampilkan jumlah produk yang ditambahkan
2. **Toast Notifications** - Notifikasi ketika produk ditambahkan
3. **Filter Produk** - Filter berdasarkan kategori kopi
4. **Form Handling** - Newsletter dan Contact form dengan feedback
5. **Smooth Scroll** - Efek scroll yang halus

## 📦 File CSS:

`style.css` mencakup styling untuk:
- Navigation bar & branding
- Page headers untuk setiap halaman
- Filter buttons untuk produk
- Form styling (contact form, newsletter)
- FAQ sections
- Product cards & testimonials
- Responsive breakpoints untuk mobile, tablet, desktop

## 🎮 File JavaScript:

`script.js` mencakup fungsi untuk:
- `addToCart()` - Menambah produk ke keranjang
- `filterProducts()` - Filter produk berdasarkan kategori
- `showToast()` - Menampilkan notifikasi
- `handleNewsletter()` - Handle newsletter submission
- `handleContact()` - Handle form submission
- Scroll animations
- Hover effects

## 🚀 Cara Menggunakan:

1. Buka `index.html` di browser untuk melihat halaman beranda
2. Gunakan navbar untuk navigasi ke halaman lain
3. Di halaman Produk, gunakan filter untuk kategori kopi
4. Klik "Tambah ke Keranjang" untuk menambah produk (cart counter akan bertambah)
5. Di halaman Kontak, isi form untuk mengirim pesan

## 🎯 Navigation:

Semua halaman memiliki navbar yang sama dengan link:
- **Beranda** → index.html
- **Produk** → products.html
- **Tentang** → about.html
- **Kontak** → contact.html
- **Cart Icon** → Menampilkan jumlah item di keranjang

## 💡 Tips Customization:

- Ubah `--primary-color`, `--secondary-color`, dll di `:root` dalam CSS untuk mengubah warna tema
- Tambah/kurangi produk di `products.html` dengan menambah/mengurangi `.product-card`
- Update informasi kontak di `contact.html`
- Tambah testimoni baru di halaman `about.html`

## 📝 Notes:

- Semua halaman menggunakan file CSS dan JS yang sama
- Responsive design menggunakan CSS Grid dan Flexbox
- Kompatibel dengan browser modern (Chrome, Firefox, Safari, Edge)
- Tidak memerlukan dependency eksternal (hanya Font Awesome icons dari CDN)

---

**Dibuat dengan ❤️ untuk pecinta kopi!**
