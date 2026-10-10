
# 🌿 KenaliAku! — Quiz Kepribadian Sahabat

KenaliAku! adalah website quiz interaktif untuk menguji seberapa baik teman mengenal kepribadian kita. Website ini memiliki tampilan ceria yang terinspirasi dari suasana kartun Upin & Ipin.

## ✨ Fitur Utama

- Memasukkan nama pembuat quiz.
- Mengubah judul quiz.
- Membuat pertanyaan dan pilihan jawaban sendiri.
- Memilih jawaban yang benar.
- Menambah dan menghapus pertanyaan.
- Memilih kategori makanan, minuman, genre film, kartun, musik, hobi, warna, hewan, tempat liburan, dan kepribadian.
- Menambahkan kategori sendiri.
- Membuat link quiz untuk dibagikan kepada teman.
- Memasukkan nama peserta sebelum menjawab.
- Menghitung skor secara otomatis.
- Menampilkan hasil dan kunci jawaban.
- Mengedit quiz dan membuat quiz baru.
- Tampilan responsif untuk HP dan komputer.

## 🛠️ Teknologi

- HTML
- CSS
- JavaScript

Website ini tidak memerlukan framework, database, atau instalasi tambahan.

## 🚀 Cara Menggunakan

1. Buka website.
2. Masukkan nama pembuat quiz.
3. Atur judul dan pertanyaan.
4. Isi empat pilihan jawaban untuk setiap pertanyaan.
5. Tentukan jawaban yang benar.
6. Klik **Buat Link Quiz**.
7. Salin link dan bagikan kepada teman.
8. Teman memasukkan nama dan mulai menjawab.
9. Setelah semua pertanyaan dijawab, skor akan ditampilkan.
10. Teman dapat membuat quiz sendiri dan membagikan link baru.

## 🌐 Cara Deploy ke GitHub Pages

1. Buat repositori baru di GitHub.
2. Unggah `index.html` dan `README.md` ke repositori.
3. Buka menu **Settings**.
4. Pilih **Pages**.
5. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/(root)`.
7. Klik **Save**.
8. Tunggu sampai website diterbitkan oleh GitHub Pages.
9. Buka URL website yang diberikan GitHub.

Bagikan link quiz yang dihasilkan dari website tersebut kepada teman-temanmu.

## 🔗 Cara Kerja Link

Data quiz disimpan dalam bentuk teks yang dikodekan di bagian hash URL.

Artinya, pertanyaan dan pilihan jawaban ikut terbawa ketika link dibagikan. Teman tidak perlu membuat akun untuk menjawab quiz.

## ⚠️ Batasan

- Quiz belum menggunakan database.
- Hasil peserta tidak disimpan dalam leaderboard bersama.
- Kunci jawaban terdapat dalam data link sehingga masih dapat diperiksa oleh orang yang memahami cara kerjanya.
- Link dapat menjadi panjang apabila jumlah pertanyaan dan pilihan jawaban terlalu banyak.
- Untuk menyimpan hasil, membuat leaderboard, dan melindungi kunci jawaban, diperlukan backend atau database tambahan.

## 📁 Struktur Proyek

```text
kenaliaku-quiz/
├── index.html
└── README.md
```

## 🎨 Pengembangan Selanjutnya

Beberapa fitur yang dapat ditambahkan:

- Ilustrasi karakter dan suasana kampung.
- Animasi saat menjawab pertanyaan.
- Efek suara dan musik.
- Leaderboard skor peserta.
- Riwayat hasil quiz.
- Backend dan database.
- Fitur berbagi hasil ke media sosial.

## 📄 Lisensi

Proyek ini dapat dikembangkan untuk keperluan belajar dan hiburan. Gunakan aset gambar atau karakter pihak ketiga sesuai izin dan ketentuan hak cipta yang berlaku.
