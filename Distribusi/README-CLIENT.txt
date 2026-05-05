==============================================================
  Telegram Blaster By VibeTool.Club
  Panduan Singkat untuk Client (sekali baca, langsung pakai)
==============================================================

CARA PAKAI (3 LANGKAH):

  1. Klik kanan file ZIP yang Anda terima >> Extract All...
     (atau pakai 7-Zip / WinRAR)

  2. Buka folder hasil extract.

  3. Double-click file:  TelegramBlaster.exe

     Aplikasi akan langsung terbuka. Tidak perlu install
     Python, library, atau program tambahan apa pun.


--------------------------------------------------------------
  LOGIN PERTAMA KALI
--------------------------------------------------------------

Di tab "Login":
  - Masukkan nomor Telegram Anda (format: +6281234567890)
  - Buat "Encryption Password" (password ini melindungi
    session Anda secara lokal — INGAT BAIK-BAIK, tidak
    bisa di-recover kalau lupa)
  - Klik "Send OTP"
  - Buka Telegram di HP, copy 5-digit kode yang masuk
  - Tempel ke kolom "OTP Code", lalu klik "Complete Login"

  Atau pakai QR Login:
  - Klik "Start QR Login"
  - Buka Telegram di HP >> Settings >> Devices >> Link
    Desktop Device
  - Scan QR code yang muncul di aplikasi


--------------------------------------------------------------
  TROUBLESHOOTING
--------------------------------------------------------------

* Windows menampilkan "SmartScreen / Defender" warning?
  Klik "More info" >> "Run anyway". Aplikasi tidak signed
  digital signature, tapi aman digunakan.

* Aplikasi lambat dibuka pertama kali?
  Normal. Windows sedang scan file. Run kedua dst akan
  jauh lebih cepat.

* Antivirus block file?
  Tambahkan folder ini ke whitelist/exception antivirus.
  False positive umum untuk aplikasi Python yang dibundle.

* Error "Tidak bisa konek ke Telegram"?
  Pastikan koneksi internet aktif dan tidak diblokir
  firewall / kantor / kampus.


--------------------------------------------------------------
  CATATAN PENTING
--------------------------------------------------------------

- Data session disimpan terenkripsi di folder "sessions"
  di samping TelegramBlaster.exe. Jangan pindahkan file ini
  ke folder lain — pindahkan SELURUH folder kalau mau pindah.

- Folder "members.csv" akan terisi otomatis saat Anda
  scrape group. Backup folder "backups" otomatis dibuat
  saat Anda klik "Hapus Hasil Scrape".

- Patuhi Telegram Terms of Service & hukum lokal Anda.
  Aplikasi ini hanya untuk akun/grup yang Anda kelola
  secara legal.


--------------------------------------------------------------
  Support: VibeTool.Club
==============================================================
