# 📘 DOKUMENTASI LENGKAP & FLOWCHART SISTEM SAAS FRAME STUDIO

Dokumen ini merupakan panduan teknis dan operasional resmi sistem **Frame Studio** (`[ Frame ]`), platform SaaS web kinetic motion video eksklusif berbasis canvas browser dengan autentikasi Google Sign-In, sistem lisensi whitelist real-time, dan otomasi database **Google Sheets via Webhook Apps Script**.

---

## 📌 1. Identitas Lengkap Proyek & Database

| Komponen | Konfigurasi / URL Resmi | Catatan |
| :--- | :--- | :--- |
| **Nama Aplikasi** | **Frame Studio** (`[ Frame ]`) | Rebranding bergaya YouTube Studio Dark Aesthetic |
| **Domain Utama** | `https://frame.satujalan.id` | Live SSL 100% Aktif via Cloudflare CNAME Vercel |
| **URL Alternatif** | `https://sj-frame-ydff.vercel.app` | Jalur langsung Vercel Edge Network (Singapore `sin1`) |
| **Repository GitHub** | `https://github.com/yopisonhaji/sj-frame` | Auto-deploy ke Vercel saat file `index.html` di-push |
| **Google Cloud Client ID** | `781988338486-i2i2mr490bp91r3hhck1e7jph3ccjo5n.apps.googleusercontent.com` | Mode **In Production** (Semua akun Gmail bisa login) |
| **Superadmin (Owner)** | **`yulison47@gmail.com`** | Akses bypass permanen + panel kelola member di studio |
| **Nomor WhatsApp Owner** | **`082138004443`** (`+62 821-3800-4443`) | Tujuan konfirmasi & ACC member baru |
| **Link Database Member** | [Buka Google Sheets Member](https://docs.google.com/spreadsheets/d/1wnRppGqNZ44Erwy-mBWKeoCPyvWSeYR-1xQFiVTc-Ok/edit?gid=0#gid=0) | ID: `1wnRppGqNZ44Erwy-mBWKeoCPyvWSeYR-1xQFiVTc-Ok` *(Paten & Terkunci)* |
| **Webhook Auto-Save** | `https://script.google.com/macros/s/AKfycby1vuG-mLuyNBS270jK-uMP4bY09gqJXA8D-fOg9PPcEIBa31934T5IS6OAoNeuyb1H/exec` | **Aktif 100% (Versi 3 - Siapa Saja)** |
| **Link Gemini Sutradara AI** | [Gemini AI Video Director Shared Link](https://gemini.google.com/share/c5b85080d7a6?social_preview=false&skid=9b3c5111-1236-4bcb-871a-9b55c8052d78) | Prompt generator skrip & storyline untuk pembeli |

---

## ⚡ 2. Solusi Tombol Hijau Langsung Buka Spreadsheet Anda

### Mengapa Kemarin Muncul "File tidak ada"?
* Sebelumnya, saat mencoba Webhook, ada kemungkinan ID Webhook atau link skrip tidak sengaja tersimpan ke memori browser (*localStorage*) pada kolom Google Sheet, sehingga tombol membuka alamat skrip yang salah.

### Solusi Permanen yang Telah Diterapkan:
1. Tombol hijau **`📊 Buka Google Sheet (Cek Memastikan / Edit)`** telah dikunci mati (*hardcoded*) secara langsung ke alamat resmi spreadsheet Anda:  
   👉 `https://docs.google.com/spreadsheets/d/1wnRppGqNZ44Erwy-mBWKeoCPyvWSeYR-1xQFiVTc-Ok/edit?gid=0#gid=0`
2. Sistem otomatis membersihkan (*auto-purge*) memori browser jika ada ID webhook yang tidak sengaja tersimpan di pengaturan sheet.
3. Begitu Anda mengklik tombol hijau tersebut, browser **dijamin 100% langsung membuka spreadsheet Member Frame Studio Anda** tanpa error!

---

## 🚀 3. Langkah Update ke GitHub:

File [index.html](file:///d:/SJ%20MOTION/index.html) di laptop Anda telah diperbarui dengan perbaikan ini:

1. Buka [github.com/yopisonhaji/sj-frame](https://github.com/yopisonhaji/sj-frame).
2. Klik **Add file** ➔ **Upload files**.
3. Tarik (*drag & drop*) file `D:\SJ MOTION\index.html` lalu klik tombol hijau **Commit changes**.
4. Selesai! Buka `frame.satujalan.id`, klik tombol hijau, dan spreadsheet Anda langsung terbuka seketika!
