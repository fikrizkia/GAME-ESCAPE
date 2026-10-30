# 🌏 Siaga Bencana! – Game Evakuasi Gempa & Tsunami
**BMKG Stasiun Meteorologi Yogyakarta**

Game edukasi interaktif berbasis web (HTML5 Canvas) yang dirancang untuk memberikan pemahaman mitigasi bencana gempa bumi dan tsunami secara seru dan mudah dipahami.

---

## 🎮 Fitur Permainan

Game terdiri dari dua tahapan utama mitigasi bencana:

1. **Tahap 1: Gempa Bumi (Drop, Cover, Hold On)**
   - Saat gempa terjadi, pemain harus segera menuju bawah meja dan menahan tombol perlindungan (**↓**).
   - Menghindari benda jatuh seperti lampu, buku, dan reruntuhan plafon.
   - Setelah guncangan selesai, keluar ruangan secara tertib melalui pintu darurat (tanpa menggunakan lift).

2. **Tahap 2: Evakuasi Tsunami**
   - Mengikuti peringatan dini tsunami dari BMKG dengan berlari menuju **Titik Kumpul** di dataran tinggi.
   - Melompat (**↑**) untuk menghindari rintangan seperti mobil dan puing di jalan.
   - Mengumpulkan item **Tas Siaga Bencana** (Air Minum, Senter, Kotak P3K, Radio, Dokumen Penting) untuk mendapatkan poin bonus serta tips edukasi mitigasi.
   - Menghindari kejaran gelombang tsunami sebelum mencapai batas evakuasi.

---

## 🕹️ Kontrol Permainan

### Keyboard (Desktop/Laptop):
- **← / →** : Bergerak ke kiri / kanan
- **↓ (Panah Bawah)** : Menunduk / berlindung di bawah meja
- **↑ (Panah Atas) / Spasi** : Melompat
- **Enter** : Memulai game / melanjutkan dialog

### Touch Screen (HP/Tablet):
- Tersedia tombol navigasi virtual di bawah layar:
  - Tombol **◀** dan **▶** untuk arah.
  - Tombol **⬇ Lindung** untuk berlindung di bawah meja.
  - Tombol **⬆ Lompat** untuk melompati rintangan.
  - Tombol **OK** untuk konfirmasi/memulai.

---

## 📁 Struktur Direktori

```text
game-evakuasi/
│
├── index.html               # File utama game (HTML5, CSS, & JavaScript Canvas)
├── README.md                # Dokumentasi proyek
└── ready to upload/         # Folder siap hosting / upload ke server
    ├── index.html           # File siap tayang
    └── README.md            # Salinan dokumentasi
```

---

## 🚀 Cara Menjalankan & Upload

### Menjalankan secara Lokal:
Cukup klik ganda (double-click) file `index.html` pada browser modern apa saja (Chrome, Edge, Firefox, Safari). Tanpa perlu instalasi web server atau dependensi tambahan.

### Upload / Deploy ke Server:
Cukup unggah seluruh isi folder `ready to upload/` ke direktori web server (cPanel / Apache / Nginx / GitHub Pages / Vercel / Netlify).

---

## 📚 Sumber Edukasi & Rujukan
- Materi panduan mitigasi gempa & peringatan dini tsunami: **BMKG (Badan Meteorologi, Klimatologi, dan Geofisika)**
- Aplikasi resmi info cuaca & gempa: **InfoBMKG** ([bmkg.go.id](https://www.bmkg.go.id))
