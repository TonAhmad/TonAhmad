# 🎨 GitHub Profile Customization Guide

Panduan lengkap untuk menyesuaikan profil GitHub Anda yang telah dipercantik.

## 📋 Daftar Fitur yang Sudah Ditambahkan

### 1. ✨ Animated Typing Effect
**Lokasi:** Header profil  
**Service:** [Readme Typing SVG](https://readme-typing-svg.herokuapp.com)

**Cara Customize:**
```markdown
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=435&lines=Welcome+to+my+GitHub+Profile!;Developer+%7C+Learner+%7C+Creator;Always+learning+something+new" />
```

**Parameter yang bisa diubah:**
- `font`: Ganti font (contoh: `Fira+Code`, `Roboto`, `Arial`)
- `color`: Ganti warna teks (hex code tanpa #)
- `lines`: Ganti teks yang ditampilkan (pisahkan dengan `;`)
- `pause`: Durasi pause antar teks (dalam ms)

### 2. 📊 GitHub Statistics
**Service:** [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)

**Fitur:**
- Total commits, PRs, issues
- Star yang diterima
- Bahasa pemrograman yang paling sering digunakan

**Theme yang tersedia:**
- `tokyonight` (current)
- `radical`
- `merko`
- `gruvbox`
- `dark`
- `default`
- dan banyak lagi...

**Cara ganti theme:**
```markdown
theme=tokyonight  →  theme=radical
```

### 3. 🔥 Contribution Streak
**Service:** [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)

**Menampilkan:**
- Total contributions streak
- Longest streak
- Current streak

**Theme yang cocok dengan Tokyo Night:**
- `tokyonight`
- `dark`
- `radical`

### 4. 🏆 GitHub Trophies
**Service:** [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)

**Menampilkan:**
- Achievements berdasarkan aktivitas GitHub
- Followers, stars, commits, dll

**Customize layout:**
```markdown
row=1  →  row=2  (untuk 2 baris trophy)
column=6  (mengatur jumlah kolom)
```

### 5. 📈 Contribution Activity Graph
**Service:** [GitHub Readme Activity Graph](https://github.com/ashutosh00710/github-readme-activity-graph)

**Menampilkan:**
- Grafik aktivitas kontribusi yang lebih menarik dari default GitHub
- Visualisasi area chart yang indah

**Theme options:**
- `tokyo-night`
- `github`
- `xcode`
- `rogue`

### 6. 💻 Tech Stack Badges
**Service:** [Shields.io](https://shields.io)

**Cara menambah badge baru:**
```markdown
![NamaTech](https://img.shields.io/badge/namatech-warna?style=for-the-badge&logo=namalogo&logoColor=white)
```

**Contoh badges populer:**
```markdown
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
```

### 7. 🌐 Social Media Badges
**Cara menambah social media:**

**LinkedIn:**
```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
```

**Twitter:**
```markdown
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
```

**Instagram:**
```markdown
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/yourhandle)
```

**Discord:**
```markdown
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/yourinvite)
```

### 8. 📌 Profile Views Counter
**Service:** [Komarev's Profile Views Counter](https://github.com/antonkomarev/github-profile-views-counter)

**Customize warna:**
```markdown
color=blueviolet  →  color=brightgreen/blue/red/orange/yellow/green
```

## 🎨 Tips Customization

### Mengubah Color Scheme
Semua komponen menggunakan theme **Tokyo Night** untuk konsistensi. Untuk mengubah:

1. **GitHub Stats:** ubah `theme=tokyonight` ke theme lain
2. **Streak Stats:** ubah `theme=tokyonight` ke theme lain
3. **Trophy:** ubah `theme=tokyonight` ke theme lain
4. **Activity Graph:** ubah `theme=tokyo-night` ke theme lain

**Pastikan semua menggunakan theme yang sama untuk tampilan yang konsisten!**

### Menambah Section Baru

**Portfolio Section:**
```markdown
## 🎯 Featured Projects

### [Project Name](link-to-repo)
Brief description of your amazing project

![Project Screenshot](link-to-screenshot)
```

**Currently Learning Section:**
```markdown
## 📚 Currently Learning

- 🔭 Working on: [project name]
- 🌱 Learning: [technology/skill]
- 👯 Looking to collaborate on: [type of projects]
```

**Blog Posts Section:**
```markdown
## 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- [Blog post title](link)
- [Blog post title](link)
<!-- BLOG-POST-LIST:END -->
```

### Menambah Animasi Lebih Banyak

**Snake Animation (contribution graph eating snake):**
```markdown
![Snake animation](https://github.com/TonAhmad/TonAhmad/blob/output/github-contribution-grid-snake.svg)
```
*Note: Memerlukan GitHub Action setup terpisah*

**Metrics:**
```markdown
![Metrics](https://metrics.lecoq.io/TonAhmad?template=classic&config.timezone=Asia%2FJakarta)
```

## 🔧 Troubleshooting

### Stats tidak muncul?
- Pastikan repository TonAhmad/TonAhmad adalah public
- Tunggu beberapa menit untuk cache refresh
- Coba tambahkan `&cache_seconds=1800` di URL

### Badge tidak sesuai?
- Periksa nama logo di [Simple Icons](https://simpleicons.org/)
- Pastikan URL encode karakter khusus

### Theme tidak konsisten?
- Pastikan semua service menggunakan nama theme yang sama
- Beberapa service menggunakan `tokyonight`, lainnya `tokyo-night`

## 📖 Resources

- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)
- [Activity Graph](https://github.com/ashutosh00710/github-readme-activity-graph)
- [Shields.io](https://shields.io)
- [Simple Icons](https://simpleicons.org/)
- [Typing SVG](https://readme-typing-svg.herokuapp.com)

## 💡 Tips Tambahan

1. **Update secara berkala** - Sesuaikan konten dengan skill dan project terbaru
2. **Jaga kesederhanaan** - Jangan terlalu banyak elemen yang bisa membuat loading lambat
3. **Konsistensi theme** - Gunakan color scheme yang konsisten
4. **Mobile-friendly** - Pastikan terlihat bagus di mobile
5. **Personalisasi** - Tambahkan sentuhan personal yang mencerminkan diri Anda

---

**Happy Customizing! 🚀**
