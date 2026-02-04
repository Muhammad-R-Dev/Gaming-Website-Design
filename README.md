# 🎮 GAMELAND - Website Portfolio Modern

![GAMELAND Preview](https://github.com/user-attachments/assets/c9a3e15f-c8fc-4ffc-9713-59c7b692b721)

Website portfolio canggih dengan animasi 3D imersif, preloader stylish, dan toggle musik interaktif. Dirancang untuk developer dan kreatif modern yang ingin memamerkan karya mereka dengan cara yang menarik.

## 🌐 Live Demo

**[🔗 Klik di sini untuk melihat Live Demo](https://muhammad-r-dev.github.io/Gaming-Website-Design/)**

## ✨ Fitur Utama

### 🎨 Pengalaman Visual
- **Efek Kartu 3D** - Kartu interaktif dengan kedalaman dan perspektif
- **Animasi Mask Scroll** - Gambar terungkap secara dinamis saat discroll
- **Preloader Stylish** - Animasi loading elegan sebelum konten muncul
- **Animasi Halus** - Transisi dan pergerakan yang fluid

### 🎵 Elemen Interaktif
- **Toggle Musik** - Kontrol audio latar dengan feedback visual
- **Desain Responsif** - Pengalaman mulus di semua perangkat
- **Efek Parallax** - Kedalaman berlapis untuk daya tarik visual

### 📱 Keunggulan Teknis
- **Pendekatan Mobile-First** - Dioptimalkan untuk interaksi sentuh dan mobile
- **Optimasi Performa** - Loading cepat dan animasi halus
- **Struktur Kode Bersih** - Arsitektur yang mudah dikelola dan dikembangkan

## 🛠 Stack Teknologi

| Teknologi | Tujuan |
|-----------|---------|
| **HTML5** | Struktur markup semantik |
| **SCSS/CSS** | Styling lanjutan dengan metodologi BEM |
| **JavaScript (ES6+)** | Fungsi interaktif |
| **GSAP** | Animasi tingkat profesional |
| **GreenSock ScrollTrigger** | Animasi berbasis scroll |
| **CSS3 Modern** | Transform 3D, flexbox, grid |

## 🚀 Memulai

### Prasyarat
- Browser web modern dengan dukungan CSS3 dan JavaScript ES6+
- Server lokal untuk pengembangan (opsional)

### Instalasi
1. Clone repository:
```bash
git clone https://github.com/namapengguna/gameland-portfolio.git
```

2. Masuk ke direktori proyek:
```bash
cd gameland-portfolio
```

3. Buka `index.html` di browser atau gunakan server lokal:
```bash
# Menggunakan Python
python -m http.server 8000

# Menggunakan Node.js
npx serve
```

## 📁 Struktur Proyek

```
gameland-portfolio/
├── index.html              # File HTML utama
├── css/
│   ├── main.css           # CSS yang dikompilasi
│   └── styles.scss        # File sumber SCSS
├── js/
│   ├── main.js            # File JavaScript utama
│   ├── animations.js      # Animasi GSAP
│   └── music-player.js    # Kontrol audio
├── assets/
│   ├── images/            # Sumber daya gambar
│   ├── models/            # Model 3D (jika ada)
│   └── audio/             # Musik latar
└── README.md              # File ini
```

## 🎯 Contoh Penggunaan

### Toggle Musik
Website menampilkan pemutar musik latar dengan kontrol toggle:
- Klik ikon musik untuk play/pause
- Feedback visual menunjukkan status audio
- Kontrol volume (jika diimplementasikan)

### Interaksi Kartu 3D
Arahkan kursor ke kartu portfolio untuk merasakan:
- Pergeseran kedalaman dan perspektif
- Animasi transisi yang halus
- Konten terungkap saat interaksi

### Animasi Scroll
Saat menggulir website:
- Gambar terungkap dengan efek mask
- Elemen muncul dan menghilang dengan halus
- Lapisan parallax menciptakan kedalaman

## 🔧 Pengembangan

### Struktur SCSS
```scss
// Contoh Metodologi BEM
.block {}
.block__element {}
.block--modifier {}
```

### Setup Animasi
```javascript
// Contoh animasi GSAP
gsap.from('.card', {
  duration: 1,
  opacity: 0,
  y: 50,
  stagger: 0.2,
  ease: "power3.out"
});
```

### Menambah Section Baru
1. Buat struktur HTML dengan kelas BEM yang sesuai
2. Styling di SCSS mengikuti pola yang ada
3. Tambahkan animasi di file JavaScript
4. Test di berbagai ukuran viewport

## 🌐 Dukungan Browser

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Opera 50+

## 📱 Breakpoint Responsif

| Perangkat | Breakpoint | Fitur |
|-----------|------------|-------|
| Mobile | < 768px | Dioptimalkan sentuh, animasi disederhanakan |
| Tablet | 768px - 1024px | Layout disesuaikan, efek dikurangi |
| Desktop | > 1024px | Efek 3D penuh, animasi kompleks |

## 🎨 Kustomisasi

### Mengubah Warna
Modifikasi variabel SCSS di `_variables.scss`:
```scss
$primary-color: #ff6b6b;
$secondary-color: #4ecdc4;
$background-dark: #121212;
```

### Menambah Konten
1. Item Portfolio: Tambahkan kartu di section portfolio
2. Musik: Ganti file audio di `/assets/audio/`
3. Gambar: Optimalkan gambar untuk web dan tambahkan ke `/assets/images/`

## 📊 Tips Performa

1. **Optimasi Gambar**: Gunakan format WebP dengan fallback JPEG
2. **Optimasi Animasi**: Gunakan properti `will-change` secara strategis
3. **Lazy Loading**: Implementasikan untuk gambar di bawah fold
4. **Code Splitting**: Pisahkan logika animasi untuk loading lebih baik

## 🤝 Berkontribusi

1. Fork repository
2. Buat branch fitur (`git checkout -b fitur/FiturMenakjubkan`)
3. Commit perubahan (`git commit -m 'Tambahkan FiturMenakjubkan'`)
4. Push ke branch (`git push origin fitur/FiturMenakjubkan`)
5. Buka Pull Request

## 📝 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file LICENSE untuk detail.

## 🙏 Ucapan Terima Kasih

- Tim GSAP untuk library animasi yang luar biasa
- Inspirasi dari website gaming modern
- Kontributor komunitas untuk feedback dan testing

## 📞 Dukungan

Untuk issues, pertanyaan, atau saran:
1. Cek halaman [Issues](https://github.com/namapengguna/gameland-portfolio/issues)
2. Buat issue baru dengan deskripsi detail
3. Email: email.anda@contoh.com

---

**Dibuat dengan ❤️ untuk komunitas kreatif** | **Versi 1.0.0**

---

<div align="center">

### 🔗 Tautan Penting
[**🌐 Live Demo**](https://muhammad-r-dev.github.io/Gaming-Website-Design/) | [**📂 Repository GitHub**](https://github.com/namapengguna/gameland-portfolio)

### ⭐ Jika Anda menyukai proyek ini, beri bintang di GitHub!

[![GitHub stars](https://img.shields.io/github/stars/namapengguna/gameland-portfolio?style=social)](https://github.com/namapengguna/gameland-portfolio)
[![GitHub forks](https://img.shields.io/github/forks/namapengguna/gameland-portfolio?style=social)](https://github.com/namapengguna/gameland-portfolio)

</div>
