# Portofolio & CV — Anindya Putri Maharani

Website statis (tanpa build). Struktur:

```
portfolio/
├── index.html      # seluruh halaman (HTML, CSS, JS)
├── assets/foto.jpg # foto profil
├── vercel.json     # konfigurasi Vercel
└── README.md
```

## Deploy ke Vercel
1. Push folder ini ke GitHub, lalu di vercel.com pilih **Add New → Project** dan impor repo.
2. Framework Preset: **Other**. Kosongkan Build Command dan Output Directory, lalu **Deploy**.
3. Atau lewat terminal: `npx vercel --prod` di dalam folder ini.

## Yang perlu diganti
Nama, email, LinkedIn, GitHub, pengalaman, dan array `PROJECTS` di bagian `<script>` pada `index.html`. Ganti `assets/foto.jpg` dengan foto Anda (nama file sama).
