# 🎂 Kejutan Ulang Tahun

Halaman kejutan ulang tahun interaktif (mobile-first). Tanpa build, tanpa framework: cukup file statis.

## Isi folder
```
index.html     -> halaman utama (jangan diganti namanya)
config.js      -> ubah nama, pesan, hadiah, tanggal jadian di sini
vercel.json    -> setelan Vercel
assets/
  favicon.svg  -> ikon tab
  video.mp4    -> (taruh sendiri) video background
```

## 1. Isi data
Buka `config.js`, ubah `nama`, `dari`, `sejak`, dan `pesan`. Tidak perlu menyentuh `index.html`.

## 2. Video background (opsional)
Taruh video kalian di `assets/video.mp4` (MP4 H.264, vertikal, 20-40 detik, di bawah 25 MB).
Tanpa video, latar otomatis jadi gradasi aurora.

## 3. Upload ke GitHub
1. Buka github.com, klik **New repository**, beri nama (misal `ultah`), klik **Create repository**.
2. Klik **uploading an existing file**.
3. Drag semua isi folder ini (`index.html`, `config.js`, `vercel.json`, folder `assets`) ke halaman itu.
4. Klik **Commit changes**.

## 4. Deploy ke Vercel
1. Buka vercel.com, login pakai akun GitHub.
2. **Add New → Project**, pilih repo tadi, klik **Import**.
3. **Framework Preset: Other**. Biarkan sisanya default, klik **Deploy**.
4. Selesai. Link `https://nama-project.vercel.app` siap dikirim.

Setiap kali kamu edit file di GitHub (misal `config.js`), Vercel otomatis deploy ulang.

## Catatan
- Fitur tiup lilin pakai mic butuh HTTPS. Di Vercel otomatis aman. Kalau ditolak, ada tombol "Ketuk saja".
- Bisa override lewat link: `?nama=Putri&dari=Budi&sejak=2024-02-14`.
- Cek video dari galeri tanpa upload: tambahkan `?edit=1` lalu tekan tombol 🎞️ di pojok kanan atas.
