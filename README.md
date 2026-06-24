# EIC7 Portal — PLTU Unit 7

Landing page Section Electric, Instrument & Control Unit 7 beserta kalender call out standby 2026.

## Isi folder
- `index.html` — halaman utama (portal PM, profil, anggota tim, ringkasan call out)
- `callout.html` — kalender call out interaktif (Tahun / Bulan / Minggu)
- `support.js` — runtime tampilan (wajib disertakan)
- `eic7-callout-data.js` — data jadwal standby 2026

## Cara publish ke GitHub Pages (gratis, online untuk semua)
1. Login GitHub → klik **New repository**. Beri nama, mis. `eic7-portal`, pilih **Public**, klik **Create repository**.
2. Klik **uploading an existing file**, lalu seret SEMUA file di folder `site/` ini (index.html, callout.html, support.js, eic7-callout-data.js). Klik **Commit changes**.
3. Buka tab **Settings → Pages**. Pada *Source* pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, klik **Save**.
4. Tunggu ~1 menit. Situs aktif di: `https://USERNAME.github.io/eic7-portal/` (ganti USERNAME dengan akun Anda).

## Cara update ke depan
- Buka file di repo → **Edit** (ikon pensil) → commit. Perubahan langsung tayang setelah ~1 menit.
- Atau minta perubahan desain dilakukan ulang, lalu upload ulang file yang berubah.

## Catatan
- Link Portal PM Electric, PM I&C, dan Material List mengarah ke aplikasi eksternal masing-masing tim (buka di tab baru).
- File desain sumber (`*.dc.html`) disimpan terpisah untuk pengembangan; yang dipublish cukup isi folder `site/`.
