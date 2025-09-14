# Website-Personal
Tugas 1 Pemrograman Web (Biodata Diri)

Website ini merupakan biodata sederhana yang dibuat dengan HTML dan CSS.

Struktur halaman dibagi menjadi tiga kolom utama dengan proporsi 1 : 2 : 1. Bagian kiri berisi foto profil, dan informasi singkat. Bagian tengah berisi nama lengkap, profil, dan riwayat pendidikan,daftar skills yang ditampilkan dalam bentuk badge kecil, serta kontak (ikon sosial media, email, dan lainnya). Bagian kanan berisi pengalaman.

Elemen .container diberi display:flex sehingga tiga kolom tersusun secara horizontal. Proporsi lebar ditentukan dengan .kiri { flex:1 }, .tengah { flex:2 }, dan .kanan { flex:1 }, sehingga kolom tengah menjadi dua kali lebih lebar daripada kiri dan kanan. Properti gap:20px digunakan untuk memberi jarak antar kolom agar tidak saling menempel.

Untuk styling, warna utama yang digunakan adalah #AC3B61, yang diterapkan pada background bagian kiri serta digunakan sebagai aksen untuk highlight nama dan badge skill. 
