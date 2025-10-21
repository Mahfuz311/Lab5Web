# Praktikum 5 - Javascript
**Nama:** Mahfuz Fauzi  
**Kelas:** TI.24.A.3  
**NIM:** 312410412  
**Mata Kuliah:** Pemrograman Web  
**Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom  
**Universitas Pelita Bangsa**

---

## 🧩 Langkah-langkah Praktikum

### 1. Persiapan File dan Folder

Buat folder bernama `Lab5Web` Di dalam folder tersebut, buat file HTML baru dengan nama `lab5_javascript.html`.

**Struktur dasar HTML.**

```<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output1.png">

`document.write()` digunakan untuk menampilkan teks langsung pada halaman web.

`console.log()` menampilkan teks pada konsol browser (bisa dilihat lewat Inspect → Console).

---

### 2. Javascript Dasar

#### Pemakaian Alert sebagai property window.

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode2.png">

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output2.png">

`alert()` menampilkan pesan peringatan.

---

#### Pemakaian Method Dalam Objek

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode3.png">

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output3.png">

---

#### Pemakaian Prompt

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode4.png">

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output4.png">

Lalu saya memasukan Nama.

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output4.1.png">

**Dan hasilnya seperti ini:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output4.2.png">

`prompt()` meminta input dari pengguna.

---

#### Pembuatan Fungsi dan Pemanggilannya

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode5.png">

**Outputnya**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output5.png">

---

### 3. Dasar Pemrograman di Javascript

#### Operasi Dasar Aritmatika

Contoh Operasi dan Logika Sederhana:

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode6.png">

**Outputnya**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output6.png">

Lalu Klik Tombol _`arithmetic`_:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output6.1.png">

📝 Penjelasan:

- JavaScript mendukung operasi aritmatika (`+`, `-`, `*`, `/`) dan logika `if...else`.

- Kode di atas memeriksa hasil penjumlahan dan menampilkan pesan yang sesuai.

---

#### Seleksi Kondisi (`if..else`)

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode7.png">

**Outputnya**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output7.png">

Kita Langsung Klik Tombol Ok:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output7.1.png">

Hasilnya "Tidak Lulus" Karena Nilai yang Saya Masukan Adalah 0, `(nilai >= 60)` nilai harus lebih besar dari 0.

Lalu Saya Masukan Angka 80:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output7.2.png">

Hasilnya "Lulus" Karena Nilainya Lebih Besar Dari 60.

---

#### Penggunaan Operator Switch Untuk Seleksi Kondisi

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode8.png">

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output8.png">

Selanjutnya Saya Klik Tombol `Switch`:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output8.1.png">

Kita Diminta Untuk Memasukkan Angka 1-5.

Disini Saya Memasukkan Angka 3:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output8.2.png">

Hasilnya Muncul "Bilangan Tiga" Karena yang Saya Memasukkan Angka 3.

---

### 4. Pembuatan From

#### Form Input

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode9.png">

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output9.png">

Disni Muncul Form dimana Kita Diminta Untuk Memasukan Angka Bilangan Genap atau Bilangan Ganjil.

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output9.1.png">

Saya Memasukan Angka 16 dan Sistem akan Otomatis Membaca Bahwa itu Bilangan Genap dan Sebaliknya, kalau Saya Memasukan Angka 11 Maka Sistem Akan Membaca Bahwa itu Adalah Bilangan Ganjil.

---

#### From Button

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode10.png">

**Outputnya**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output10.png">

Saya Klik Latar Belakang Hijau dan Teks Kuning:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output10.1.png">

Maka Hasilnya Akan Merubah Warna Background dan Warna Tulisannya.

---

### 5. HTML DOM

#### Pilihan Menggunakan CheckBox dengan Perhitungan Otomatis

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode11.png">

**Outputnya**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output11.png">

Dan Bisa Menjumlahkan Otomatis Jika Kita Memilih lebih dari 1 Produk:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output11.1.png">

---

### 6. Pertanyaan dan Tugas

#### 1. Buat script untuk melakukan validasi pada isian form.

Disini Saya Menggunakan Form Pemesanan HandPhone Seperti yang Di Atas.

Code:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/vscode12.png">

**Outputnya:**

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output12.png">

Mengisi Form:

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output12.3.png">

Validasi Form (Tugas)

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output12.2.png">

Jika pengguna:

- Tidak mengisi nama → muncul pesan “Nama harus diisi!”
- Nomor HP bukan angka atau kurang dari 10 digit → “Nomor HP harus 10–13 digit!”
- Tidak memilih handphone → “Pilih minimal satu handphone!”

<img src="https://github.com/Mahfuz311/Lab5Web/blob/d39b4099683cba931c84ab9935290aa5d33ffa31/screenshot/output12.1.png">

Jika Semua Benar Muncul Pesan Sukes.

```✅ Pesanan berhasil dikirim!
Nama: Mahfuz Fauzi
Nomor HP: 081234567890
Total Bayar: Rp 39.248.000.00
```

---
