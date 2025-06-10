# FurinaMD 🌸

FurinaMD adalah bot WhatsApp Multi-Device berbasis [Baileys](https://github.com/WhiskeySockets/Baileys) yang dikembangkan untuk berbagai kebutuhan otomasi WhatsApp. Bot ini dibuat dengan fitur yang lengkap, responsif, dan mudah digunakan.

## 📦 Fitur Utama

- 📑 Menu interaktif dengan button dan list
- 🔍 Fitur downloader: YouTube, TikTok, Instagram, dll.
- 📝 Stiker maker dari gambar/video
- 🎮 Fitur game sederhana (tebak-tebakan, suit, dll.)
- 🎨 Convert media (foto ke stiker, dll.)
- 🎶 Play musik via WhatsApp
- ⚙️ Admin tools: kick, add, promote, demote
- 📊 Statistik penggunaan bot
- 📌 Dan masih banyak lagi...


## 🚀 Instalasi

### 📱 Via Termux

1. Install Node.js

```bash
pkg update && pkg upgrade
pkg install nodejs git
````

2. Clone repo

```bash
git clone https://github.com/frhndevweb/FurinaMD
cd FurinaMD
```

3. Install dependency

```bash
npm install
```

4. Jalankan bot

```bash
node index.js
```

---

### 🖥️ Via Panel Pterodactyl

1. Upload file ZIP project ke panel via menu **Files**
2. Ekstrak (unarchive) file ZIP
3. Pindahkan isi folder hasil extract ke direktori utama (**move ../**)
4. Buka menu **Home**
5. Klik **Start** untuk menjalankan bot

---

## ⚙️ Konfigurasi

Edit file `config.js` atau `settings.json` sesuai kebutuhan:

* Nomor Owner
* Prefix command
* API key layanan eksternal
* Dan lainnya

## 📚 Dokumentasi

Untuk list perintah lengkap, kamu bisa cek langsung di WhatsApp dengan ketik:

```
.menu
```

Atau buka folder `command/` untuk melihat struktur perintah.

## 📞 Kontak & Support

* Author: [hannaaffiii](https://github.com/frhndevweb)
* Website: [https://frhndevweb.my.id](https://frhndevweb.my.id)

## 📜 Lisensi

Project ini dirilis di bawah lisensi **MIT License**

---

© 2025 hannaaffiii | [frhndevweb.my.id](https://frhndevweb.my.id)
