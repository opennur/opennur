# Contributing to OpenNur

**Bismillahirrahmanirrahim.**

Segala puji bagi Allah yang telah mempertemukan kita dalam kebaikan. Terima kasih atas niat dan semangat Anda untuk berkontribusi pada **OpenNur Project** — proyek wakaf digital yang bertujuan menyinari umat dengan kode yang terbuka.

Kami menyambut semua bentuk kontribusi: kode, desain, konten, review, pengujian, donasi, doa, dan ide. Dokumen ini adalah panduan agar kolaborasi kita berjalan lancar, penuh berkah, dan tetap berada di atas landasan keilmuan yang benar.

---

## 🌱 Prinsip Dasar

1. **Niat karena Allah**  
   Setiap kontribusi hendaknya diniatkan sebagai amal jariyah, bukan untuk pamer, mencari popularitas, atau keuntungan duniawi semata.

2. **Terbuka dan Kolaboratif**  
   Semua orang dipersilakan berkontribusi tanpa memandang latar belakang, selama mengikuti aturan dan adab yang berlaku.

3. **Menghormati Ilmu dan Ulama**  
   Konten keislaman harus merujuk pada sumber yang mu'tabar (Al-Qur'an, hadits shahih, kitab ulama yang diakui). Hindari pendapat yang menyimpang, kontroversial tanpa dasar, atau klaim yang tidak dapat dipertanggungjawabkan.

4. **Amanah dan Transparan**  
   Tidak ada agenda tersembunyi, tidak menyisipkan kode berbahaya, iklan, pelacak, atau hal yang merugikan pengguna.

---

## 💻 Cara Berkontribusi (Developer)

### 1. Fork Repository
- Kunjungi repository yang ingin Anda kerjakan, misalnya [Tahsin Qur'an](https://github.com/opennur/tahsin).
- Klik tombol **Fork** di kanan atas untuk membuat salinan repository ke akun GitHub Anda.

### 2. Clone Repository
```bash
git clone https://github.com/username-anda/nama-repo.git
cd nama-repo
```

### 3. Buat Branch Baru
Gunakan nama branch yang deskriptif, misalnya `fitur-tajwid-warna` atau `perbaikan-bug-notifikasi`.
```bash
git checkout -b fitur-anda
```

### 4. Lakukan Perubahan
- Ikuti gaya kode yang sudah ada di project.
- Tulis komentar secukupnya untuk memudahkan review.
- Pastikan tidak ada file sementara atau hasil build yang ikut ter-commit.

### 5. Commit dengan Pesan yang Jelas
Gunakan format pesan commit yang singkat dan deskriptif, misalnya:
```
feat: tambah pewarnaan tajwid pada mode mushaf
fix: perbaiki crash saat membuka surah Al-Baqarah
docs: update panduan instalasi
```

### 6. Push dan Buat Pull Request
```bash
git push origin fitur-anda
```
- Buka repository fork Anda di GitHub.
- Klik **Compare & pull request**.
- Jelaskan secara singkat apa yang Anda ubah, alasan perubahan, dan jika ada screenshot/tangkapan layar, sertakan.
- Pull Request akan direview oleh maintainer. Mohon bersabar dan terbuka terhadap masukan.

---

## 🎨 Cara Berkontribusi (Non-Developer)

### Desainer UI/UX
- Membuat mockup, ikon, ilustrasi, atau aset visual.
- Menyarankan perbaikan antarmuka agar lebih ramah pengguna.
- File desain bisa disimpan di folder `design/` atau dikirim melalui issue/diskusi.

### Penulis Konten & Penerjemah
- Menyusun materi pembelajaran (misalnya pelajaran bahasa Arab, kuis tajwid, kosakata).
- Menerjemahkan teks antarmuka atau konten ke bahasa lain.
- Pastikan setiap materi mencantumkan sumber rujukan.

### Ahli Agama / Penuntut Ilmu
- Mereview konten keislaman: tajwid, tafsir, hadits, fiqih, doa.
- Memberikan koreksi atau validasi terhadap fitur yang berkaitan dengan syariat.
- Bisa berkontribusi melalui issue, pull request, atau diskusi.

### Tester / Pengguna
- Mengunduh dan mencoba aplikasi.
- Melaporkan bug atau perilaku yang tidak diharapkan melalui **Issues**.
- Memberikan saran perbaikan dan fitur baru.
- Menyebarkan informasi tentang OpenNur.

### Donatur
- Mendukung biaya operasional dan pengembangan melalui [Tako](https://tako.id/opennur) atau [Ko-Fi](https://ko-fi.com/opennur).
- Dana dicatat secara transparan dan digunakan untuk kebaikan proyek.

---

## 📋 Pedoman Konten Keislaman

Karena proyek ini berhubungan langsung dengan ajaran Islam, kami menetapkan beberapa aturan:

1. **Sumber Utama**  
   - Al-Qur'an: gunakan mushaf standar (riwayat Hafs 'an 'Ashim) dan terjemahan resmi (misalnya Kemenag RI).
   - Hadits: utamakan kitab hadits shahih (Bukhari, Muslim, Abu Dawud, Tirmidzi, Nasai, Ibnu Majah, dll). Cantumkan nomor hadits dan derajatnya jika diketahui.
   - Tafsir: rujuk kitab tafsir mu'tabar seperti Tafsir Ibnu Katsir, Tafsir As-Sa'di, Tafsir Al-Qurthubi, dll.
   - Fiqih: rujuk kitab-kitab fiqih standar dari madzhab yang diakui atau fatwa lembaga yang kredibel.

2. **Hindari**  
   - Pendapat yang menyimpang dari Ahlus Sunnah wal Jama'ah.
   - Konten yang mengandung bid'ah, khurafat, atau klaim tanpa dasar.
   - Debat khilafiyah yang tidak produktif; jika ada perbedaan pendapat, sampaikan secara objektif dan sebutkan rujukannya.

3. **Verifikasi AI**  
   - Hasil yang dihasilkan oleh AI (misalnya terjemahan, penjelasan, kuis) **wajib diverifikasi** oleh manusia yang berkompeten sebelum dimasukkan ke dalam aplikasi.
   - AI adalah alat bantu, bukan sumber hukum.

---

## 🧭 Etika Komunikasi

- Gunakan bahasa yang santun, ramah, dan profesional.
- Hormati semua kontributor, apa pun latar belakangnya.
- Hindari serangan pribadi, ujaran kebencian, dan perdebatan yang tidak sehat.
- Jika ada perbedaan pendapat, sampaikan dengan dalil dan adab.
- Ingatlah bahwa kita semua sedang berusaha beramal shalih; jangan sampai perbedaan merusak ukhuwah.

---

## 🐞 Melaporkan Bug atau Mengusulkan Fitur

Silakan buka **Issue** di repository terkait. Untuk memudahkan, gunakan template berikut:

**Judul Issue:**  
`[Bug] Aplikasi crash saat membuka Surah Al-Baqarah`

**Deskripsi:**  
- **Versi aplikasi:** (misal v1.2.0)  
- **Perangkat:** (misal Samsung A51, Android 12)  
- **Langkah reproduksi:**  
  1. Buka aplikasi  
  2. Pilih surah Al-Baqarah  
  3. Scroll ke ayat 255  
  4. Aplikasi tiba-tiba tertutup  
- **Hasil yang diharapkan:** Aplikasi tetap berjalan normal  
- **Screenshot/log:** (jika ada)

Untuk usulan fitur, jelaskan manfaat fitur tersebut bagi pengguna dan, jika memungkinkan, bagaimana implementasinya.

---

## 📜 Lisensi

Dengan berkontribusi pada OpenNur, Anda menyetujui bahwa kontribusi Anda (kode, desain, konten) akan dilisensikan di bawah:

- **Kode:** [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)  
- **Konten non-kode:** Dapat menggunakan lisensi yang sesuai (misalnya [Creative Commons BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)), kecuali disebutkan lain.

Pastikan Anda memiliki hak atas kontribusi yang Anda berikan dan tidak melanggar hak cipta pihak lain.

---

## 🤲 Penutup

Kami sangat menghargai setiap detik waktu, pikiran, dan tenaga yang Anda luangkan untuk proyek ini. Semoga Allah menjadikan setiap langkah kita sebagai amal jariyah yang terus mengalir pahalanya, dan semoga proyek ini menjadi sebab hidayah dan kemudahan bagi umat.

**“Barangsiapa yang menunjukkan kepada kebaikan, maka baginya pahala seperti orang yang mengerjakannya.”** (HR. Muslim)

---

**OpenNur Project — Menyinari Umat dengan Kode yang Terbuka.**
