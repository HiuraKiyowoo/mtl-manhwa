---
name: mtl-manhwa
description: Translate Korean manhwa/webtoon pages into natural, context-aware Indonesian; preserve reading order, apply a verified Cosmic ID style guide, maintain a six-category chapter glossary, and flag uncertain OCR. Use for Korean-to-Indonesian manhwa translation, chapter glossary work, or editor-ready Cosmic ID output.
---

# MTL Manhwa — Korean to Indonesian

Terjemahkan manhwa Korea ke bahasa Indonesia yang natural, konsisten, dan siap diperiksa editor. Pisahkan hasil terjemahan bersih dari catatan OCR/QC. Jangan mengarang teks sumber, detail glossary, atau aturan format.

## Aturan utama

- Baca gambar berdasarkan urutan halaman dan panel yang terlihat. Untuk webtoon vertikal, ikuti aliran panel dari atas ke bawah; di dalam panel, ikuti susunan balon/teks yang benar-benar tampak.
- Tangani satu chapter sebagai satu pekerjaan dengan ledger/ceklist halaman atau berkas agar tidak ada halaman, panel, atau dialog yang terlewat atau diproses dua kali.
- Terjemahkan dialog, monolog, narasi, dan SFX yang relevan dengan cerita. Abaikan watermark, logo, kredit scanlation, username, URL, promosi, nomor halaman, serta teks noncerita.
- Gunakan bahasa Indonesia yang luwes dan sesuai konteks, karakter, relasi, emosi, dan register. Pertahankan maksud, bukan susunan kata Korea secara kaku. Jangan menambah informasi yang tidak ada pada sumber.
- Tandai teks yang tetap tidak terbaca sebagai `[PERLU CEK MANUAL: lokasi]`; jangan menebak atau mengisi dialog dari konteks semata. Jika pembacaan ulang memperjelasnya, gunakan teks yang terverifikasi dan jangan tampilkan penanda itu di hasil TL bersih.
- Jangan menyatakan OCR sempurna atau coverage lengkap jika sumber tidak terbaca/terpotong atau halaman tidak tersedia.

## Workflow

### 1. Terima dan inventarisasi input

Kenali chapter, halaman/berkas, urutannya, bahasa target, glossary/style sheet sebelumnya, dan pedoman Cosmic ID yang diberikan. Jika input berisi beberapa gambar, susun daftar sesuai nama/urutan yang diberikan pengguna; jangan mengurutkan alfabetis jika itu bertentangan dengan urutan sumber. Catat halaman yang hilang/duplikat/ambigu.

### 2. Baca gambar dan pulihkan teks

1. Inspeksi gambar utuh terlebih dahulu. Ukuran atau rasio panjang saja bukan alasan untuk memecah gambar; pecah/crop hanya bila teks relevan tidak terbaca pada tampilan utuh.
2. Jika bagian tertentu kecil atau buram, periksa crop area itu pada resolusi sumber. Untuk strip panjang yang keseluruhan teksnya tak terbaca, buat bagian berurutan dengan overlap yang cukup agar balon/panel di batas tidak terpotong. Ikuti panduan `read-special-images` bila tersedia.
3. Baca semua tile/crop sesuai urutan; gunakan overlap untuk mengenali pengulangan, bukan untuk menyalin dialog dua kali. Rekonsiliasi perbedaan OCR memakai tampilan sumber yang paling jelas.
4. Catat urutan panel/balon dan teks sumber yang terbaca sebelum menyatukan hasil. Jangan menganggap OCR otomatis benar. Jika teks tetap tak terpulihkan, masukkan hanya penanda tinjauan manual dalam bagian catatan.

### 3. Kunci acuan cerita dan glossary

- Baca glossary chapter sebelumnya terlebih dahulu. Entri yang sudah ditetapkan dipertahankan kecuali ada bukti baru atau alasan kuat; jelaskan perubahan di catatan.
- Tambahkan hanya nama, istilah, tempat, kelompok/organisasi, monster, obat, atau item yang benar-benar muncul dan dapat diidentifikasi.
- Jangan menebak hanja, ejaan Inggris, gender, arti, atau detail `Ext.`. Kosongkan sel atau tulis `—` bila tidak diketahui. Jangan buat baris duplikat; cocokkan entri berdasarkan istilah sumber Korea dan terjemahan yang sudah ada.
- Pertahankan enam kategori dan kolom sebagaimana didefinisikan di `references/glossary.md`.
- Nama perusahaan/merek tidak diterjemahkan; pertahankan romanisasi/nama resminya (misalnya Samsung). Nama grup/kelompok diterjemahkan ke Indonesia; catat padanan kanonisnya di glossary.
- Gunakan `references/approved-sample-ch06.md` sebagai contoh TL yang disetujui untuk gaya dan bentuk output. Glossary chapter 6 di dalamnya hanya boleh dipakai sebagai glossary aktif bila seri yang sedang diterjemahkan dipastikan sama; bila judul/seri belum jelas, tanyakan atau perlakukan hanya sebagai contoh, jangan campurkan entri ke glossary proyek lain.

### 4. Terjemahkan

Terjemahkan setiap unit teks satu kali, sambil mempertahankan urutan baca dan keterkaitan speaker/aksi yang dapat dipastikan. Pertahankan nama/panggilan, tingkat kesopanan, suara khas karakter, dan konsistensi istilah glossary. Pertahankan honorifik Korea `-nim`, `-ssi`, `-unnie`, dan `-hyung` apa adanya. Terjemahkan sapaan kekerabatan seperti `eommonim` dan `abeojinim` ke bahasa Indonesia yang sesuai konteks karena tidak familier bagi banyak pembaca. Pertahankan Konglish sebagai bahasa Inggris yang dimaksud. Jangan menyensor umpatan; terjemahkan setara dengan tingkat kekasaran sumber, jangan diperhalus atau diperkeras. Bila speaker tidak dapat dikenali, jangan menetapkan identitas berdasarkan tebakan; pertahankan dialog tanpa label speaker jika format mengizinkan, atau tandai di catatan.

#### Preferensi diksi dan kata ganti

- Gunakan **"kau"**, bukan **"kamu"**. Jangan ganti `kau` secara mekanis jika bahasa Indonesia yang alami mengizinkan subjek dihilangkan; utamakan dialog yang wajar dan setia pada maksud sumber.
- Gunakan **"apa"**, bukan **"apakah"**. Susun ulang pertanyaan agar terdengar alami tanpa mengubah maksud.
- Gunakan **"saya/Anda"** hanya jika situasi, relasi, dan tingkat formalitas memang menuntutnya. Kapitalisasi `Anda` sesuai ejaan baku; jangan menjadikannya pilihan default.
- Untuk percakapan santai/sehari-hari, pilih **"kalau"**. Gunakan **"jika"** hanya untuk suasana formal, latar/zaman dahulu, atau bawahan yang berbicara kepada atasan.
- Untuk percakapan santai, pilih **"sudah"**. Gunakan **"telah"** hanya pada konteks formal, berita, atau laporan.
- Untuk percakapan santai, pilih **"kenapa"**. Gunakan **"mengapa"** hanya pada situasi formal.
- Terapkan pengecualian berdasarkan konteks karakter dan adegan; jangan membuat tutur formal menjadi santai atau sebaliknya. Saat merevisi agar sesuai preferensi ini, jangan mengubah isi, emosi, atau hubungan antarpenutur.

### 5. Terapkan format Cosmic ID dengan sumber tepercaya

Ikuti definisi dan tata tulis wajib pada `references/cosmic-id.md`. Pedoman resmi yang dilampirkan pengguna mengonfirmasi fungsi seluruh kode, termasuk `TL/N:`.

- Terapkan prefiks sesuai jenis teks; jangan mengganti satu prefiks dengan lainnya berdasarkan tebakan. Gunakan `TL/N:` hanya untuk catatan penerjemah yang memang perlu disampaikan, bukan bagian dari dialog.
- Pedoman resmi mengutamakan formatnya jika berbeda dari variasi tipografi dalam contoh approved chapter 6. Untuk dialog pikiran, pakai `():` sesuai pedoman; pertahankan `(0):` hanya bila proyek/editor secara khusus meminta format bernomor itu.
- Gunakan tanda baca kanonis yang tercantum di referensi dan jangan menambahkan spasi tak konsisten antara kode, titik dua, dan isi. Pertahankan satu unit TL per baris dan tanpa baris kosong di antara dialog.
- Jangan mengarang makna, pasangan kode, label speaker, atau aturan urutan di luar pedoman. Jangan mengasumsikan konvensi platform lain sama.
- Hasil final harus rapat dan konsisten, tanpa baris kosong di antara dialog kecuali pedoman resmi menyatakan sebaliknya.

### 6. Quality control

Periksa seluruh chapter, bukan hanya sampel:

- Cocokkan ledger halaman/panel dengan input; tidak ada yang terlewat atau terduplikasi.
- Cocokkan setiap unit teks sumber relevan dengan tepat satu unit TL, kecuali sumber memang berulang.
- Periksa urutan baca, speaker bila diketahui, nuansa, akurasi, dan keterbacaan bahasa Indonesia.
- Periksa preferensi diksi: `kau` (bukan `kamu`), `apa` (bukan `apakah`), serta pemilihan `saya/Anda`, `kalau/jika`, `sudah/telah`, dan `kenapa/mengapa` sesuai tingkat formalitas.
- Periksa honorifik, Konglish, umpatan, nama perusahaan/merek, nama grup, serta kecocokan prefiks Cosmic ID dengan jenis teks.
- Periksa ulang teks OCR yang meragukan pada gambar/crop asli; tandai yang belum terpecahkan.
- Cocokkan nama dan istilah dengan glossary lama serta ejaan antarhalaman.
- Periksa kode dan tata tulis Cosmic ID terhadap `references/cosmic-id.md`.
- Pastikan watermark dan teks noncerita tidak masuk TL.

## Output standar

Gunakan bagian berikut, dalam urutan ini, kecuali pengguna meminta bentuk lain:

1. `Translation` — hanya hasil TL bersih dalam urutan baca; tanpa baris kosong di antara dialog bila pedoman mengizinkan.
2. `Glossary` — enam tabel sesuai `references/glossary.md`, berisi entri baru/perubahan dan glossary berjalan bila diberikan.
3. `Review Notes` — teks/lokasi yang perlu cek manual, halaman yang tidak tersedia, konflik OCR, keputusan istilah, atau catatan QC. Jangan sisipkan catatan ini ke dalam Translation.

Jika pengguna hanya meminta TL tanpa glossary penuh, berikan TL dan glossary delta (entri baru/perubahan) agar konsistensi tetap terjaga.

## Google Docs

Buat dokumen Google Docs hanya jika konektor/tool Google Docs benar-benar tersedia dan telah diotorisasi pada sesi berjalan. Buat bagian `Translation` dan `Glossary`, gunakan tabel untuk keenam kategori glossary, dan simpan `Review Notes` terpisah. Setelah tindakan, verifikasi hasil melalui tool; jangan mengklaim dokumen berhasil dibuat tanpa konfirmasi sukses. Jika konektor tidak ada, jangan membuat atau mengubah konfigurasi konektor atas inisiatif sendiri: berikan konten siap-tempel atau file lokal yang diminta dan jelaskan keterbatasannya secara singkat.

## Referensi

- `references/cosmic-id.md` — syarat penggunaan kode Cosmic ID dan penanganan ketika pedoman belum tersedia.
- `references/glossary.md` — skema enam tabel dan aturan konsistensi glossary.
- `references/approved-sample-ch06.md` — contoh TL dan glossary yang dinyatakan pengguna sudah disetujui editor; gunakan sesuai batas seri/proyek yang dijelaskan di dalamnya.
- `templates/chapter-output.md` — kerangka hasil chapter.
