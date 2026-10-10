
# 🎮 PlayZone — Dunia Permainan Anak Remaja

PlayZone adalah website permainan ringan untuk remaja berusia sekitar 13–19 tahun. Website ini menjadi tempat untuk bermain kuis, menguji pengetahuan, memecahkan teka-teki, dan bersenang-senang bersama teman.

Website dibuat menggunakan HTML, CSS, dan JavaScript murni sehingga dapat berjalan langsung di browser dan dipublikasikan secara gratis menggunakan GitHub Pages.

## ✨ Fitur Utama

1. **Kuis Kepribadian**
   - Menjawab pertanyaan tentang kebiasaan dan gaya belajar.
   - Mendapatkan hasil berupa deskripsi karakter.
   - Mengulang kuis dan membagikan hasil.

2. **Seberapa Kenal Kamu dengan Aku?**
   - Membuat kuis sendiri dengan 1–10 pertanyaan.
   - Menambahkan empat pilihan jawaban dan kunci jawaban.
   - Menghasilkan link yang bisa dibagikan kepada teman.
   - Menghitung skor dan menampilkan pembahasan jawaban.
   - Memungkinkan pemain membagikan hasilnya kembali.

3. **Tebak Kata**
   - Menebak kata berdasarkan petunjuk.
   - Memilih kategori yang tersedia.
   - Mendapatkan poin dari jawaban yang benar.

4. **Teka-Teki Logika**
   - Menjawab pertanyaan logika.
   - Mendapatkan skor dan pembahasan.
   - Melihat review jawaban setelah selesai.

5. **Kuis Pengetahuan Umum**
   - Pertanyaan tentang sains, sejarah, olahraga, teknologi, dan pengetahuan sehari-hari.
   - Timer 15 detik untuk setiap pertanyaan.
   - Skor otomatis dan review jawaban.

6. **Pilih Salah Satu**
   - Memilih di antara dua pilihan yang unik.
   - Mendapatkan ringkasan pilihan di akhir permainan.

7. **Truth or Dare Digital**
   - Kategori santai, lucu, dan persahabatan.
   - Pertanyaan dan tantangan yang aman.
   - Pemain boleh melewati tantangan yang membuatnya tidak nyaman.

8. **Fitur Pendukung**
   - Pencarian permainan berdasarkan nama.
   - Filter berdasarkan kategori.
   - Menu navigasi responsif.
   - Skor terbaik yang disimpan di browser untuk beberapa permainan.
   - Tombol berbagi hasil atau menyalin teks.
   - Desain responsif untuk HP, tablet, dan komputer.

## 🛠️ Teknologi

- HTML5
- CSS3
- JavaScript murni
- `localStorage` untuk menyimpan skor terbaik secara lokal.
- Web Share API dan Clipboard API jika didukung oleh browser.

Website tidak memerlukan framework, database, API key, atau backend.

## 📁 Struktur File

```text
playzone/
├── index.html
└── README.md
```

## 💻 Cara Menjalankan Secara Lokal

1. Buat folder bernama `playzone`.
2. Simpan kode website dalam file `index.html`.
3. Simpan dokumentasi ini sebagai `README.md` di folder yang sama.
4. Buka `index.html` menggunakan browser modern.
5. Website dapat langsung digunakan.

## 🚀 Cara Mengunggah ke GitHub

1. Masuk ke [GitHub](https://github.com/).
2. Buat repository baru, misalnya `playzone`.
3. Unggah file `index.html` dan `README.md` ke folder utama repository.
4. Pastikan nama file halaman utama adalah `index.html`.
5. Klik **Commit changes** untuk menyimpan file.

## 🌐 Cara Mengaktifkan GitHub Pages

1. Buka repository `playzone`.
2. Pilih menu **Settings**.
3. Buka bagian **Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`.
6. Klik **Save**.
7. Tunggu proses publikasi selesai.
8. Buka alamat website yang ditampilkan oleh GitHub Pages.

Alamat website biasanya berbentuk:

`https://nama-akun.github.io/playzone/`

Ganti `nama-akun` dengan nama akun GitHub kamu.

## 🎲 Cara Menggunakan Permainan

### Kuis Kepribadian
Pilih permainan, masukkan nama, jawab pertanyaan, dan lihat hasil kepribadian yang diberikan.

### Kuis Pertemanan
Pilih **Buat kuis**, masukkan nama dan judul, tambahkan pertanyaan beserta empat pilihan jawaban, lalu tentukan kunci jawaban. Setelah link dibuat, salin dan kirim kepada teman.

Teman dapat membuka link tersebut, memasukkan nama, menjawab pertanyaan, dan melihat skor akhirnya.

### Tebak Kata
Masukkan nama, pilih kategori, lalu tebak kata berdasarkan petunjuk. Jawaban benar bernilai 10 poin.

### Teka-Teki Logika dan Pengetahuan Umum
Masukkan nama, jawab pertanyaan pilihan ganda, baca pembahasan, dan lihat skor akhir.

### Pilih Salah Satu
Masukkan nama dan pilih satu opsi pada setiap dilema. Di akhir, website menampilkan ringkasan pilihan.

### Truth or Dare
Masukkan nama, pilih kategori, lalu pilih Truth atau Dare. Semua pemain boleh melewati tantangan yang tidak nyaman.

## 🔒 Penyimpanan Data dan Keterbatasan

- Website tidak memiliki database online atau backend.
- Skor terbaik disimpan di `localStorage` pada browser dan perangkat yang digunakan. Skor tidak otomatis tersinkronisasi ke perangkat lain.
- Kuis pertemanan disimpan di bagian hash URL, yaitu teks setelah tanda `#` pada link. Dengan demikian, kuis dapat dibuka tanpa server.
- Kunci jawaban kuis pertemanan juga berada di dalam URL. Jangan gunakan informasi pribadi atau pertanyaan rahasia.
- Pembuat kuis tidak menerima skor teman secara otomatis. Pemain harus membagikan hasilnya kembali melalui pesan atau tangkapan layar.
- Link kuis yang terlalu panjang mungkin tidak nyaman dibagikan. Kurangi jumlah atau panjang pertanyaan jika diperlukan.
- Fitur berbagi bergantung pada dukungan browser. Jika Web Share API tidak tersedia, website mencoba menyalin teks ke clipboard.
- Menghapus data situs di browser dapat menghapus skor terbaik yang tersimpan.
- Hasil kuis kepribadian hanya untuk hiburan, bukan penilaian psikologis.

## 💡 Ide Pengembangan Selanjutnya

- Menambahkan lebih banyak soal dan kategori permainan.
- Menambahkan tema gelap.
- Membuat mode beberapa pemain dalam satu perangkat.
- Menambahkan akun dan papan peringkat online melalui backend.
- Menambahkan penyimpanan kuis pertemanan secara online.
- Meningkatkan aksesibilitas dan menguji kompatibilitas di berbagai browser.

## 📄 Lisensi

Proyek ini dapat digunakan dan dimodifikasi untuk keperluan pembelajaran. Kamu bebas mengembangkan desain dan fiturnya sesuai kebutuhan.
