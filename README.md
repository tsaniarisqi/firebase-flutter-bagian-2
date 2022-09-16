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

## Tambahkan LoginPengguna (RSVP)
![Screenshoot firebase](images/05.png)

| Result | Description |
| --- | --- |
| <img src="images/05-1.png" width="600"> | Berikut merupakan halaman awal dari alur otentikasi. User dapat menekan tombol RSVP, untuk memulai formulir email. |
| <img src="images/05-2.png" width="600"> | Setelah memasukkan email, sistem mengkonfirmasi jika pengguna sudah terdaftar, dalam hal ini pengguna dimintai kata sandi, atau jika pengguna tidak terdaftar, maka mereka pergi melalui formulir pendaftaran. |
| <img src="images/05-3.png" width="600"> | Jika belum memiliki akun maka akan diminta untuk mengisi formulir create account. Masukkan email dan password|
| <img src="images/05-4.png" width="600"> | Ketika password kurang dari enam karakter maka akan muncul pemberitahuan bahwa password yang dimasukkan harus terdiri dari enam karakter atau lebih.|
| <img src="images/05-5.png" width="600"> | Masukkan email dan password sesuai dengan yang dibuat pada ceate account. |
| <img src="images/05-6.png" width="600"> | Halaman yang akan tampil ketika berhasil login |
| <img src="images/05-7.png" width="600"> | Ketika password yang dimasukkan salah maka akan muncul pemberitahuan bahwa password yang dimasukkan salah |

## Tulis Pesan ke Cloud Firestor
![Screenshoot firebase](images/06.png)
- Untuk mengirim pesan pastikan sudah masuk ke akun 
- <img src="images/06-1.png" width="300"> 
- Coba untuk memasukkan pesan, disini saya mencoba memasukkan pesan "Hi!" 
- <img src="images/06-2.png" width="300"> 
- Pesan yang berhasil dikirimkan akan tersimpan pada cloyd firestore, seperti gambar berikut 
- <img src="images/06-3.png" width="700"> 

## Baca Pesan
- Pesan yang berhasil disimpan akan ditampilkan pada aplikasi 
![Screenshoot firebase](images/07.png)
