# Alezonyth Website

Website carousel interaktif yang menampilkan berbagai platform social media dengan tampilan desktop yang konsisten di semua perangkat.

## 🚀 Fitur Utama

- **Carousel Interaktif**: Slider yang menampilkan 6 platform social media
- **Desktop-Only Layout**: Tampilan desktop yang konsisten di semua perangkat
- **Fixed Layout**: Layout tidak berubah di mobile, tetap mempertahankan ukuran desktop
- **Mobile Desktop View**: Mobile browser akan menampilkan versi desktop
- **Animasi Smooth**: Transisi yang halus antar slide

## 📱 Platform yang Ditampilkan

1. **Saweria** - Platform donasi
2. **YouTube** - Channel video content
3. **Instagram** - Platform foto dan video
4. **Twitter (X)** - Platform microblogging
5. **TikTok** - Platform video pendek
6. **GitHub** - Platform development dan coding

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur website
- **CSS3** - Styling dan animasi
  - Fixed layout (tidak responsive)
  - CSS animations
- **Vanilla JavaScript** - Interaktivitas
  - Event listeners
  - DOM manipulation
- **Font Awesome** - Icon navigation

## 📁 Struktur File

```
/
├── index.html          # File utama HTML
├── styles.css          # Styling dengan layout fixed
├── script.js           # JavaScript interaktivitas
├── favicon.ico         # Icon website
└── README.md           # Dokumentasi ini
```

## 🚀 Cara Menjalankan

### Opsi 1: Live Server (Recommended)
1. Install extension Live Server di VS Code
2. Klik kanan pada `index.html`
3. Pilih "Open with Live Server"
4. Website akan terbuka di browser

### Opsi 2: Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### Opsi 3: Node.js HTTP Server
```bash
npx http-server
```

### Opsi 4: Direct File
Cukup buka file `index.html` langsung di browser

## 📱 Desktop-Only Design

Website ini menggunakan **fixed layout** yang tidak berubah di berbagai ukuran layar:

- **Desktop**: Layout penuh dengan ukuran 1000px × 500px
- **Mobile**: Tetap menampilkan layout desktop (1000px × 500px)
- **Tablet**: Tetap menampilkan layout desktop (1000px × 500px)

### Fitur Desktop pada Mobile:
- Viewport di-set ke 1000px width
- User tidak bisa zoom in/out
- Layout tetap mempertahankan proporsi desktop
- Mobile browser akan menampilkan versi desktop

## 🎮 Cara Penggunaan

### Semua Perangkat:
- Klik tombol panah kiri/kanan untuk navigasi
- Di mobile, user perlu scroll horizontal untuk melihat keseluruhan konten
- Layout tetap sama persis seperti di desktop

## 🎨 Fitur Desain

- **Fixed container**: 1000px × 500px (tidak berubah)
- **Background gradient** dengan warna abu-abu modern
- **Box shadow** untuk efek depth
- **Smooth transitions** antar slide
- **Hover effects** pada navigation buttons
- **Fixed positioning** untuk layout yang konsisten

## 🔧 Kustomisasi

### Menambah Platform Baru:
1. Tambahkan item baru di `index.html`:
```html
<div class="item" style="background-image: url('your-image-url');">
    <div class="content">
        <div class="name">Nama Platform</div>
        <div class="des">Deskripsi platform</div>
        <button onclick="window.open('your-url')">Click Untuk Membuka</button>
    </div>
</div>
```

2. Update JavaScript di `script.js` jika diperlukan:
```javascript
// Update length calculation if adding more items
document.querySelector('.slide').prepend(items[items.length - 1])
```

### Mengubah Styling:
Edit file `styles.css` dan modifikasi:
- Warna: Ubah nilai `background`, `color`, dll
- Ukuran: Modifikasi `width`, `height`, `font-size`
- Animasi: Edit `@keyframes animate`

## 🌐 Browser Support

- ✅ Chrome/Chromium (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile) - akan tampil desktop view
- ✅ Opera

## 📝 Lisensi

Website ini dibuat untuk keperluan pribadi/portfolio.

## 👨‍💻 Developer

Dibuat oleh **Alezonyth** / **MaBroJati**

## 📞 Kontak

- YouTube: [@AlzntyhCh](https://www.youtube.com/@AlzntyhCh)
- Instagram: [@mas.jati_](https://www.instagram.com/mas.jati_)
- Twitter: [@MaBroJati_](https://x.com/MaBroJati_)
- TikTok: [@mas.jati._](https://www.tiktok.com/@mas.jati._)
- GitHub: [MaBroJati](https://github.com/MaBroJati)
- Saweria: [AlezonythCH](https://saweria.co/AlezonythCH)

---

**Catatan**: Website ini menggunakan fixed layout 1000px × 500px yang akan tampil sama persis di semua perangkat. Mobile user perlu scroll horizontal untuk melihat keseluruhan konten.
