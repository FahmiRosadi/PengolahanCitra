
#   UAS_PENGOLAHAN CITRA

praktikum terlampir di file UAS PENGCIT_202131164_FahmiRosadi.ipynb untuk data citra pelat.jpeg

library yang digunakan :

- imutils: melakukan translation, rotation, resizing, and skeletonization
- opencv: untuk menyederhanakan programing terkait citra digital.
- numpy: Untuk memproses kemampuan terhadap gambar
- matplotlib: untuk mendukung berbagai jenis gambar

penjelasan

- masukkan library yang dibutuhkan
- masukkan variabel citra
- ubah citra dari BGR ke grayscale
- buat filter grayscale dan cara pengaplikasiannya
- bilateral-filter untuk mengurangi noise pada citra dan tetap mempertahankan detail tepi gambar
- cv2.Canny untuk bantu deteksi tepi gambar
- setelah itu ambil kontur citra untuk crop plat nomor mobilnya
cv2.RETR_TREE untuk mengambil semua kontur dengan hirarki lengkap
- konturnya pakai library imutils
- mengurutkan kontur secara descending
- pakai looping
- dan terakhir memastikan citra edge dan biner apakah trus atau tidak


