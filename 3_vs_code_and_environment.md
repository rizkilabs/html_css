# **VS Code & Environment: Penjelasan Lengkap**

## **Apa Itu VS Code?**

📌 **VS Code (Visual Studio Code)** adalah **code editor** yang ringan namun sangat powerful, dibuat oleh Microsoft.

📌 Digunakan oleh developer untuk menulis kode dalam berbagai bahasa pemrograman seperti **HTML, CSS, JavaScript, Python, PHP, dan lainnya**.

📌 Dilengkapi dengan fitur seperti **Auto-completion, Debugging, Extensions, dan Terminal** untuk mempermudah pengembangan aplikasi.

---

## **Mengapa Memilih VS Code?**

✅ **Gratis dan Open Source**

✅ **Ringan & Cepat**

✅ **Banyak Extension (Ekstensi) yang Mendukung Berbagai Bahasa Pemrograman**

✅ **Bisa Langsung Menjalankan Kode dengan Terminal Bawaan**

---

## **Cara Menginstall VS Code**

1️⃣ **Download VS Code** dari situs resmi: https://code.visualstudio.com/

2️⃣ Pilih versi sesuai dengan sistem operasi kamu (Windows, macOS, atau Linux).

3️⃣ Install seperti software biasa.

4️⃣ Buka **VS Code** setelah instalasi selesai.

---

## **Mengenal Tampilan VS Code**

Ketika pertama kali membuka VS Code, berikut adalah bagian utama yang perlu kamu ketahui:

🔹 **Explorer** – Untuk melihat dan mengelola file proyek.

🔹 **Editor** – Tempat menulis kode.

🔹 **Terminal** – Untuk menjalankan perintah seperti menjalankan server atau menginstal paket.

🔹 **Extensions** – Untuk menambahkan fitur tambahan seperti **Live Server, Prettier, dan lainnya**.

---

## **Menyiapkan Environment untuk Pengembangan Web**

Agar nyaman dalam menulis dan menjalankan kode, kita perlu mengatur **Environment (Lingkungan Pengembangan)** dengan langkah-langkah berikut:

### **1️⃣ Membuat Folder Proyek**

📌 Buat folder khusus untuk menyimpan file proyek web kamu.

🔹 Di **Windows**:

- Buka Explorer
- Klik kanan > **New Folder** > beri nama **"Proyek-Web"**
- Buka VS Code, lalu **File > Open Folder** > pilih folder **"Proyek-Web"**

🔹 Di **Mac/Linux**:

- Buka Terminal, lalu jalankan:
    
    ```
    mkdir Proyek-Web
    cd Proyek-Web
    code .
    
    ```
    
- Ini akan membuka VS Code langsung di dalam folder tersebut.

---

### **2️⃣ Membuat File Dasar Web (HTML, CSS, JavaScript)**

Di dalam **VS Code**, buat file berikut:

✅ `index.html` – Struktur utama halaman.

✅ `styles.css` – Untuk desain tampilan.

✅ `script.js` – Untuk interaktivitas halaman.

➡ **Struktur Folder**

```
Proyek-Web/
│── index.html
│── styles.css
└── script.js

```

---

### **3️⃣ Menulis Kode Dasar Web**

**File: `index.html`**

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Sederhana</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Halo, Dunia!</h1>
    <p>Ini adalah contoh website pertama saya.</p>
    <button onclick="sayHello()">Klik Saya</button>

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
}
button:hover {
    background-color: darkgreen;
}

```

**File: `script.js`**

```
function sayHello() {
    alert("Halo, Selamat Datang di Website Saya!");
}

```

---

### **4️⃣ Menjalankan Website dengan Live Server**

Agar lebih mudah melihat perubahan kode tanpa harus **refresh manual**, kita bisa menggunakan ekstensi **Live Server**.

🔹 **Cara Menginstall Live Server**

1. Buka **VS Code**
2. Pergi ke **Extensions** (Ctrl + Shift + X)
3. Cari **Live Server**, lalu klik **Install**
4. Setelah terinstall, klik kanan pada `index.html` > **Open with Live Server**
5. Halaman akan terbuka di browser secara otomatis

📌 **Sekarang setiap kali kamu menyimpan perubahan, browser akan otomatis refresh!** 🚀

---

### **5️⃣ Menjalankan JavaScript di VS Code dengan Node.js (Opsional)**

Jika ingin menjalankan kode **JavaScript** tanpa browser, kita bisa menggunakan **Node.js**.

🔹 **Install Node.js**

- Download dari: https://nodejs.org/
- Install sesuai sistem operasi kamu.
- Cek apakah berhasil dengan perintah di **Terminal**:

Jika muncul versi Node.js, berarti sudah terinstall dengan benar.
    
    ```
    node -v
    
    ```
    

🔹 **Menjalankan Script JavaScript**

Misalnya kita punya file `test.js`:

```
console.log("Halo dari JavaScript di VS Code!");

```

Jalankan di terminal dengan perintah:

```
node test.js

```

📌 **Hasil akan langsung tampil di terminal!** ✅

---

## **Kesimpulan**

💡 **VS Code adalah editor kode yang powerful & fleksibel**

💡 **Kita bisa menggunakannya untuk pengembangan web dengan HTML, CSS, & JavaScript**

💡 **Dengan ekstensi seperti Live Server, kita bisa mengembangkan website lebih cepat**

💡 **Dengan Node.js, kita bisa menjalankan JavaScript langsung di terminal**

➡ **Sekarang kamu sudah siap untuk mulai ngoding dengan VS Code!** 🚀