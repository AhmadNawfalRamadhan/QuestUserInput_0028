# Pertemuan 5 – Form Data Diri

## Deskripsi
Aplikasi Android sederhana yang dibuat menggunakan Kotlin dan Jetpack Compose untuk menampilkan formulir pengisian data diri.

## Fitur
- Input nama lengkap.
- Pilihan jenis kelamin menggunakan RadioButton.
- Input alamat.
- Tombol Submit untuk menyimpan dan menampilkan data yang dimasukkan.
- Menampilkan hasil input dalam bentuk Card.
- Menggunakan HorizontalDivider sebagai pemisah komponen.
- Menggunakan resource dimensi dari `dimens.xml`.

## Teknologi
- Kotlin
- Android Studio
- Jetpack Compose
- Material Design 3

## Komponen yang Digunakan
- `OutlinedTextField` untuk input nama dan alamat.
- `RadioButton` untuk memilih jenis kelamin.
- `Button` untuk mengirim data.
- `ElevatedCard` untuk menampilkan hasil data diri.
- `HorizontalDivider` untuk pemisah.
- `remember` dan `mutableStateOf` untuk mengelola state.
- `dimensionResource` untuk mengambil nilai dimensi dari resource XML.

## Struktur Resource

File `dimens.xml` disimpan di direktori `res/values/`.

```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <dimen name="padding_small">10dp</dimen>
    <dimen name="padding_medium">30dp</dimen>
    <dimen name="divider_tipis">1dp</dimen>
</resources>
```

## Cara Menjalankan
1. Buka project melalui Android Studio.
2. Pastikan konfigurasi Gradle telah selesai disinkronkan.
3. Jalankan aplikasi menggunakan emulator atau perangkat Android.
4. Masukkan nama lengkap dan alamat.
5. Pilih jenis kelamin.
6. Tekan tombol **Submit** untuk menampilkan data pada Card.

## Tujuan Praktikum
Memahami penggunaan komponen UI Jetpack Compose, pengelolaan state, input data, pemilihan jenis kelamin, serta pemanfaatan resource dimensi pada aplikasi Android.

## Tampilan Aplikasi pada Emulator

### 1. Form Data Diri Kosong
Tampilan awal aplikasi ketika dijalankan pada emulator, sebelum pengguna mengisi data diri.

**Screenshot:** Tempelkan gambar emulator saat form masih kosong di sini.

### 2. Form Data Diri Terisi
Tampilan aplikasi setelah pengguna memasukkan nama lengkap, memilih jenis kelamin, mengisi alamat, dan menekan tombol **Submit**. Data yang dimasukkan akan ditampilkan pada Card di bagian bawah form.

**Screenshot:** Tempelkan gambar emulator saat form sudah terisi dan hasilnya tampil di Card di sini.

### 1. Form Data Diri Kosong

!<img width="390" height="860" alt="Screenshot 2026-10-15 175816" src="https://github.com/user-attachments/assets/1dc7e390-33b9-4121-875e-b2eb5c0a0e7b" />


### 2. Form Data Diri Terisi

!<img width="384" height="857" alt="Screenshot 2026-10-15 175726" src="https://github.com/user-attachments/assets/72cbbaa9-b978-49ea-802c-aeb82f40f1b9" />
