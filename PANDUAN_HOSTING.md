# 🌐 Panduan Upload ke Hosting

Panduan lengkap untuk meng-upload website PTA Palangka Raya ke berbagai platform hosting.

## 📊 Hosting Gratis Terbaik

### 1. **GitHub Pages** (Rekomendasi)
**Keunggulan**: Gratis selamanya, domain custom, SSL otomatis

**Langkah-langkah**:
1. Buat akun di [github.com](https://github.com)
2. Buat repository baru dengan nama `pta-palangkaraya-website`
3. Upload semua file ke repository
4. Ke Settings → Pages → Source: Deploy from branch
5. Pilih branch `main`, folder `/ (root)`
6. Website akan tersedia di: `username.github.io/pta-palangkaraya-website`

### 2. **Netlify**
**Keunggulan**: Deploy drag & drop, domain custom gratis

**Langkah-langkah**:
1. Buka [netlify.com](https://netlify.com)
2. Drag & drop folder `website_pta_palangkaraya_ready` ke area upload
3. Website langsung live dengan URL acak
4. Bisa ganti domain custom di settings

### 3. **Vercel**
**Keunggulan**: Sangat cepat, optimasi otomatis

**Langkah-langkah**:
1. Buka [vercel.com](https://vercel.com)
2. Import dari GitHub atau upload langsung
3. Deploy otomatis
4. Domain custom tersedia

## 🏢 Hosting Berbayar

### **cPanel Hosting** (Hosting Indonesia)
**Untuk**: Domain sendiri (misal: pta-palangkaraya.id)

**Langkah-langkah**:
1. Login ke cPanel hosting Anda
2. Buka File Manager
3. Masuk ke folder `public_html`
4. Upload file `website_pta_palangkaraya_ready.zip`
5. Extract zip file
6. Pindahkan isi folder ke `public_html`
7. Website tersedia di domain Anda

## 🔧 Konfigurasi Domain Custom

### Untuk GitHub Pages:
1. Beli domain di registrar (Niagahoster, Cloudflare, dll)
2. Tambah file `CNAME` berisi domain Anda
3. Setting DNS di registrar:
   - Type: CNAME
   - Name: www
   - Value: username.github.io

### Untuk Netlify:
1. Beli domain
2. Di Netlify: Site Settings → Domain Management
3. Add custom domain
4. Update nameserver di registrar ke Netlify

## 📱 Testing Website

Setelah upload, pastikan test:
- ✅ **Desktop**: Chrome, Firefox, Edge, Safari
- ✅ **Mobile**: Android & iOS
- ✅ **Navigasi**: Sidebar menu berfungsi
- ✅ **Gambar**: Semua screenshot tampil
- ✅ **Responsive**: Layout adaptif di berbagai ukuran

## ⚡ Tips Optimasi

### **Untuk Performa Terbaik**:
1. **Gunakan CDN** (Cloudflare gratis)
2. **Aktifkan Gzip compression**
3. **Setup SSL certificate** (biasanya otomatis)
4. **Monitor uptime** dengan tools seperti UptimeRobot

### **Untuk SEO** (jika diperlukan):
1. Tambahkan meta description di `index.html`
2. Setup Google Analytics
3. Submit ke Google Search Console

## 🛡️ Keamanan

- **Backup rutin**: Simpan file di cloud
- **Update berkala**: Monitor hosting provider
- **SSL wajib**: Pastikan https:// aktif
- **Access log**: Monitor traffic dan akses

## 📞 Support Hosting

**GitHub Pages**: [docs.github.com/pages](https://docs.github.com/pages)
**Netlify**: [docs.netlify.com](https://docs.netlify.com)
**Vercel**: [vercel.com/docs](https://vercel.com/docs)

## 🎯 Rekomendasi Final

**Untuk penggunaan resmi institusi**:
1. **Domain sendiri**: `pta-palangkaraya.go.id` atau serupa
2. **Hosting Indonesia**: Untuk compliance dan kecepatan
3. **SSL Certificate**: Wajib untuk keamanan
4. **Backup berkala**: Hindari kehilangan data

**Untuk testing/demo cepat**:
1. **Netlify**: Paling mudah dan cepat
2. **GitHub Pages**: Paling stabil dan gratis
3. **Vercel**: Paling cepat loading

---

💡 **Tips**: Mulai dengan hosting gratis untuk testing, kemudian upgrade ke domain sendiri untuk penggunaan resmi.
