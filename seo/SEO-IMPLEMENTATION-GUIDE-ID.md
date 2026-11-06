# Paket SEO COCOVANTA — Panduan Repository

Paket ini melengkapi fondasi SEO teknis situs `https://cocovanta.web.id/`. Tidak ada file yang dapat menjamin posisi 5 besar; ranking ditentukan sistem Google berdasarkan relevansi, kualitas, reputasi, pengalaman halaman, kompetisi, dan konteks pencarian.

## File yang ditambahkan/diperbarui

- `robots.txt`: mengizinkan crawling halaman publik dan menunjuk sitemap utama.
- `sitemap.xml`: daftar URL kanonis dengan `lastmod` dan metadata gambar untuk halaman relevan.
- `seo/SEO-KEYWORD-CLUSTERS-ID.md`: kelompok kata kunci dan pemetaan halaman agar tidak saling bersaing.
- `seo/CONTENT-PLAN-90-DAYS-ID.md`: rencana konten berbasis kebutuhan importir.
- `seo/STRUCTURED-DATA-NOTES-ID.md`: penjelasan schema Organization/WebSite yang disisipkan pada halaman HTML.
- `humans.txt`: identitas dan informasi situs.

## Cara memasukkan ke repository

1. Ekstrak ZIP website.
2. Salin seluruh isi folder ke root repository GitHub, pertahankan struktur folder.
3. Commit ke branch kerja, periksa diff, lalu merge/deploy ke production setelah lolos pengujian.
4. Pastikan `https://cocovanta.web.id/sitemap.xml` dapat dibuka dan mengembalikan HTTP 200.
5. Di Google Search Console, submit `sitemap.xml` satu kali.
6. Gunakan URL Inspection untuk halaman penting dan minta pengindeksan setelah halaman live.

## Catatan penting

- Tag `meta keywords` tidak digunakan Google sebagai sinyal ranking; jangan menambahkannya berulang.
- Jangan membuat halaman doorway per negara/kota atau artikel massal yang tipis.
- Jangan menambahkan harga, sertifikasi, kapasitas produksi, MOQ, laboratorium, atau klaim pabrik jika belum dapat dibuktikan.
- Informasi spesifikasi harus menyebutkan bila masih indikatif dan harus dikonfirmasi per lot.
- Schema harus sesuai informasi yang terlihat di halaman. Jangan menambahkan rating, review, Product Offer, atau alamat kantor rinci yang tidak nyata.
- `lastmod` harus diperbarui hanya ketika konten halaman benar-benar berubah secara substansial.
