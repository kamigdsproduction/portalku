INDONEWSTODAY.COM — SINGLE-FILE PHP CMS

Kebutuhan: PHP 8.1+, Apache, ekstensi json/session/fileinfo/mbstring.

INSTALASI:
1. Upload seluruh isi folder ini ke public_html.
2. Pastikan uploads/ dapat ditulis PHP (biasanya 755).
3. Buka https://domain-anda/index.php?admin=1
4. Login awal: admin / admin12345
5. Segera buat/ganti password admin melalui Manajemen User.

Semua fungsi utama berada dalam index.php:
- Frontend magazine style
- Detail berita
- Kategori
- Breaking News ticker
- Berita populer
- Login session
- Role admin/penulis
- CRUD berita/menu/user
- Upload gambar
- Quill editor
- JSON flat-file
- Pembatasan penulis hanya mengedit/menghapus berita sendiri

JSON jangan dihapus. .htaccess mencegah akses langsung JSON di Apache.
Untuk produksi, ganti password default segera setelah instalasi.
