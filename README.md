# Portfolio Anisa Fitriani

Portfolio website siap deploy!

## 📁 Struktur File
```
portfolio/
├── index.html          (file utama)
├── anisa.jpg          (foto profil - SUDAH DIGANTI)
├── assets/
│   ├── index-BeZ-5cEl.js     (JavaScript app)
│   └── index-BiIlItBm.css    (Styling)
└── README.md
```

## 🚀 Cara Upload ke GitHub

### Via GitHub Web:
1. Buka https://github.com/new
2. Nama repository: `portfolio` (atau terserah)
3. Set **Public**
4. Klik **Create repository**
5. Klik **"uploading an existing file"**
6. **Drag semua file ini** (index.html, anisa.jpg, folder assets/, README.md)
7. Commit changes

### Atau Via Git Command:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/portfolio.git
git push -u origin main
```

## 🌐 Deploy ke Vercel

1. Login ke https://vercel.com
2. Klik "Add New" → "Project"
3. "Import Git Repository"
4. Pilih repo GitHub yang barusan dibuat
5. **Framework Preset:** Pilih "Other" atau "Vite"
6. **Root Directory:** Kosongkan atau set ke `/`
7. **Build Command:** Kosongkan
8. **Output Directory:** Kosongkan
9. Klik **Deploy**

## 🌐 Deploy ke GitHub Pages

1. Di repo GitHub, buka **Settings**
2. Scroll ke **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** → folder: **/ (root)**
5. Save
6. Tunggu 1-2 menit
7. Website live di: `https://USERNAME.github.io/portfolio/`

## ⚠️ Troubleshooting

**404 Not Found di Vercel?**
- Pastikan semua file (index.html, assets/, anisa.jpg) ada di root folder
- Jangan upload file ZIP, tapi isi folder-nya langsung
- Root directory harus `/` bukan `/dist`

**Blank page / konten tidak muncul?**
- Buka Developer Tools (F12)
- Cek Console untuk error
- Pastikan file JS dan CSS di folder `assets/` keload dengan benar

**Foto tidak muncul?**
- Pastikan file `anisa.jpg` ada di root folder (sama level dengan index.html)
- File size: ~252 KB

## 📝 Notes
- Ini adalah **production build** dari React app
- Tidak perlu install npm atau build lagi
- Tinggal upload dan deploy langsung
- Foto sudah diganti dengan foto yang baru (graduation photo)
