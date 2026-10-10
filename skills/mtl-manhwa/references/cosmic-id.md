# Cosmic ID — format lintas bahasa dan aturan gaya

Acuan format: dokumen **Cosmic ID - Korean Translator (KTL)** yang dilampirkan pengguna. Kode Cosmic ID berlaku sebagai format output untuk pekerjaan yang memakai gaya Cosmic ID. Aturan bahasa Korea pada dokumen itu hanya berlaku untuk sumber Korea; jangan otomatis menerapkannya ke Jepang, Inggris, atau Mandarin. Lihat `source-languages.md` untuk aturan bahasa lainnya. Contoh TL chapter 6 di `approved-sample-ch06.md` tetap menjadi contoh gaya yang disetujui.

## Kode wajib

| Kode | Fungsi | Bentuk penggunaan |
|---|---|---|
| `“”:` | Dialog di dalam bubble | `“”: [teks dialog bubble]` |
| `//:` | Dialog dalam bubble yang tersambung dengan bubble sebelumnya | `//: [lanjutan dialog]` |
| `[]:` | Narasi dalam bubble box | `[]: [teks narasi]` |
| `():` | Isi pikiran yang tidak diucapkan | `(): [teks pikiran]` |
| `ST:` | Small text yang diucapkan karakter dan side text | `ST: [teks kecil/samping sesuai konteks]` |
| `OT:` | Teks di luar panel | `OT: [teks luar panel]` |
| `SFX:` | Sound effect/efek suara | `SFX: [padanan efek suara]` |
| `{}:` | Miscellaneous text, misalnya tulisan pada gedung atau buku | `{}: [teks yang terlihat]` |
| `TL/N:` | Catatan yang ingin disampaikan penerjemah | `TL/N: [catatan penerjemah]` |

Teks dalam kurung siku pada contoh di atas adalah placeholder, bukan bagian yang harus disalin. Gunakan `TL/N:` hanya bila catatan memang dibutuhkan; jangan masukkan catatan penerjemah ke dialog bersih.

## Aturan gaya lintas bahasa

- Jangan menyensor umpatan. Pertahankan tingkat kekasaran yang sepadan dengan sumber; jangan melembutkan atau memperkeras tanpa alasan konteks.
- Nama perusahaan/merek tidak diterjemahkan; pertahankan ejaan resmi/romanisasinya, misalnya Samsung.
- Gunakan padanan resmi/terlokalisasi untuk nama grup/kelompok dan catat bentuk kanonisnya di glossary. Pilih terjemahan Indonesia bila memang lazim, tetapi jangan mengganti nama resmi yang sudah mapan dengan terjemahan literal. Contoh pedoman: `소녀시대` → `Girl's Generation`.

## Khusus sumber Korea (KO)

- Pertahankan honorifik Korea `-nim`, `-ssi`, `-unnie`, dan `-hyung` tanpa diterjemahkan.
- Terjemahkan sapaan kekerabatan tertentu seperti `eommonim` dan `abeojinim` ke padanan Indonesia yang sesuai konteks karena belum familier bagi banyak pembaca.
- Pertahankan Konglish sebagai bahasa Inggris yang dimaksud. Aturan Konglish ini hanya berlaku untuk bahasa sumber Korea.

## Untuk sumber Jepang (JA), Inggris (EN), dan Mandarin/Chinese (ZH)

Ikuti aturan honorifik, sapaan, idiom, register, dan romanisasi yang sesuai pada `source-languages.md`. Jangan memakai honorifik Korea untuk bahasa lain atau menganggap nama pada Kanji/Hanzi punya bacaan yang pasti tanpa acuan.

## Tata tulis dan cakupan

- Pilih prefiks berdasarkan fungsi visual/teks pada gambar, bukan dugaan berdasarkan isi kalimat saja.
- Ikuti bentuk kode pada tabel: kode diikuti titik dua dan teks, konsisten sebagai `KODE: teks`. Hindari variasi spasi yang muncul pada beberapa contoh lampiran.
- Setiap unit TL berada pada baris tersendiri. Jangan sisipkan baris kosong di antara unit TL, kecuali editor memberi aturan khusus.
- Jangan menerjemahkan label kode atau menghilangkannya dari hasil final.
- Untuk SFX, gunakan padanan Indonesia yang natural dan ekspresif bila maknanya jelas. Jika tidak jelas, pertahankan deskripsi terdekat dan tandai untuk cek; jangan mengarang konteks.
- Gunakan `{}:` untuk teks miscellaneous yang merupakan bagian dunia cerita, misalnya tulisan pada gedung/buku/benda; `[]:` untuk narasi dalam bubble box; `OT:` untuk teks di luar panel. Jangan masukkan watermark, logo, kredit scanlation, username, URL, promosi, atau nomor halaman noncerita.

## Rekonsiliasi dengan contoh chapter 6

Contoh approved chapter 6 menggunakan variasi seperti `"":` alih-alih `“”:` dan `(0):` alih-alih `():`. Untuk pekerjaan baru, gunakan bentuk kanonis pada tabel (`“”:` dan `():`). Pertahankan variasi bernomor atau tanda petik ASCII hanya jika editor secara eksplisit mengonfirmasi bahwa itu standar khusus seri tersebut. Contoh chapter 6 tetap menjadi acuan diksi dan glossary untuk seri yang sama.

## Pemeriksaan format

Sebelum menyerahkan hasil, pastikan setiap dialog bubble memakai `“”:` atau `//:` sesuai hubungan bubble; narasi, pikiran, small/side text, outer text, SFX, miscellaneous, dan catatan penerjemah memakai kode yang sesuai; tidak ada baris kosong yang tidak diizinkan; serta tidak ada label noncerita yang ikut diterjemahkan. Pastikan aturan honorifik, nama, romanisasi, umpatan, dan register sesuai bahasa sumber.
