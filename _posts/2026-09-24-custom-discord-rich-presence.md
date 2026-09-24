---
layout: post
title: Custom Discord Rich Presence
date: 2026-09-24
categories: [tutorial]
author: nurjavier1660
tags: [discord, how to, custom, diy]
---

[Cek source codenya disini!](https://github.com/nurjavier8789/discord-presence-js)

Pernah gak sih kalian kepikiran untuk membuat tulisan custom di samping kata "Playing" di Discord? Well, ternyata gak cuma kalian aja yang berpikiran seperti itu. Diriku yang dulu juga berpikir begitu.

Kali ini aku mau sharing cara membuat Custom Discord Rich Presence menggunakan node.js!

# Persiapan
Yang perlu kalian siapkan yaitu:
- Laptop/PC
- [Node.js](https://nodejs.org)
- IDE/Tempat untuk coding (VSCode, notepad++, dkk.)
- Discord (pasti)

# Menyiapkan discord application
1. Pergi ke website [Discord Developer Portal](https://discord.com/developers/applications) kemudian buat aplikasi baru
![Step 1 - buat aplikasi di Discord](./ce3831213da8d729d50621e2da16d29e.jpg)

2. Buat nama terserah kalian. Nama itu yang akan muncul di sebelah kata "Playing". Tapi bisa diganti juga saat coding nanti. (Contoh: "Playing `Terserah kalian`")
![Step 2 - Kasih nama bebas](./0934864918eefb4a6a5b681aa75fa349.jpg)

3. Buka aplikasi yang barusan kalian buat. Kemudian buka tab "Rich Presence > Art Assets" setelah itu kalian bisa tambahin gambar terserah kalian.
![Step 3 - Upload gambar](./8ed73563a1524f5910e3d584b523562c.jpg)(Catatan: Saat upload gambar pastikan kalian kasih nama yang gampang biar enak ngodingnya.)\
(Catatan lagi: Jika saat kalian refresh halamannya dan gambar hilang, wajar saja karena discord masih memprosesnya. Tunggu beberapa menit setelah itu gambar kalian muncul kembali)

**Sedikit saran:**
- Kalian bisa cek gimana nanti bentuk presencenya di tab "Rich Presence > Visualizer"!
![Preview Rich Presence](./60ba784a68bf8c81d25d217d6a78e1f1.jpg)
- Pastikan kalian menyimpan Application ID aplikasi kalian. Karena akan dibutuhkan saat ngoding nantinya!
![Image](./38c909839460b84806e2e05812a16a20.jpg)

# Persiapan sebelum ngoding
1. Buatlah folder kosong dimanapun
2. Buka command prompt (cmd) dan arahkan cmd ke folder untuk Custom Rich Presencenya.
3. Ketikan command ini di cmd:
    - `npm i discord-rpc`, pastikan sudah terinstall
    - `npm init`, jika tidak ingin ribet `npm init -y`
4. Buat file baru bernama bebas dengan akhiran `.js`. Pastikan pada settingan File explorer kalian bisa lihat extension file!
5. Buka file yang barusan kalian buat di VSCode atau notepad++ atau semacamnya
6. Ketik codenya seperti code dibawah ini
