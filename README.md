## Proyek ini akan berisi:

Sebuah bot Discord interaktif yang dirancang untuk membantu mahasiswa mengeksplorasi jalur karir berdasarkan dua pendekatan utama: **Kesesuaian Jurusan Kuliah** atau **Minat & Bakat Pribadi**. Bot ini terintegrasi dengan database SQL untuk menyimpan data kuis, referensi karir, dan informasi lowongan kerja terbaru.

### 📊 Desain Database (SQL)
Proyek ini menggunakan database relasional dengan struktur tabel sebagai berikut (Catatan: Semua penulisan teks menghindari penggunaan tanda petik tunggal/apostrof seperti *doesnt* atau *havent* untuk menjaga keamanan eksekusi sintaks SQL):
1. **Tabel Pertanyaan (`kuis_pertanyaan`)**: Menyimpan daftar pertanyaan kuis beserta pilihan jawaban untuk menentukan kecenderungan minat atau kesesuaian jurusan.
2. **Tabel Daftar Karir (`daftar_karir`)**: Memuat informasi profil profesi, deskripsi kerja, serta keahlian yang dibutuhkan.
3. **Tabel Lowongan Pekerjaan (`loker_aktif`)**: Berisi info lowongan kerja, nama perusahaan, syarat, dan link pendaftaran yang bisa diakses pengguna.

---

## 🤖 Daftar Command (Perintah Bot)

Berikut adalah perintah-perintah yang dapat digunakan oleh pengguna di dalam server Discord:

| Command | Deskripsi |
| :--- | :--- |
| `!mulai` |  Bot akan menyapa pengguna dan memberikan opsi pilihan: Apakah ingin mencari karir berdasarkan **Jurusan Saat Ini** atau **Minat/Hobi**. |
| `!tanya` | Menampilkan saran karir sesuai dengan minat/jurusan pengguna. |
| `!loker` | Menampilkan daftar lowongan pekerjaan terbaru yang tersedia di dalam database, lengkap dengan syarat dan link eksternal. |
| `!tipstrickslamaran` | Menyajikan tips seputar dunia kerja, cara menghadapi interview, cara negosiasi gaji, dan persiapan mental bagi *fresh graduate*. |
| `!saranportfolio` | Memberikan panduan dan poin-poin penting dalam menyusun portfolio. |
| `!help` | Menampilkan daftar-daftar command beserta jurusan serta pekerjaan yg trsedia di database |

---

## 🚀 Alur Kerja Bot
1. Pengguna mengetik `!mulai` dan 
