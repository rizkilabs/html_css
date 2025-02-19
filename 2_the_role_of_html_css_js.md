## **Peran HTML, CSS, dan JavaScript dalam Pengembangan Web**

Ketika kita membuka sebuah halaman web, sebenarnya ada tiga teknologi utama yang bekerja bersama untuk membuat tampilan dan interaktivitasnya, yaitu:

✅ **HTML (HyperText Markup Language)** – Struktur halaman

✅ **CSS (Cascading Style Sheets)** – Gaya dan desain tampilan

✅ **JavaScript** – Interaktivitas dan dinamika

Mari kita bahas satu per satu dengan cara yang mudah dipahami.

---

## **1. HTML: Struktur Halaman Web**

📌 **HTML adalah kerangka dasar sebuah website**.

Tanpa HTML, browser tidak akan tahu bagaimana menyusun konten halaman. HTML menggunakan **tag** untuk mendefinisikan elemen-elemen dalam web.

**Contoh:**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Belajar HTML</title>
</head>
<body>
    <h1>Selamat Datang di Website Saya</h1>
    <p>Ini adalah paragraf pertama saya!</p>
    <a href="https://www.example.com">Klik di sini untuk info lebih lanjut</a>
</body>
</html>

```

📌 **Penjelasan:**

- `<h1>` → Judul utama (heading).
- `<p>` → Paragraf teks.
- `<a>` → Tautan ke halaman lain.

➡ **Tanpa HTML, website tidak akan memiliki struktur dan tidak bisa ditampilkan di browser!**

---

## **2. CSS: Mengatur Gaya & Tampilan**

📌 **CSS digunakan untuk mempercantik tampilan website** agar lebih menarik dan enak dilihat.

**Tanpa CSS**

```html
<h1>Selamat Datang</h1>
<p>Ini adalah halaman web sederhana.</p>

```

Hasilnya hanya teks hitam polos di atas background putih.

**Dengan CSS**

```css
h1 {
    color: blue;
    font-size: 36px;
    text-align: center;
}
p {
    color: gray;
    font-style: italic;
}

```

📌 **Penjelasan:**

- `color: blue;` → Mengubah warna teks menjadi biru.
- `font-size: 36px;` → Memperbesar ukuran teks.
- `text-align: center;` → Pusatkan teks.

➡ **CSS membuat website lebih menarik dan nyaman dilihat!**

---

## **3. JavaScript: Menambahkan Interaktivitas**

📌 **JavaScript digunakan untuk membuat halaman menjadi dinamis dan interaktif**.

Misalnya, kita ingin menampilkan pesan ketika pengguna mengklik tombol.

```html
<button onclick="sayHello()">Klik Saya</button>

<script>
    function sayHello() {
        alert("Halo, Selamat Datang!");
    }
</script>

```

📌 **Penjelasan:**

- `<button>` → Tombol yang bisa diklik.
- `onclick="sayHello()"` → Saat tombol diklik, fungsi `sayHello()` dijalankan.
- `alert("Halo, Selamat Datang!")` → Menampilkan pesan pop-up.

➡ **JavaScript membuat website lebih hidup dan responsif!**

---

## **Gabungan HTML, CSS, dan JavaScript**

Mari kita buat contoh lengkap yang menggabungkan ketiga teknologi ini!

**File: `index.html`**

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Interaktif</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Halo, Pengunjung!</h1>
    <p>Klik tombol di bawah untuk mendapatkan pesan.</p>
    <button onclick="showMessage()">Klik Saya</button>

    <script src="script.js"></script>
</body>
</html>

```

**File: `styles.css`**

```css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
    padding: 50px;
}
h1 {
    color: blue;
}
button {
    padding: 10px 20px;
    background-color: green;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 16px;
}
button:hover {
    background-color: darkgreen;
}

```

**File: `script.js`**

```
function showMessage() {
    alert("Terima kasih telah mengklik tombol ini!");
}

```

➡ **Hasil:**

- Halaman memiliki **struktur (HTML)**.
- Tampilan menjadi lebih menarik dengan **warna & desain (CSS)**.
- Ada **interaksi tombol (JavaScript)** yang memunculkan pesan.

---

## **Kesimpulan**

🔹 **HTML = Struktur** (tanpa HTML, tidak ada konten).

🔹 **CSS = Desain** (tanpa CSS, halaman terlihat polos).

🔹 **JavaScript = Interaktif** (tanpa JS, halaman menjadi statis).

Ketiga teknologi ini saling melengkapi untuk membangun website yang **indah, interaktif, dan berfungsi dengan baik!** 🚀