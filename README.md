# Landing Page: Paket Aktivasi & Setup Awal Sistem Informasi Manajemen Rumah Kos

Landing page kreatif, modern, responsif, dan berkonversi tinggi untuk penawaran:
**Paket Aktivasi & Setup Awal Sistem Informasi Manajemen Rumah Kos — Rp99.000 (Sekali Beli)**

---

## 🚀 Fitur Unggulan & Elemen Kreatif

1. **Desain Visual Modern & Clean (PropTech Aesthetic)**
   - Menggunakan kombinasi warna emerald green, navy slate, dan aksen warm amber yang memberi kesan terpercaya, profesional, dan menguntungkan.
   - Tipografi modern menggunakan *Plus Jakarta Sans*.
   - Responsive total (Mobile, Tablet, Desktop) dengan *Tailwind CSS*.

2. **Simulasi / Demo Antarmuka Interaktif (Owner vs Tenant Preview)**
   - Tab 1: **Tampilan Pengelola (Owner Kos)** — Simulasi real-time denah kamar (Kamar 101, 102, 103, 204 Jatuh Tempo, 205 Kosong), ringkasan okupansi, tagihan jatuh tempo, dan tombol simulasi reminder invoice via WhatsApp.
   - Tab 2: **Portal Mandiri (Anak Kos)** — Menampilkan status sewa lunas, kontrak digital, dan form tiket pengaduan kerusakan fasilitas tanpa mengganggu chat pribadi pengelola.

3. **Kalkulator Efisiensi & Hemat Waktu Interaktif**
   - Slider interaktif (3 s/d 50 kamar) untuk menghitung berapa jam waktu dan estimasi nilai rupiah yang dihemat setiap bulan dengan sistem digital.

4. **Struktur Copywriting Berorientasi Konversi Tinggi (AIDA + PAS Framework)**
   - **Hook & Hero Section**: Problem-solution bridge & penawaran paket Rp99.000.
   - **Realita / Pain Points Juragan Kos**: Komparasi visual antara *Cara Lama Manual* (buku catatan hilang, chat WA tenggelam) vs *Solusi Paket Setup Rp99.000*.
   - **4 Fondasi Utama**: Akun Admin Terisolasi, Input Data Awal Kamar & Penghuni, Kontrak Digital & Alur Penagihan, serta Akses Mandiri Penghuni.
   - **Alasan Memilih**: Highlight "tidak perlu habiskan akhir pekan utak-atik sistem".
   - **3 Langkah Praktis**: Cara kerja dari transfer sampai akun aktif dalam 24 jam.
   - **Testimoni Sosial**: Cerita sukses pemilik kos di Jogja, Malang, dan Bandung.
   - **Pricing Card Berdampak Tinggi**: Penawaran promo coret (Rp350.000 -> Rp99.000) + Bonus Template SOP Kos Digital.
   - **Pusat FAQ**: Menjawab keraguan calon pembeli yang gaptek atau khawatir biaya tersembunyi.
   - **Sticky Bottom Action Bar**: Tombol cepat untuk konversi dari posisi scroll manapun.

5. **WhatsApp Order Generator Modal**
   - Pengunjung mengisi nama kos, nama pemilik, jumlah kamar, kota, dan catatan tambahan.
   - Sistem langsung merangkai pesan pesanan resmi dan membuka aplikasi WhatsApp (`wa.me`) secara otomatis.

---

## 🛠️ Cara Menjalankan & Membuka

Halaman ini dibuat mandiri (*standalone single-page*) tanpa perlu instalasi `npm` atau build tool rumit:

1. **Buka Langsung:**
   - Cukup klik dua kali file `index.html` untuk langsung melihatnya di browser (Google Chrome, Microsoft Edge, Safari, Firefox).
2. **Deploy Gratis (Opsional):**
   - Unggah folder ini ke **Netlify Drop**, **Vercel**, atau **GitHub Pages** untuk langsung live online dengan domain Anda sendiri.

---

## 📱 Mengubah Nomor WhatsApp Admin

Buka file `index.html`, scroll ke bagian bawah (sekitar baris 1492), lalu ganti nomor berikut dengan nomor WhatsApp bisnis Anda:

```javascript
// Ganti nomor WhatsApp admin bila dibutuhkan (gunakan kode negara 62 untuk Indonesia tanpa tanda +)
const waNumber = "6281234567890";
```
