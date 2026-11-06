# MADARA FF TOOL V1

Aplikasi Android Kotlin sederhana bertema merah-hitam untuk latihan aim mandiri.

## Build APK dari HP memakai GitHub Actions
1. Ekstrak ZIP di HP.
2. Buat repository baru di https://github.com/new (pilih Public atau Private; keduanya bisa).
3. Upload **isi folder project**, bukan file ZIP-nya. Pastikan `.github/workflows/android-apk.yml` ikut ter-upload.
4. Buka tab **Actions** di repository.
5. Pilih workflow **Build MADARA FF TOOL V1 APK**, lalu tekan **Run workflow**.
6. Tunggu proses selesai dengan tanda centang hijau.
7. Buka hasil run, gulir ke **Artifacts**, lalu unduh `MADARA-FF-TOOL-V1-APK`.
8. Ekstrak file artifact ZIP dan pasang `app-debug.apk` di HP.

Jika tab Actions meminta izin, pilih **I understand my workflows, go ahead and enable them**.
Jika GitHub menampilkan prompt untuk mengaktifkan Actions, aktifkan Actions untuk repository tersebut.

## Catatan
- Build menggunakan JDK 17, Gradle 8.9, Android SDK 35.
- Minimum Android aplikasi: Android 6.0 (API 23), sehingga Android 10 (API 29) didukung.
- Source ini untuk aim training mandiri. Tidak membaca atau mengubah memori Free Fire dan tidak menyuntikkan kode ke game.
