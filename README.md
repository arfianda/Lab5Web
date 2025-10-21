# 🧠 Praktikum 5 - JavaScript

Repository ini berisi latihan-latihan dari **Praktikum 5: JavaScript** pada mata kuliah Pemrograman Web.

## 📁 Struktur Folder
Berikut adalah isi folder praktikum:
- `lab5_javascript.html` → Pengenalan JavaScript (document.write & console.log)
- `alertbox.html` → Contoh penggunaan `alert()`
- `methodobject.html` → Contoh penggunaan `document.write()`
- `prompt.html` → Contoh penggunaan `prompt()`
- `create_and_call_function.html` → Membuat dan memanggil fungsi
- `basic_arithmetic.html` → Operasi aritmatika dasar
- `condition.html` → Seleksi kondisi `if...else`
- `switch_operator.html` → Seleksi kondisi dengan `switch`
- `input_form.html` → Validasi form input
- `formbutton.html` → Tombol dengan event JavaScript
- `dom.html` → Contoh manipulasi DOM (checkbox & total harga)

## ⚙️ Cara Menjalankan
1. Buka folder proyek di VSCode.
2. Klik kanan pada file `.html` → **Open with Live Server**,  
   atau buka langsung di browser dengan klik dua kali file-nya.
3. Setiap file akan menampilkan hasil latihan yang berbeda.

## 🎯 Tujuan Praktikum
- Memahami sintaks dasar JavaScript.  
- Menggunakan JavaScript untuk interaksi di halaman web.  
- Mempelajari manipulasi elemen HTML menggunakan JavaScript.

## 🧾 Tugas Akhir
1. Buat validasi pada form input.

![image alt >](/docs/forminput.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Form Input</title>
</head>
<body>
    <form name="inputForm" onsubmit="return validasi()">
        Nama: <input type="text" name="nama"><br>
        Email: <input type="text" name="email"><br>
        <input type="submit" value="Kirim">
    </form>

    <script>
        function validasi() {
            var nama = document.inputForm.nama.value;
            var email = document.inputForm.email.value;
            if (nama == "" || email == "") {
                alert("Nama dan Email tidak boleh kosong!");
                return false;
            } else {
                alert("Data berhasil dikirim!");
                return true;
            }
        }
    </script>
</body>
</html>
```

2. Dokumentasi hasil.

### Pengenalan Js

![image alt >](/docs/Screenshot_20251021_103903.png)

```html
<!DOCTYPE html>
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

### Alert Box

![image alt >](/docs/alert.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Alert Box</title>
</head>
<body>
    <script>
        window.alert("Ini merupakan pesan untuk Anda");
    </script>
</body>
</html>
```




---

👨‍💻 **Dibuat oleh:** Arfianda Firsta Satritama  / 312410377
📚 Universitas Pelita Bangsa  
