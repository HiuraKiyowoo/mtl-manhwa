# Cosmic ID — pedoman format dan gaya

Acuan: dokumen **Cosmic ID - Korean Translator (KTL)** yang dilampirkan pengguna. Pedoman ini menjadi sumber utama untuk fungsi kode dan tata tulis. Contoh TL chapter 6 di `approved-sample-ch06.md` tetap menjadi acuan gaya yang sudah disetujui, tetapi bila formatnya berbeda, ikuti pedoman ini kecuali editor memberi instruksi khusus untuk seri tersebut.

## Kode wajib

| Kode | Fungsi | Bentuk penggunaan |
|---|---|---|
| `“”:` | Dialog yang berada di dalam bubble | `“”: [teks dialog bubble]` |
| `//:` | Dialog di dalam bubble yang tersambung dengan bubble sebelumnya | `//: [lanjutan dialog]` |
| `[]:` | Narasi yang berada di bubble box | `[]: [teks narasi]` |
| `():` | Isi pikiran yang tidak diucapkan | `(): [teks pikiran]` |
| `ST:` | Small text yang diucapkan karakter dan side text | `ST: [teks kecil/samping sesuai konteks]` |
| `OT:` | Teks di luar panel | `OT: [teks luar panel]` |
| `SFX:` | Sound effect/efek suara | `SFX: [padanan efek suara]` |
| `{}:` | Miscellaneous text, misalnya tulisan pada gedung atau buku | `{}: [teks yang terlihat]` |
| `TL/N:` | Catatan yang ingin disampaikan penerjemah | `TL/N: [catatan penerjemah]` |

Contoh label di atas menunjukkan bentuk kode dan tempat isi; teks dalam kurung siku pada kolom contoh adalah placeholder, bukan bagian yang harus disalin. Gunakan `TL/N:` hanya bila catatan memang dibutuhkan. Jangan masukkan catatan penerjemah ke dialog bersih.

## Aturan gaya terjemahan

1. **Honorifik Korea:** pertahankan `-nim`, `-ssi`, `-unnie`, dan `-hyung` tanpa diterjemahkan.
2. **Sapaan kekerabatan tertentu:** terjemahkan `eommonim`, `abeojinim`, dan sapaan sejenis yang tidak familier bagi pembaca ke padanan Indonesia yang sesuai konteks. Jangan memaksakan romanisasi jika pembaca kemungkinan tidak memahaminya.
3. **Konglish:** pertahankan sebagai bahasa Inggris yang dimaksud.
4. **Umpatan:** jangan disensor. Pertahankan tingkat kekasaran yang sepadan dengan sumber; jangan melembutkan atau memperkeras tanpa alasan konteks.
5. **Nama perusahaan/merek:** jangan diterjemahkan; pertahankan romanisasi/nama resminya, misalnya Samsung.
6. **Nama grup/kelompok:** terjemahkan ke bahasa Indonesia. Gunakan padanan kanonis dalam glossary; contoh yang diberikan pedoman: `소녀시대` → `Girl's Generation`.

## Tata tulis dan konsistensi

- Pakai prefiks berdasarkan fungsi visual/teks di gambar, bukan dugaan berdasarkan isi kalimat saja.
- Ikuti bentuk kode tepat seperti tabel: kode diikuti titik dua dan teks. Hindari variasi spasi yang tampak pada beberapa contoh lampiran; keluaran dinormalkan menjadi `KODE: teks`.
- Setiap unit TL berada pada baris tersendiri. Jangan sisipkan baris kosong di antara unit TL, kecuali editor memberikan aturan khusus.
- Jangan menerjemahkan label kode atau menghilangkannya dari hasil final.
- Untuk sound effect, gunakan padanan Indonesia yang natural dan ekspresif bila dapat dipastikan. Jika efeknya tidak jelas, pertahankan deskripsi yang paling dekat tanpa mengarang konteks.
- Teks pada gedung, buku, layar, atau benda yang menjadi bagian narasi visual dapat memakai `{}:`; teks narasi dalam bubble box memakai `[]:`; teks di luar panel memakai `OT:`. Bedakan dari watermark, URL, kredit scanlation, username, promosi, atau nomor halaman noncerita yang harus diabaikan.

## Rekonsiliasi dengan contoh chapter 6

Contoh approved chapter 6 menggunakan beberapa variasi, misalnya `"":` alih-alih `“”:` dan `(0):` alih-alih `():`. Untuk pekerjaan baru, gunakan bentuk kanonis pedoman terbaru (`“”:` dan `():`). Pertahankan variasi bernomor atau tanda petik ASCII hanya jika editor secara eksplisit mengonfirmasi bahwa itu standar khusus seri tersebut. Contoh chapter 6 tetap berguna sebagai acuan diksi dan glossary untuk seri yang sama.

## Pemeriksaan format

Sebelum menyerahkan hasil:

- pastikan setiap dialog bubble memakai `“”:` atau `//:` sesuai hubungan bubble;
- pastikan narasi bubble box, pikiran, teks kecil/samping, teks luar panel, SFX, misc, dan catatan TL/N masing-masing memakai kode yang sesuai;
- pastikan format konsisten, tidak ada baris kosong yang tidak diizinkan, dan tidak ada label noncerita yang ikut diterjemahkan;
- pastikan istilah, nama merek, nama grup, honorifik, Konglish, dan umpatan mengikuti aturan di atas.
