# Sistem Daftar Surat — Perbadanan Muzium Melaka (POS PERZIM)

Sistem daftar surat keluar dan cetakan **Senarai Penghantaran Pos (Lampiran A)**. Berfungsi tanpa internet selepas dibuka kali pertama.

## Pasang di PC sebagai aplikasi
1. Buka https://blackburn-code.github.io/Daftar-surat-keluar/ dalam **Google Chrome** atau **Microsoft Edge**.
2. Klik ikon **Install** (⊕) di hujung bar alamat.  
   Edge: menu **⋯ → Apps → Install this site as an app**.
3. Ikon **POS PERZIM** akan muncul di Desktop / Start Menu.

## Kali pertama
- Tetapkan kata laluan dan soalan keselamatan sendiri.
- Untuk pindah data dari fail HTML lama: dalam fail lama, **Tetapan & Sandaran → Muat Turun Sandaran (.json)**, kemudian dalam aplikasi ini **Pulihkan Dari Sandaran**.

## Nota
- Data surat disimpan dalam PC itu sahaja (IndexedDB), **tidak** dihantar ke GitHub. Buat sandaran secara berkala.
- Apabila `index.html` dikemas kini, tukar `VERSI` dalam `sw.js` supaya PC mendapat versi baharu.
- `projek.txt` dan `.github/workflows/build-apk.yml` adalah untuk versi APK Android (tidak berkaitan dengan versi PC ini).
