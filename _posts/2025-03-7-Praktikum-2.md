---
layout: post
title: "Membuat Index.html dan jekyll serve"
---

Membuat Index.html dan menjalankan jekyll serve

07 Mar 2025 
- Membuat index.html dan menjalankan jekyll serve

# Menjalankan jekyll serve

- setelah membuat sebuah repository dengan nama sendiri
- Clone repository tersebut ke lokal
- Kemudian masuk ke dalam folder repository tersebut dan install melalui terminal visual studio code dengan perintah berikut:
    * gem install jekyll bundler
    * bundle init
- kemudian masuk kefolder Gemfile yang muncul dan tambahkan
    * gem "jekyll" dibaris baru
- Tambahkan file baru dengan nama index.html dan isi dengan kode berikut <!DOCTYPE html>

# Hello Dunia

- Lalu ketik "jekyll build" di terminal agar menghasilkan directory _site
- Dan jalankan "jekyll serve" dan klik url https://localhost:4000 yang muncul.
- Jika web sudah berhasil dibuka, edit Gemfile.lock dan tambahkan "x86_64-Linux" pada bagian "Platforms"
- Dan ketik perintah berikut untuk push ke repository github:
    * git add .
    * git commit -m "first publish"
    * git push



