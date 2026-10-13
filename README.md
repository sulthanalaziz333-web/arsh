# Website Arsh Production

Website statis (HTML + CSS + JS) yang siap dipasang di GitHub Pages.

## Struktur

```
index.html          ← seluruh website
assets/
  logo.png          ← logo Arsh Production (sudah termasuk)
  work/             ← (opsional) thumbnail portofolio
```

## Langkah wajib sebelum publish

1. **Logo**: sudah terpasang di `assets/logo.png` (latar transparan, otomatis tampil putih di tema gelap). Ganti file ini jika ingin memakai versi logo lain.
2. **WhatsApp**: buka `index.html`, cari `CONFIG` di bagian `<script>`, ganti `whatsapp: "6280000000000"` dengan nomor Anda (format 62xxxxxxxxxx, tanpa + dan spasi).
3. **Harga**: harga di `packages` hanyalah contoh, sesuaikan dengan harga Arsh Production.
4. **Portofolio**: isi `img` dengan path gambar (mis. `assets/work/wedding-1.jpg`) dan `link` dengan URL video/postingan Instagram atau YouTube.
5. **Instagram, TikTok, YouTube, email**: isi di bagian atas `CONFIG`.
6. **Testimoni**: ganti dengan testimoni klien asli. Statistik di hero (150+ proyek, 80+ klien) juga contoh, ubah di bagian `data-count` pada `index.html`.

## Cara publish di GitHub Pages

1. Buat repository baru di GitHub, mis. `arsh-production` (public).
2. Upload semua isi folder ini (`index.html`, folder `assets`).
3. Buka **Settings → Pages**, pada *Source* pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu Save.
4. Tunggu 1–2 menit. Alamat situs: `https://username.github.io/arsh-production/`

Tips: jika repository dinamai `username.github.io`, alamat situs menjadi `https://username.github.io/` tanpa nama repo.
