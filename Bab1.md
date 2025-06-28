# 📘 Bab 1: Instalasi dan Konfigurasi Git

Ini adalah langkah pertama sebelum kamu mulai menggunakan Git. Di tutorial ini, kita akan:
1. Menginstal Git di komputer
2. Mengecek apakah Git sudah terpasang
3. Mengatur nama dan email sebagai identitas Git


## 🧩 1. Instalasi Git

🔹 Untuk Windows:
1. Buka situs resmi Git: https://git-scm.com/
2. Klik tombol Download for Windows
3. Jalankan file instalasi .exe yang sudah diunduh
4. Saat proses instalasi, cukup klik Next terus hingga selesai (pengaturan default sudah cukup baik)

🔹 Untuk macOS:
pergi ke bash pada macOS:

```
brew install git
```

*(Pastikan kamu sudah menginstal Homebrew. Jika belum, lihat https://brew.sh)*


🔹 Untuk Linux (Ubuntu/Debian):

```
sudo apt update
sudo apt install git
```

## ✅ 2. Cek Apakah Git Sudah Terinstal
Buka terminal (Command Prompt, Terminal, atau Git Bash), lalu ketik:

```
git --version
```

Jika berhasil, maka akan muncul informasi versi git seperti:

```    
git version 2.50.0
```


informasi versi git yang ditampilkan setiap sistem operasi berbeda-beda
