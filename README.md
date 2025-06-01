# Waste Free - Aplikasi Pelaporan Sampah

Aplikasi pelaporan sampah berbasis Android menggunakan Flutter.

## Fitur

- Login dengan email/password dan social login
- Mode pengguna: Pelapor dan Petugas Kebersihan
- Informasi jenis sampah (Hijau, Kuning, Merah/B3)
- Pelaporan sampah dengan lokasi dan foto
- Tracking status laporan
- Manajemen laporan untuk petugas
- Sistem reward dengan koin

## Cara Menjalankan

1. Pastikan Flutter SDK sudah terinstall
2. Clone repository ini
3. Install dependencies:
```bash
flutter pub get
```
4. Jalankan aplikasi:
```bash
flutter run
```

## Struktur Project

```
lib/
├── main.dart
├── screens/
│   ├── auth/
│   │   └── login_screen.dart
│   ├── home/
│   │   ├── home_screen.dart
│   │   └── widgets/
│   │       ├── reporter_view.dart
│   │       ├── waste_type_card.dart
│   │       └── worker_view.dart
│   ├── report/
│   │   ├── create_report_screen.dart
│   │   └── report_details_screen.dart
│   ├── splash_screen.dart
│   └── user_mode_screen.dart
```

## Dependencies

- google_maps_flutter: Untuk menampilkan peta
- image_picker: Untuk mengambil foto
- shared_preferences: Untuk menyimpan data lokal
- provider: Untuk state management
- google_sign_in: Untuk login dengan Google
- flutter_facebook_auth: Untuk login dengan Facebook
