- Pengembangan CodeIgniter 4
Membangun Status Status Cakupan Unduhan Rilis GitHub (terbaru menurut tanggal) Bintang GitHub Lisensi GitHub kontribusi selamat datang

- Apa itu CodeIgniter?
CodeIgniter adalah framework web full-stack PHP yang ringan, cepat, fleksibel dan aman. Informasi lebih lanjut dapat ditemukan di situs resmi .
Repositori ini menyimpan kode sumber untuk CodeIgniter 4 saja. Versi 4 adalah penulisan ulang lengkap untuk membawa kualitas dan kode ke versi yang lebih modern, sambil tetap menjaga banyak hal utuh yang telah membuat orang menyukai kerangka kerja selama bertahun-tahun.
Informasi lebih lanjut tentang rencana untuk versi 4 dapat ditemukan di pengumuman di forum.
- Dokumentasi
Panduan Pengguna adalah dokumentasi utama untuk CodeIgniter 4.
Panduan Pengguna yang sedang berlangsung saat ini dapat ditemukan di sini . Seperti halnya kerangka kerja lainnya, ini adalah pekerjaan yang sedang berjalan, dan akan melihat perubahan dari waktu ke waktu pada struktur, penjelasan, dll.
Anda mungkin juga tertarik dengan dokumentasi API untuk komponen kerangka kerja.
- Perubahan Penting dengan index.php
index.php tidak lagi di root proyek! Itu telah dipindahkan ke dalam folder publik , untuk keamanan dan pemisahan komponen yang lebih baik.
Ini berarti Anda harus mengonfigurasi server web Anda untuk "menunjuk" ke folder publik proyek Anda , dan bukan ke root proyek. Praktik yang lebih baik adalah mengonfigurasi host virtual untuk menunjuk ke sana. Praktik yang buruk adalah mengarahkan server web Anda ke root proyek dan berharap untuk masuk ke public/... , karena sisa logika dan kerangka kerja Anda terbuka.
Silakan baca panduan pengguna untuk penjelasan yang lebih baik tentang cara kerja CI4!

- Manajemen Repositori
CodeIgniter dikembangkan sepenuhnya secara sukarela. Oleh karena itu, berikan waktu hingga 7 hari untuk meninjau masalah Anda. Jika Anda belum mendengar kabar dari salah satu tim dalam jangka waktu tersebut, jangan ragu untuk memberikan komentar tentang masalah tersebut sehingga dapat kembali menjadi perhatian kami.
Kami menggunakan masalah GitHub untuk melacak BUGS dan untuk melacak paket kerja DEVELOPMENT yang disetujui . Kami menggunakan forum kami untuk memberikan DUKUNGAN dan mendiskusikan PERMINTAAN FITUR.
Jika Anda mengangkat masalah di sini yang berkaitan dengan dukungan atau permintaan fitur, itu akan ditutup! Jika Anda tidak yakin apakah Anda telah menemukan bug, ajukan utas di forum terlebih dahulu - orang lain mungkin mengalami hal yang sama.
Sebelum mengangkat masalah GitHub baru, harap periksa apakah bug Anda belum dilaporkan atau diperbaiki.
Kami menggunakan permintaan tarik (PR) untuk KONTRIBUSI ke repositori. Kami mencari kontribusi yang mengatasi salah satu bug yang dilaporkan atau paket pekerjaan yang disetujui.

Jangan gunakan PR sebagai bentuk permintaan fitur. Kontribusi yang tidak diminta hanya akan dipertimbangkan jika sesuai dengan roadmap kerangka kerja. Ingat bahwa beberapa komponen yang merupakan bagian dari CodeIgniter 3 sedang dipindahkan ke paket opsional, dengan repositori mereka sendiri.

https://drive.google.com/file/d/1wvwhrDCAAm2aLIvohiCe1OS7FTL8PTW-/view?usp=drivesdk
