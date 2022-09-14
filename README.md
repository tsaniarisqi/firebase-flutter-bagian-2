# firebase_part2

A new Flutter project.

## Dapatkan kode sampel
![Screenshoot firebase](images/01.png)

## Membuat Proyek Firebase
- Membuat proyek firebase dengan nama Firebase-Flutter-Codelab
![Screenshoot firebase](images/02.png)

- Mengaktifkan login email untuk Firebase Authentication
![Screenshoot firebase](images/03.png)

- Mengaktifkan cloud firestore
![Screenshoot firebase](images/04.png)

## Konfigurasi Firebase
- Konfigurasi dependensi
```
flutter pub add firebase_core 
flutter pub add firebase_auth
flutter pub add cloud_firestore
flutter pub add provider
```

- Memasang flutterfire
```
dart pub global activate flutterfire_cli
```

- Mengonfigurasi aplikasi Anda
```
flutterfire configure
```