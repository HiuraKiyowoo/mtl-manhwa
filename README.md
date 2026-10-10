# MTL Manhwa

Skill untuk menerjemahkan manhwa/webtoon Korea ke bahasa Indonesia dengan format Cosmic ID, menjaga konsistensi glossary, dan menandai bagian OCR yang perlu ditinjau.

## Pasang dengan `npx skills`

Repositori ini privat. Pastikan GitHub CLI sudah terautentikasi pada akun yang memiliki akses ke repo, lalu jalankan:

```bash
npx skills add HiuraKiyowoo/mtl-manhwa --skill mtl-manhwa --global --copy
```

Untuk melihat skill yang tersedia:

```bash
npx skills add HiuraKiyowoo/mtl-manhwa --list
```

Untuk memperbarui instalasi:

```bash
npx skills update mtl-manhwa
```

`npx skills` menggunakan kredensial Git/GitHub CLI yang telah dikonfigurasi pada mesin pengguna untuk mengakses repo privat; jangan menempelkan token ke command atau file.

## Isi skill

```text
skills/mtl-manhwa/
├── SKILL.md
├── references/
│   ├── approved-sample-ch06.md
│   ├── cosmic-id.md
│   └── glossary.md
└── templates/
    └── chapter-output.md
```
