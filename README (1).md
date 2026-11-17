# LabStock – Inventory Laboratorium

Aplikasi HP (PWA) untuk mendata stok lab, barang masuk, pemakaian hari ini, vendor, dan monitor stok. Bisa di-install ke layar utama dan jalan offline.

## Upload ke GitHub (dari HP, tanpa folder)
1. Buat repository baru, set **Public**.
2. *Add file → Upload files*, pilih **semua file** (index.html, app.js, style.css, sw.js, manifest.webmanifest, semua .png, logo.svg, README.md), lalu *Commit changes*.
3. *Settings → Pages → Source: Deploy from a branch → Branch: main, folder: / (root) → Save*.
4. Tunggu 1–2 menit, buka `https://USERNAME.github.io/NAMA-REPO/`.
5. Android Chrome: menu ⋮ → Instal aplikasi. iPhone Safari: Bagikan → Tambah ke Layar Utama.

## Catatan
- Data tersimpan di HP (tanpa server). Lakukan Backup JSON lewat menu ☰ secara berkala.
- Setelah mengubah file, naikkan versi `CACHE` di `sw.js` (mis. `labstock-v2`).
