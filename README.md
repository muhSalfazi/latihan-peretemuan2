# latihan-pertemuan2

Latihan ini bertujuan untuk mengasah pemahaman dasar tentang sintaks PHP Native, terutama dalam penggunaan variabel, operator, dan struktur output.

---

## 1) Perbaiki dan rapikan kode berikut agar bisa berjalan dengan benar:

```php
<?php
$nama = "Dino";
echo "Halo nama saya $nama";
?>
```

---

## 2) Tuliskan kode PHP untuk menghitung luas persegi panjang dengan variabel panjang dan lebar.  
**Hasil output harus:**

```
Luas persegi panjang dengan panjang 10 dan lebar 5 adalah 50
```

```php
<?php
$panjang = 10;
$lebar = 5;
$luas = $panjang * $lebar;
echo "Luas persegi panjang dengan panjang $panjang dan lebar $lebar adalah $luas";
?>
```

---

## 3) Buatlah script PHP yang menampilkan hasil penjumlahan dua angka menggunakan operator aritmatika.  
**Ketentuan:**
- Gunakan `echo` untuk menampilkan hasil.
- Gunakan komentar untuk menjelaskan setiap baris kode.

```php
<?php
// Mendefinisikan dua angka
$angka1 = 7;
$angka2 = 5;

// Menjumlahkan kedua angka
$hasil = $angka1 + $angka2;

// Menampilkan hasil penjumlahan
echo "Hasil penjumlahan $angka1 + $angka2 = $hasil";
?>
```

---

## 4) Studi Kasus: Cetak Biodata Dinamis  
Buatlah sebuah script PHP yang mencetak biodata berikut:

```
Nama Lengkap  : Salman Fauzi
Umur          : 22
Hobi          : Coding, Musik
Status        : Mahasiswa
```

**Ketentuan:**
- Gunakan variabel untuk setiap elemen biodata.
- Output ditampilkan dalam format yang rapi seperti di atas.
- Gunakan penggabungan string.

```php
<?php
$nama = "Salman Fauzi";
$umur = 22;
$hobi = "Coding, Musik";
$status = "Mahasiswa";

echo "Nama Lengkap  : " . $nama . "\n";
echo "Umur          : " . $umur . "\n";
echo "Hobi          : " . $hobi . "\n";
echo "Status        : " . $status;
?>
```

> **Catatan:** Jika dijalankan di browser, gunakan `<br>` untuk ganti baris.

---

## 5) Studi Kasus: Sistem Penilaian Sederhana  
Buat program PHP untuk menilai nilai ujian siswa dengan ketentuan:

- Nilai diinput lewat variabel.
- Jika nilai ≥ 75, tampilkan "Lulus".
- Jika nilai < 75, tampilkan "Tidak Lulus".

**Contoh output:**
```
Nilai Anda: 82
Status: Lulus
```

```php
<?php
$nilai = 82;

echo "Nilai Anda: $nilai <br>";

if ($nilai >= 75) {
    echo "Status: Lulus";
} else {
    echo "Status: Tidak Lulus";
}
?>
```

---

Selamat mengerjakan!
