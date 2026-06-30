# Flazo (Flazoo store) — Demo Static Site

Situs statis demo yang menampilkan nama "Flazo" dan store sebagai "Flazoo store". Cocok untuk di-deploy ke Vercel atau GitHub Pages.

Cara cepat (tinggal ketik) untuk membuat repo lokal dan deploy ke Vercel:

1. Buat folder baru dan inisialisasi git:
   ```bash
   mkdir flazo-site && cd flazo-site
   # lalu copy file index.html dan styles.css ke folder ini (atau jalankan perintah di bawah)
   ```

2. (Opsi cepat: buat file otomatis)
   - Di macOS/Linux:
     ```bash
     # paste seluruh isi index.html ke file
     cat > index.html <<'HTML'
     ... (isi index.html) ...
     HTML

     cat > styles.css <<'CSS'
     ... (isi styles.css) ...
     CSS

     echo "Created site files."
     ```
   - Di Windows PowerShell, gunakan notepad atau editor favorit untuk membuat 2 file tersebut.

3. Commit & deploy:
   ```bash
   git init
   git add -A
   git commit -m "Initial Flazo (Flazoo store) demo site"
   # push ke GitHub (buat repo di GitHub lalu ikuti instruksi push)
   # atau deploy langsung via Vercel CLI:
   npm i -g vercel
   vercel
   ```

4. Sesuaikan:
   - Ganti logo atau favicon di folder public (jika perlu).
   - Edit teks/deskripsi/produk sesuai kebutuhan.

Jika mau, saya bisa:
- Membuat versi Next.js (untuk fitur lebih seperti routing/SSG/SSR),
- Membuat branch & PR ke repo GitHub-mu (kalau kamu beri owner/repo),
- Atau bantu deploy ke Vercel dari repo yang sudah ada.
