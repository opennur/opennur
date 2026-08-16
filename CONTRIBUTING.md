# Contributing to OpenNur

**Bismillahirrahmanirrahim.**

Terima kasih telah berkenan berkontribusi untuk **OpenNur Project** — proyek wakaf digital yang berfokus pada pengembangan aplikasi Islami berbasis kode terbuka.

Bentuk kontribusi sangat beragam: kode, desain, konten, tinjauan, pengujian, donasi, doa, bahkan ide. Dokumen ini merupakan panduan agar kita dapat bekerja sama dengan baik dan lancar.

---

## 🌱 Prinsip Dasar

1. **Niat karena Allah**  
   Kontribusi merupakan amal jariyah, bukan untuk pamer, mencari popularitas, atau keuntungan duniawi.

2. **Terbuka dan Kolaboratif**  
   Siapa pun dapat berkontribusi tanpa memandang latar belakang, selama mengikuti aturan yang berlaku.

3. **Menghormati Ilmu dan Ulama**  
   Konten keislaman harus merujuk pada sumber yang mu'tabar (Al-Qur'an, hadis sahih, kitab ulama yang diakui). Jangan mengklaim sesuatu tanpa dasar yang jelas.

4. **Amanah dan Transparan**  
   Tidak ada agenda tersembunyi, tidak menyisipkan kode berbahaya, iklan, atau pelacak yang merugikan pengguna.

---

## 💻 Cara Berkontribusi (Pengembang)

### 1. Fork Repositori
- Buka repositori yang ingin dikerjakan, misalnya [Tahsin Qur'an](https://github.com/opennur/tahsin).
- Klik **Fork** di pojok kanan atas untuk membuat salinan ke akun GitHub Anda.

### 2. Clone Repositori
```bash
git clone https://github.com/username-anda/nama-repo.git
cd nama-repo
```

### 3. Buat Branch Baru
Berikan nama branch yang jelas, misalnya `fitur-tajwid-warna` atau `perbaikan-bug-notifikasi`.
```bash
git checkout -b fitur-anda
```

### 4. Kerjakan Perubahan
- Ikuti gaya kode yang sudah ada di proyek.
- Tulis komentar secukupnya agar mudah ditinjau.
- Pastikan tidak ada file sampah atau hasil build yang ikut di-commit.

### 5. Commit dengan Pesan yang Jelas
Gunakan format commit yang singkat dan deskriptif, misalnya:
```
feat: tambah pewarnaan tajwid pada mode mushaf
fix: perbaiki crash saat membuka surah Al-Baqarah
docs: perbarui panduan instalasi
```

### 6. Push dan Buat Pull Request
```bash
git push origin fitur-anda
```
- Buka repositori fork Anda di GitHub.
- Klik **Compare & pull request**.
- Jelaskan secara singkat apa yang diubah, alasan perubahan, serta sertakan tangkapan layar jika ada.
- Pull request akan ditinjau oleh maintainer. Mohon bersabar dan terbuka terhadap masukan.

---

## 🎨 Cara Berkontribusi (Non-Pengembang)

### Desainer UI/UX
- Membuat mockup, ikon, ilustrasi, atau aset visual.
- Mengusulkan perbaikan antarmuka agar lebih ramah pengguna.
- File desain disimpan di folder `design/` atau dikirim melalui issue/diskusi.

### Penulis Konten & Penerjemah
- Menyusun materi belajar (pelajaran bahasa Arab, kuis tajwid, kosakata, dan lain-lain).
- Menerjemahkan teks antarmuka atau konten ke bahasa lain.
- Pastikan setiap materi memiliki sumber rujukan yang jelas.

### Ahli Agama / Penuntut Ilmu
- Meninjau konten keislaman: tajwid, tafsir, hadis, fikih, doa.
- Memberikan koreksi atau validasi terkait fitur yang berkaitan dengan syariat.
- Dapat berkontribusi melalui issue, pull request, atau diskusi.

### Tester / Pengguna
- Mengunduh dan mencoba aplikasi.
- Melaporkan bug atau perilaku yang tidak wajar melalui **Issues**.
- Memberikan saran perbaikan dan fitur baru.
- Menyebarkan informasi tentang OpenNur kepada orang lain.

### Donatur
- Mendukung biaya operasional dan pengembangan melalui [Tako](https://tako.id/opennur) atau [Ko-Fi](https://ko-fi.com/opennur).
- Dana dicatat secara transparan dan digunakan untuk kebaikan proyek.

---

## 📋 Pedoman Konten Keislaman

Karena proyek ini berkaitan langsung dengan ajaran Islam, terdapat beberapa aturan yang perlu diperhatikan:

1. **Sumber Utama**  
   - Al-Qur'an: gunakan mushaf standar (riwayat Hafs ‘an ‘Ashim) dan terjemahan resmi (misalnya Kementerian Agama RI).
   - Hadis: utamakan kitab hadis sahih (Bukhari, Muslim, Abu Dawud, Tirmidzi, Nasai, Ibnu Majah, dan lain-lain). Cantumkan nomor hadis dan derajatnya jika diketahui.
   - Tafsir: rujuk kitab tafsir mu'tabar seperti Tafsir Ibnu Katsir, Tafsir As-Sa'di, Tafsir Al-Qurthubi, dan lain-lain.
   - Fikih: rujuk kitab fikih standar dari mazhab yang diakui atau fatwa lembaga kredibel.

2. **Hindari**  
   - Pendapat yang menyimpang dari Ahlus Sunnah wal Jama'ah.
   - Konten yang mengandung bid’ah, khurafat, atau klaim tanpa dasar.
   - Debat khilafiyah yang tidak produktif — jika ada perbedaan pendapat, sampaikan secara objektif dan berikan rujukannya.

3. **Verifikasi Konten**  
   - Hasil dari alat bantu teknologi modern (terjemahan, penjelasan, kuis, dan lain-lain) **wajib diverifikasi** oleh manusia yang kompeten sebelum dimasukkan ke aplikasi.
   - Teknologi adalah alat bantu, bukan sumber hukum.

---

## 🧭 Etika Komunikasi

- Gunakan bahasa yang santun, ramah, dan profesional.
- Hormati semua kontributor, apa pun latar belakangnya.
- Jangan menyerang pribadi, mengucapkan kebencian, atau berdebat secara tidak sehat.
- Jika ada perbedaan pendapat, sampaikan dengan dalil dan adab.
- Ingat, kita semua sedang berusaha beramal saleh — jangan sampai perbedaan pendapat merusak ukhuwah.

---

## 🐞 Melaporkan Bug atau Mengusulkan Fitur

Buka **Issue** di repositori terkait. Agar memudahkan, gunakan template berikut:

**Judul Issue:**  
`[Bug] Aplikasi crash saat membuka Surah Al-Baqarah`

**Deskripsi:**  
- **Versi aplikasi:** (misal v1.2.0)  
- **Perangkat:** (misal Samsung A51, Android 12)  
- **Langkah reproduksi:**  
  1. Buka aplikasi  
  2. Pilih surah Al-Baqarah  
  3. Gulir ke ayat 255  
  4. Aplikasi tiba-tiba tertutup  
- **Hasil yang diharapkan:** Aplikasi tetap berjalan normal  
- **Tangkapan layar/log:** (jika ada)

Untuk usulan fitur, jelaskan manfaat fitur tersebut bagi pengguna dan, jika memungkinkan, cara implementasinya.

---

## 📜 Lisensi

Dengan berkontribusi di OpenNur, Anda menyetujui bahwa kontribusi Anda (kode, desain, konten) akan dilisensikan di bawah:

- **Kode:** [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)  
- **Konten non-kode:** Menggunakan lisensi yang sesuai (misalnya [Creative Commons BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)), kecuali disebutkan lain.

Pastikan Anda memiliki hak atas kontribusi Anda dan tidak melanggar hak cipta pihak lain.

---

## 🤲 Penutup

Terima kasih banyak telah menyumbangkan waktu, pikiran, dan tenaga untuk proyek ini. Semoga Allah menjadikan setiap langkah kita sebagai amal jariyah yang pahalanya terus mengalir, dan semoga proyek ini menjadi sebab hidayah dan kemudahan bagi umat.

**"Barangsiapa yang menunjukkan kepada kebaikan, maka baginya pahala seperti orang yang mengerjakannya."** (HR. Muslim)

---

**OpenNur Project — Menyinari Umat dengan Kode yang Terbuka.**
