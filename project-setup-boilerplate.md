# Project Setup (Boilerplate)

## Boilerplate

Gunakan boilerplate agar tidak perlu membuat ulang bagian dasar setiap kali membuat app baru.

Boilerplate bisa berupa:

- Boilerplate pribadi yang sudah pernah dipakai.
- iOS boilerplate.
- Android boilerplate.
- Flutter boilerplate.
- React Native boilerplate.
- Template dari starter kit yang sudah siap monetisasi.

Yang penting, boilerplate harus membuat proses build lebih cepat dan mengurangi pekerjaan berulang.

## Yang Harus Sudah Ada Di Boilerplate

Minimal setup boilerplate:

- Dependencies utama.
- Struktur folder project.
- Onboarding.
- Paywall.
- Payment.
- Free trial.
- Premium state.
- Settings page.
- App config.
- Theme dasar.
- Reusable component.

## Dependencies

Siapkan dependencies yang hampir selalu dipakai di setiap app.

Contoh:

- Navigation.
- State management.
- In-app purchase.
- Subscription.
- Analytics.
- Crash reporting.
- Remote config.
- Image picker atau camera.
- API client.
- Local storage.

Tujuannya supaya project baru langsung siap dipakai tanpa setup dari nol.

## Onboarding

Onboarding harus sudah tersedia sebagai flow dasar.

Isi onboarding:

- Intro singkat fungsi app.
- Benefit utama app.
- Permission request jika dibutuhkan.
- Arahkan user ke paywall atau main screen.

Onboarding tidak perlu dibuat unik dari awal untuk setiap app. Cukup siapkan template yang bisa diganti copywriting, icon, warna, dan gambar.

## Paywall

Paywall wajib sudah tersedia di boilerplate jika app menggunakan monetisasi subscription.

Paywall minimal punya:

- Judul benefit.
- List fitur premium.
- Pilihan paket.
- Tombol continue.
- Restore purchase.
- Terms dan privacy link.
- Free trial jika ada.

Paywall harus mudah diganti kontennya sesuai app.

## Payment & Trial

Setup payment harus reusable.

Yang perlu disiapkan:

- Product ID.
- Subscription package.
- Trial status.
- Purchase flow.
- Restore purchase.
- Premium access check.
- Error handling saat purchase gagal.

Pastikan app bisa membedakan user free dan user premium.

## Premium State

Siapkan logic untuk mengecek status premium.

Contoh kebutuhan:

- Apakah user sudah subscribe.
- Apakah trial masih aktif.
- Apakah fitur premium boleh dibuka.
- Apakah paywall perlu ditampilkan.
- Apakah subscription sudah expired.

Premium state harus bisa dipakai di semua screen.

## Settings Page

Settings page minimal berisi:

- Restore purchase.
- Manage subscription.
- Privacy policy.
- Terms of use.
- Contact support.
- App version.

Jika app punya akun user, tambahkan:

- Profile.
- Sign out.
- Delete account.

## Struktur Project

Gunakan struktur folder yang konsisten.

Contoh:

```text
app/
  screens/
  components/
  services/
  config/
  constants/
  utils/
  assets/
```

Untuk app baru, cukup ganti:

- Nama app.
- Icon.
- Theme.
- Copywriting.
- Main feature.
- Product ID.
- Metadata.

## Step-by-Step

### 1. Clone Boilerplate

Mulai dari boilerplate yang sudah siap.

Jangan mulai dari project kosong kecuali benar-benar perlu.

### 2. Rename Project

Ganti nama project sesuai app baru.

Yang perlu diganti:

- App name.
- Bundle ID.
- Package name.
- App icon.
- Splash screen.
- Product ID.

### 3. Setup Dependencies

Pastikan semua dependencies sudah terinstall dan project bisa dijalankan.

Cek:

- App bisa run.
- Tidak ada error dependency.
- Build berhasil.
- Navigation berjalan.
- Theme tampil normal.

### 4. Setup Onboarding

Ganti isi onboarding sesuai app.

Update:

- Headline.
- Description.
- Benefit.
- Image atau icon.
- Permission request jika ada.

### 5. Setup Paywall

Ganti paywall sesuai positioning app.

Update:

- Premium benefit.
- Subscription package.
- Free trial.
- Product ID.
- Pricing display.

### 6. Setup Premium Access

Hubungkan fitur utama dengan premium state.

Contoh:

- User free hanya bisa scan beberapa kali.
- User premium bisa akses unlimited.
- Fitur tertentu dikunci sampai user subscribe.

### 7. Setup Settings

Pastikan halaman settings sudah siap.

Cek:

- Restore purchase berfungsi.
- Privacy policy terbuka.
- Terms of use terbuka.
- Contact support tersedia.
- App version tampil.

### 8. Jalankan App

Run app dan cek flow dasar.

Checklist:

- Onboarding tampil.
- Paywall tampil.
- Main screen bisa dibuka.
- Settings bisa dibuka.
- Premium state terbaca.
- Tidak ada crash saat app pertama dibuka.

## Ringkasan

Setup project harus dimulai dari boilerplate yang sudah punya dependencies, onboarding, paywall, payment, trial, premium state, dan settings, supaya fokus utama bisa langsung ke fitur inti app.
