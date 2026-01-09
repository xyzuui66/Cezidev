# Web Load Tester & Defense Simulator 🚀

Alat sederhana berbasis HTML & JavaScript untuk menguji ketahanan server web terhadap lonjakan trafik (Load Testing). Dibuat khusus untuk keperluan edukasi, riset keamanan, dan pengujian infrastruktur pribadi langsung melalui browser.

## ⚠️ Disclaimer (Penting!)
**Penyalahgunaan alat ini untuk menyerang infrastruktur milik orang lain tanpa izin tertulis adalah tindakan ILLEGAL.** Penulis tidak bertanggung jawab atas segala kerusakan, pemblokiran IP, atau masalah hukum yang timbul akibat penggunaan alat ini. Gunakan hanya pada server/website milik sendiri untuk menguji sistem pertahanan seperti Rate Limiting atau WAF.

---

## 🛠️ Fitur Utama
* **Browser Based:** Tidak perlu instalasi, bisa dijalankan langsung dari HP atau Laptop.
* **Dual Control:** Dilengkapi tombol **START** dan **STOP** yang responsif.
* **Cache Bypass:** Menggunakan teknik *random parameter* untuk memastikan setiap request diproses oleh server, bukan diambil dari cache.
* **Thread Control:** Jumlah permintaan serentak (concurrency) dapat diatur sesuai kemampuan perangkat.

---

## 🚀 Cara Penggunaan melalui GitHub Pages
1. Upload file `index.html` ke repository ini.
2. Aktifkan **GitHub Pages** di menu *Settings > Pages*.
3. Buka link GitHub Pages yang muncul.
4. Masukkan URL target (Contoh: `https://website-kamu.com`).
5. Klik **START** untuk memulai simulasi dan **STOP** untuk menyudahi.

---

## 🛡️ Analisis Hasil Pengujian
Saat simulasi berjalan, perhatikan respon dari website target:
* **Lancar:** Pertahanan server sangat kuat atau trafik belum cukup besar.
* **Slowdown:** Website mulai lambat diakses (tanda resource server hampir penuh).
* **HTTP 429:** Server kamu berhasil memblokir serangan dengan *Rate Limiting*.
* **HTTP 502/504:** Server tumbang atau kehabisan sumber daya (Down).

---

## 📝 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

