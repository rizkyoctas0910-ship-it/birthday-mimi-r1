CARA PAKAI
1. Taruh foto/video di folder images/ (nama file tanpa spasi, mis. foto1.jpg).
2. Buka data.json dan isi sesuai kebutuhan:
   - name, birth, tog (tanggal lahir dan jadian, format YYYY-MM-DD)
   - header.src: "images/header.jpg" (foto atau video mp4/webm)
   - gallery: tambah {"src":"images/foto1.jpg","caption":"Liburan pertama"}
   - milestones[].media: "images/foto1.jpg" untuk memunculkan tombol lihat foto/video
   - todo[].done: true atau false
3. Unggah semua ke repository GitHub (index.html, data.json, folder images).
4. Aktifkan Settings > Pages (branch main, folder root).
UPDATE: edit data.json di GitHub (ikon pensil) lalu Commit changes.
Halaman pasangan memeriksa data.json setiap 30 detik, jadi perubahan tampil sekitar 1-2 menit tanpa perlu memuat ulang.
Pasangan hanya melihat. Tidak ada tombol edit di halaman ini.
