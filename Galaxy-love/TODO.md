# TODO: Perbaiki Halaman Buku Scrapbook

## Langkah-langkah Implementasi

1. **Modifikasi struktur scrapbookPages**
   - Ubah dari objek dengan left (text) dan right (image) menjadi leftPhotos (array images) dan rightPhotos (array images)
   - Buat 2 halaman: halaman 0 dengan img1-4, halaman 1 dengan img5-6 dan pesan akhir

2. **Update fungsi updatePageContent**
   - Ubah untuk menampilkan grid foto di page-left dan page-right menggunakan polaroid-photo
   - Tambahkan event listener ke setiap foto untuk membalik halaman

3. **Modifikasi event listener scrapbook**
   - Jika belum terbuka, buka buku
   - Jika klik pada foto, balik ke halaman berikutnya

4. **Perbaiki animasi membalik buku**
   - Tambahkan kelas CSS untuk animasi membalik halaman yang lebih realistis
   - Gunakan transform rotateY untuk simulasi membalik

5. **Test fungsionalitas**
   - Pastikan buku terbuka dengan animasi
   - Klik foto membalik halaman dengan animasi
   - Loop kembali ke halaman pertama setelah halaman terakhir
