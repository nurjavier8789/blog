---
layout: post
title: Custom Discord Rich Presence
date: 2026-09-24
categories: [tutorial]
author: nurjavier1660
tags: [discord, how to, custom, diy, rpc, discord-rpc]
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
![Step 1 - buat aplikasi di Discord]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/1-devport.jpg)

2. Buat nama terserah kalian. Nama itu yang akan muncul di sebelah kata "Playing". Tapi bisa diganti juga saat coding nanti. (Contoh: "Playing `Terserah kalian`")
![Step 2 - Kasih nama bebas]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/2-devport.jpg)

3. Buka aplikasi yang barusan kalian buat. Kemudian buka tab "Rich Presence > Art Assets" setelah itu kalian bisa tambahin gambar terserah kalian.
![Step 3 - Upload gambar]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/3-devport.jpg)(Catatan: Saat upload gambar pastikan kalian kasih nama yang gampang biar enak ngodingnya.)\
(Catatan lagi: Jika saat kalian refresh halamannya dan gambar hilang, wajar saja karena discord masih memprosesnya. Tunggu beberapa menit setelah itu gambar kalian muncul kembali)

**Sedikit saran:**
- Kalian bisa cek gimana nanti bentuk presencenya di tab "Rich Presence > Visualizer"!
![Preview Rich Presence]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/4-devport.jpg)
- Pastikan kalian menyimpan Application ID aplikasi kalian. Karena akan dibutuhkan saat ngoding nantinya!
![Tempat App ID]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/5-devport.jpg)

# Persiapan sebelum ngoding
1. Buatlah folder kosong dimanapun
2. Buka command prompt (cmd) dan arahkan cmd ke folder untuk Custom Rich Presencenya.
3. Ketikan command ini di cmd:
    - `npm i discord-rpc`, pastikan sudah terinstall
    - `npm init`, jika tidak ingin ribet `npm init -y`
4. Buat file baru bernama bebas dengan akhiran `.js`. Pastikan pada settingan File explorer kalian bisa lihat extension file!
5. Buka file yang barusan kalian buat di VSCode atau notepad++ atau semacamnya

# Coding
Ketik codenya seperti code dibawah ini
<script src="https://gist.github.com/nurjavier8789/07baa7bdfbd74a46e6ff0d7a93bffbc0.js"></script>
Client ID disini adalah Application ID kalian masing-masing ya!\
Codingan bisa kalian sesuaikan dengan preferensi kalian masing-masing.\
Ketika kalian selesai ngoding, simpan filenya kemudian kembali ke terminal/cmd yang sebelumnya kemudian ketikan `node .` atau `node nama_file_kalian.js` dan tunggu hasilnya!

# Setelah ngoding
Hasilnya akan terlihat seperti ini!
![RPC pada profile]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/6-hasil.jpg)
![RPC pada pop up profile]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/7-hasil.jpg)
Lah terus mana buttonnya?\
Button hanya terlihat pada teman kalian. Pada POV kalian memang tidak terlihat tetapi teman kalian sebenarnya bisa melihatnya!
![POV teman kalian]({{ site.baseurl }}/assets/images/discord-rpc-tutorial/8-hasil.jpg)

---
Sekian untuk tutorial kali ini!\
Jika ada yang ditanyakan tanyakan saja di discord gwej yak ;) (Discord: nyrjavier8789)\
Have an ice day!
