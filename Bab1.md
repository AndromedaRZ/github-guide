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


## 📝 3. Konfigurasi Git (Wajib)
Setelah Git terpasang, kita perlu memberi tahu Git siapa kita. Ini penting karena setiap perubahan yang kita simpan akan mencatat nama dan email kita.
Buka terminal, lalu jalankan:
```
git config --global user.name "Nama Kamu"
git config --global user.email "emailkamu@example.com"
```

contoh
```
git config --global user.name "Rizky"
git config --global user.email "rizky.dev@gmail.com"
```

untuk memastikannya, ketik:
```
git config user.name
git config user.email
```

maka kamu akan melihat hasil seperti ini:
```shell
user.name=Rizky
user.email=rizky.dev@gmail.com
```
