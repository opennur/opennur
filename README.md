# OpenNur Project  
### Cahaya Ilmu yang Terbuka | The Open Light of Knowledge

> **English version:** [readme.en.md](readme.en.md)

**Bismillahirrahmanirrahim.**

OpenNur adalah proyek open-source yang berfokus pada pengembangan perangkat lunak Islami. Intinya, ini merupakan **wakaf digital**: setiap kode yang ditulis diniatkan sebagai *sadaqah jariyah*, agar pahalanya terus mengalir meskipun penulisnya telah tiada.

---

## Mengapa Kami Menggunakan Teknologi?

Sebagai latar belakang, kami sempat merenungkan: *"Apakah teknologi canggih yang ada saat ini benar-benar bermanfaat untuk urusan agama?"*

Namun, teknologi merupakan karunia Allah yang sayang apabila hanya digunakan untuk hal-hal yang kurang bermanfaat, seperti sekadar menelusuri media sosial atau percakapan yang tidak produktif. Teknologi adalah alat yang sangat kuat, dan umat Islam perlu memanfaatkannya dengan sebaik-baiknya.

Dahulu, membuat aplikasi jadwal sholat saja harus menulis kode dari awal, mengelola data astronomi, dan melakukan debugging hingga larut malam. Saat ini, dengan memanfaatkan alat bantu pengembangan yang tersedia, prototipe dapat diselesaikan dalam hitungan menit. Tentu ini merupakan kemudahan yang patut disyukuri.

Harapan kami, teknologi ini diarahkan untuk hal-hal yang bermanfaat bagi umat, misalnya mengembangkan aplikasi belajar Al-Qur'an, memahami Nahwu Shorof, mengakses tafsir, dan menghafal doa—semuanya bertujuan mendekatkan diri kepada Allah.

---

## 🌿 Misi Kami

- **Alat Bantu Al-Qur'an:** Membantu umat membaca, memahami, dan mentadabburi Al-Qur'an melalui teknologi yang akurat dan mudah diakses.
- **Transparansi:** Seluruh kode bersifat bebas (FOSS) dengan lisensi GNU GPL v3, sehingga dapat dipelajari, dimodifikasi, dan dikembangkan oleh siapa saja.
- **Wakaf Ilmu:** Sebagaimana para ulama dahulu mewakafkan kitab, kami mewakafkan kode.

---

## Visi

Menjadi gerakan bersama umat Islam dalam memanfaatkan teknologi open-source untuk membangun ekosistem aplikasi Android yang bermanfaat, transparan, dan tidak berorientasi komersial.

---

## Prinsip-Prinsip Dasar

1. **Terbuka (Open Source)**  
   Kode sumber dipublikasikan di GitHub/GitLab dengan lisensi GPL v3. Siapa pun boleh membaca, mempelajari, memodifikasi, dan menyebarluaskannya kembali.

2. **Bermanfaat**  
   Setiap fitur harus bermanfaat untuk meningkatkan kualitas ibadah dan pemahaman agama, bukan sekadar mengikuti tren atau mengejar keuntungan finansial.

3. **Amanah**  
   Tidak ada pelacakan data pribadi, tidak ada iklan, dan tidak ada motif tersembunyi. Privasi pengguna adalah prioritas utama.

4. **Ilmiah**  
   Konten keagamaan (tafsir, hadis, fikih) merujuk pada sumber yang diakui. Jika memungkinkan, melibatkan ulama atau penuntut ilmu untuk menelaah dan memberikan masukan.

5. **Sederhana**  
   Antarmuka dirancang sederhana agar mudah digunakan oleh semua kalangan, termasuk orang tua yang mungkin kurang familier dengan teknologi.

---

## 🚀 Proyek Unggulan

### [Tahsin Qur'an](https://github.com/opennur/tahsin)

Aplikasi Android untuk murojaah dan latihan membaca Al-Qur'an, dengan fitur-fitur berikut:

- 📖 **Mushaf digital** gaya Utsmani (font Amiri), memuat 114 surah secara offline, teks Arab serta terjemahan bahasa Indonesia dan Inggris.
- 🎙️ **Penilaian bacaan secara real-time** melalui mikrofon: kata berwarna hijau (benar), merah (salah), dan kuning (sedang dibaca).
- 🎨 **Pewarnaan tajwid otomatis** untuk hukum mad, ghunnah, qalqalah, ikhfa’, iqlab, idgham, dan lam jalalah, dengan opsi untuk dinonaktifkan.
- 🔊 **Audio qari’** per ayat dan per kata (Minshawy, Husary, Alafasy, dan lainnya) dengan kecepatan 0,5×–1,25×.
- 🔁 **Mode Flow** untuk murojaah tanpa perlu terus melihat layar—secara otomatis melanjutkan ke ayat berikutnya.
- 🧠 **Kuis Tajwid**: menebak hukum tajwid pada kata acak (pilihan ganda empat opsi beserta penjelasan).
- 📖 **Kosakata Al-Qur'an**: 589 kata terkurasi menggunakan sistem SRS dan kuis.
- 🎮 **Dream BIG**: permainan arcade kuis kosakata tanpa batas, dengan rekor skor dan streak yang tersimpan.
- 📚 **Belajar Bahasa Arab**: 15 pelajaran orisinal (dengan metodologi ala Durusul Lughoh) untuk pemula.
- 📊 **Statistik terintegrasi** yang menggabungkan seluruh aktivitas belajar.
- 🔍 **Pencarian ayat** (Arab dan terjemahan Indonesia/Inggris) secara offline di 114 surah.
- 🗓️ **Widget dan notifikasi “Ayah of the Day”**—satu ayat berganti setiap hari, tersedia secara offline.
- 🌙 **Mode gelap (dark mode)** dan pilihan bahasa Indonesia/Inggris.
- 🎨 **Sistem desain khusus** (tanpa Material 3) yang ringan dan khas.

> ⚠️ Aplikasi ini merupakan **alat bantu latihan**, bukan pengganti guru. Teknologi pengenalan suara (STT) hanya membaca teks ucapan, sehingga tidak dapat menilai makhraj atau panjang-pendek harakat.

---

## Rencana Pengembangan

1. **Aplikasi Jadwal Sholat Offline**  
   - Menghitung waktu sholat berdasarkan lokasi (GPS/manual).  
   - Notifikasi azan dengan pilihan suara.  
   - Arah kiblat, kalender Hijriah, serta hari-hari penting.  
   - Sepenuhnya offline, tanpa iklan, dan tanpa izin yang tidak relevan.

2. **Aplikasi Belajar Nahwu-Shorof Interaktif**  
   - Modul bertahap dari tingkat dasar hingga mahir.  
   - Latihan i’rab dan tasrif dengan koreksi otomatis.  
   - Bantuan alat modern untuk menghasilkan contoh kalimat dan latihan tambahan, yang selanjutnya divalidasi secara manual oleh ahlinya.

3. **Aplikasi Dzikir & Doa Harian**  
   - Dzikir pagi dan petang, doa harian, serta doa setelah sholat.  
   - Pengingat dan penghitung tasbih digital.  
   - Sumber dari kitab hadis sahih.

---

## 🤝 Berkontribusi

Terbuka untuk siapa saja—developer, desainer, ahli tajwid, atau siapa pun yang peduli. Silakan membaca [CONTRIBUTING.md](CONTRIBUTING.md) untuk informasi lebih lanjut.

Kontribusi yang kami butuhkan antara lain:

- **Developer Android** (Kotlin/Java/Flutter) untuk membangun dan memelihara aplikasi.
- **Desainer UI/UX** untuk merancang antarmuka yang nyaman digunakan.
- **Penulis konten & penerjemah** untuk menyusun materi belajar dan terjemahan.
- **Ahli agama/penuntut ilmu** untuk memvalidasi konten keislaman.
- **Tester** untuk memastikan kualitas dan kenyamanan aplikasi.
- **Siapa saja** yang ingin belajar—tidak harus menguasai pemrograman; kontribusi sekecil apa pun sangat berarti.

Setiap kontribusi—baik kode, desain, tulisan, doa, maupun sekadar informasi—insya Allah menjadi amal jariyah yang pahalanya terus mengalir.

---

## 🕌 Dukung OpenNur (Wakaf Kode)

Donasi digunakan untuk biaya server dan pengembangan fitur. Seluruhnya dicatat secara transparan.

- **🇮🇩 Donasi via Tako** — untuk donatur Indonesia (GoPay, OVO, Dana, transfer bank, dan lainnya).  
  [Klik di sini](https://tako.id/opennur)

- **🌍 Donasi via Ko-Fi** — untuk donatur internasional (PayPal, kartu kredit).  
  [Klik di sini](https://ko-fi.com/opennur)

> **Status:** OpenNur saat ini masih dikelola secara pribadi dan belum berbadan hukum. Mohon doa serta dukungan agar ke depannya dapat berkembang menjadi yayasan yang amanah.

---

## Penutup

Pada intinya, teknologi adalah alat. Ia dapat digunakan untuk kebaikan maupun untuk hal yang sia-sia. Sebagai umat Islam, kita dituntut menjadi *khairu ummah*—umat terbaik yang menyeru kepada kebaikan. Salah satu caranya adalah memanfaatkan teknologi untuk menyebarkan ilmu dan mempermudah ibadah.

Mari jadikan teknologi sebagai sarana menuju ridha Allah, bukan sekadar hiburan. Mari bangun warisan digital yang bermanfaat bagi generasi mendatang.

**"Dan tolong-menolonglah kamu dalam (mengerjakan) kebajikan dan takwa, dan jangan tolong-menolong dalam berbuat dosa dan pelanggaran."**  
(QS. Al-Ma’idah: 2)

*"Barangsiapa yang menunjukkan kepada kebaikan, maka baginya pahala seperti orang yang mengerjakannya."*  
(HR. Muslim)

---

**OpenNur Project — Menyinari Umat dengan Kode yang Terbuka.**
