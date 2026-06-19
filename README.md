Go.In

## Deskripsi Aplikasi

Go.In adalah platform yang memungkinkan pengguna untuk:
- Melihat daftar hotel dan kamar
- Memesan kamar
- Mengelola profil dan melihat histori transaksi

## Fitur Utama
- Autentikasi (login/register)
- Halaman daftar kamar/history
- Daftar dan Detail activity
- Give review room

## Daftar Fitur (Rinci)
1. Homepage (search, recommend, promo)
2. Loading screen
3. Login & register (menggunakan Google account)
4. Settings page (edit profile, privacy policy, FAQ, helpdesk, dll)
5. List hotel (setelah search) dengan filter dan sorting
6. Detail hotel
7. Detail kamar
8. Detail booking (add-on)
9. Confirm payment (bayar dengan fingerprint lalu lanjut ke receipt)
10. Receipt (QR, booking no, bisa di-download PDF)
11. Give review (rating, foto opsional: galeri/kamera, comment wajib max 500 karakter)
12. List review untuk kamar &  hotel (akumulasi dari kamar)

## ERD

- Link ERD: https://lucid.app/lucidchart/ff2c7616-8ef8-4413-9534-edb4cb3076e0/edit?viewport_loc=-762%2C-25%2C3205%2C1596%2C0_0&invitationId=inv_4933c16b-0225-410c-a98a-a3c6510ff144

## Desain UI / Figma

- Link Figma: https://www.figma.com/design/9YBwRr39PJjp428pD5ZERF/2---Go.in?node-id=0-1&t=CZxWcroQcFrTLv4U-1

## Pembagian Tugas & Tanggung Jawab

Pembagian Tugas:
- Abi: loading screen, login & register, confirm payment
- Paulin: review hotel & kamar, homepage, receipt (QR Code), wishlist page, activity page
- Saski: detail hotel & kamar, detail booking, detail hotel
- Febby: settings page (edit profile), list hotel + filter, give review, promo page

## Kendala & Solusi (Contoh)
- Kendala: -
- Solusi - 

## Struktur Proyek

- `backend/` — Laravel API
- `frontend/` — Flutter app (mobile + web)

## Cara Menjalankan Proyek

1. Backend (Laravel):
   - Pasang dependensi: `composer install`
   - Salin `.env.example` ke `.env` dan konfigurasi
   - Jalankan `composer install`
   - Jalankan server: `php artisan serve`

2. Frontend (Flutter):
   - Pasang dependensi: `flutter pub get`
   - Jalankan: `flutter run` atau build sesuai platform