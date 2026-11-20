# **WEB DEVELOPER LEARN — FROM ZERO TO EXPERT**

# **Panduan Lengkap Membangun Website dan Aplikasi Web dari Dasar hingga Profesional (Edisi 1.0 — 2026\)**

---

## **IDENTITAS PENULIS & INSTITUSI**

* **Penulis:** Danish Arfa Wibowo  
* **NIM:** 261111037  
* **Program Studi:** S1 Teknik Informatika  
* **Fakultas:** Fakultas Teknologi Informasi  
* **Institusi:** Universitas Nahdlatul Ulama Yogyakarta, Yogyakarta, Indonesia

---

## **KATA PENGANTAR**

Puji syukur kehadirat Allah SWT atas tersusunnya buku panduan komprehensif *Web Developer Learn — From Zero to Expert*. Buku ini dirancang sebagai kurikulum terstruktur dan panduan praktis yang menjembatani jurang antara teori akademis dan kebutuhan industri rekayasa perangkat lunak web modern.

Pengembangan web modern tidak lagi sekadar merangkai dokumen HTML dan CSS sederhana. Saat ini, seorang *Web Developer* dituntut untuk memahami arsitektur sistem yang kompleks, keamanan perangkat lunak, skalabilitas backend, hingga optimasi eksekusi di tingkat browser dan server. Buku ini disusun dari sudut pandang kurikulum Teknik Informatika untuk memberikan fondasi konseptual yang kuat sekaligus keterampilan teknis tingkat lanjut.

Harapan penulis, buku ini dapat menjadi acuan utama bagi mahasiswa, praktisi mandiri, maupun profesional yang ingin menguasai rekayasa web secara sistematis, disiplin, dan terukur.

Yogyakarta, 2026  
**Danish Arfa Wibowo**

---

## **PANDUAN PENGGUNAAN BUKU**

Untuk memperoleh hasil belajar yang optimal, pembaca disarankan mengikuti metode dan memahami konvensi yang digunakan dalam buku ini.

### **1\. Metodologi Belajar 7 Langkah (*7-Step Learning Method*)**

1. **Konsep & Analogi:** Pahami landasan teori dan kerangka konseptual melalui perumpamaan dunia nyata.  
2. **Setup Lingkungan:** Konfigurasikan sistem operasi (Ubuntu Linux Bash) dan alat pengembangan sesuai petunjuk.  
3. **Studi Kode:** Amati struktur pustaka, sintaksis, dan alur eksekusi logika.  
4. **Verifikasi Tekstual & Sintaksis:** Periksa validitas kode berdasarkan status pengujian yang tertera.  
5. **Analisis Kesalahan Komun:** Pelajari potensi *bug*, kerentanan keamanan, dan *anti-pattern*.  
6. **Praktik Mandiri (3 Tingkat):** Selesaikan latihan bernomor (*Easy*, *Intermediate*, *Challenge*).  
7. **Proyek Portofolio:** Terapkan seluruh materi ke dalam sistem nyata (seperti POS, e-commerce, atau API gateway).

### **2\. Konvensi Tag Prioritas Materi**

* `[WAJIB]`: Fondasi kritis yang mutlak dikuasai sebelum melangkah ke bab berikutnya.  
* `[INTI]`: Konsep mendasar dan sintaksis utama yang digunakan dalam pekerjaan sehari-hari.  
* `[LANJUTAN]`: Teknik tingkat tinggi untuk optimasi, skalabilitas, dan arsitektur tingkat lanjut.

### **3\. Kotak Informasi & Petunjuk Khusus**

**PERHATIAN (Security & Best Practice):** Menyoroti aspek keamanan, validasi kebenaran data di server (*server-truth*), dan penanganan konkurensi.**CATATAN STATIS VERIFIKASI:** Seluruh contoh kode dalam buku ini telah melalui tahap **\[Diperiksa tekstual\]** dan **\[Diperiksa sintaksis\]**. Namun, harap dicatat bahwa *runtime execution tidak dikonfirmasi secara otomatis pada lingkungan lokal pembaca*. Eksekusi riil bergantung pada versi *dependency* dan konfigurasi OS pembaca.

---

## **ROADMAP PEMBELAJARAN 5 FASE**

```
+-----------------------------------------------------------------------------------+

| FASE 1: FONDASI WEB & DASAR PENGEMBANGAN                                         |
|---|
+-----------------------------------------------------------------------------------+
                                         |
                                         v
+-----------------------------------------------------------------------------------+
| FASE 2: JAVASCRIPT ES6+ & MANIPULASI DOM                                         |
| Fundamentals, Async/Await, Fetch API, DOM Manipulation, Modules, Unit Testing     |
+-----------------------------------------------------------------------------------+
                                         |
                                         v
+-----------------------------------------------------------------------------------+
| FASE 3: BACKEND ENGINE & DATABASE ENGINEERING                                     |
| Node.js, Express.js, RESTful API, PostgreSQL, Relational Schema, ORM, Auth JWT    |
+-----------------------------------------------------------------------------------+
                                         |
                                         v
+-----------------------------------------------------------------------------------+
| FASE 4: FRONTEND FRAMEWORK MODERN & STATE MANAGEMENT                             |
| React.js Fundamentals, Hooks, State Management, Next.js App Router, SSR/SSG       |
+-----------------------------------------------------------------------------------+
                                         |
                                         v
+-----------------------------------------------------------------------------------+
| FASE 5: DEPLOYMENT, ARSITEKTUR TINGKAT LANJUT & PRODUKSI                          |
| Docker Containerization, CI/CD, Nginx Reverse Proxy, Security Hardening, POS Proj |
+-----------------------------------------------------------------------------------+
```

---

## **DAFTAR ISI TERSTRUKTUR**

* **FASE 1: FONDASI WEB & DASAR PENGEMBANGAN**  
  * Bab 1: Arsitektur Web & Protokol HTTP/HTTPS `[WAJIB]`  
  * Bab 2: HTML5 Semantik & Aksesibilitas Web (a11y) `[WAJIB]`  
  * Bab 3: CSS3 Modern: Flexbox Layout Engine `[INTI]`  
  * Bab 4: CSS3 Modern: Grid Layout System `[INTI]`  
  * Bab 5: Responsive Web Design & Mobile-First Strategy `[INTI]`  
  * Bab 6: Git & GitHub Workflow untuk Pengembang `[WAJIB]`  
  * Bab 7: Proyek Fase 1: Landing Page Profil Profesional `[INTI]`  
* **FASE 2: JAVASCRIPT ES6+ & MANIPULASI DOM**  
  * Bab 8: Dasar Sintaksis JavaScript & Tipe Data `[WAJIB]`  
  * Bab 9: Kontrol Alur, Fungsi & Scope `[INTI]`  
  * Bab 10: Array Engine & Object Manipulation `[INTI]`  
  * Bab 11: Manipulasi DOM & Event Handling `[INTI]`  
  * Bab 12: Asynchronous JavaScript: Promise & Async/Await `[WAJIB]`  
  * Bab 13: Fetch API & Interaksi REST API Client `[INTI]`  
  * Bab 14: JavaScript Modules (ESM) & Tooling Dasar `[LANJUTAN]`  
  * Bab 15: Proyek Fase 2: Aplikasi Manajemen Tugas (Task Engine) `[INTI]`  
* **FASE 3: BACKEND ENGINE & DATABASE ENGINEERING**  
  * Bab 16: Pengenalan Node.js & Runtime Environment `[WAJIB]`  
  * Bab 17: Express.js Framework & Routing Architecture `[INTI]`  
  * Bab 18: Restful API Design & Middleware Pipeline `[WAJIB]`  
  * Bab 19: Dasar Database Relasional & PostgreSQL `[WAJIB]`  
  * Bab 20: Pemodelan Data & Relasi Tabel PostgreSQL `[INTI]`  
  * Bab 21: Integrasi Node.js & Database Menggunakan ORM `[INTI]`  
  * Bab 22: Autentikasi & Otorisasi: JWT & Bcrypt `[WAJIB]`  
  * Bab 23: Keamanan API & Prevensi Kerentanan (OWASP) `[WAJIB]`  
  * Bab 24: Proyek Fase 3: REST API Point of Sale (POS) Engine `[INTI]`  
* **FASE 4: FRONTEND FRAMEWORK MODERN & STATE MANAGEMENT**  
  * Bab 25: Pengenalan React.js & Arsitektur Berbasis Komponen `[WAJIB]`  
  * Bab 26: JSX, Props, & State Management (useState, useReducer) `[INTI]`  
  * Bab 27: React Lifecycle & Side Effects (useEffect) `[INTI]`  
  * Bab 28: Form Handling & Validasi (React Hook Form / Zod) `[INTI]`  
  * Bab 29: Interaksi API Backend pada React (TanStack Query) `[LANJUTAN]`  
  * Bab 30: Routing Modern dengan React Router / Next.js App Router `[INTI]`  
  * Bab 31: Rendering Strategy: SSR, SSG, & ISR `[LANJUTAN]`  
  * Bab 32: Proyek Fase 4: Frontend Dashboard Point of Sale `[INTI]`  
* **FASE 5: DEPLOYMENT, ARSITEKTUR TINGKAT LANJUT & PRODUKSI**  
  * Bab 33: Konteinerisasi Aplikasi dengan Docker `[LANJUTAN]`  
  * Bab 34: CI/CD Pipeline dengan GitHub Actions `[LANJUTAN]`  
  * Bab 35: Web Server Hardening & Nginx Reverse Proxy `[LANJUTAN]`  
  * Bab 36: Monitoring, Logging, & Performance Tuning `[LANJUTAN]`  
  * Bab 37: Arsitektur Microservices vs Monolith Engine `[LANJUTAN]`  
  * Bab 38: Sistem Transaksi Terdistribusi & Transaksi Aman Server `[WAJIB]`  
  * Bab 39: Proyek Akhir: Production-Ready Fullstack POS System `[WAJIB]`  
* **BAGIAN PENUTUP**  
  * Glosarium Istilah  
  * Cheat Sheet Perintah Bash Ubuntu & Git  
  * Referensi Resmi & Bibliografi  
  * Indeks Istilah  
  * Lembar Cek List Kompetensi Industri

---

## **DAFTAR GAMBER, TABEL, DAN GLOSARIUM**

### **Daftar Tabel Utama**

1. **Tabel 1.1:** Perbandingan Metode HTTP (`GET`, `POST`, `PUT`, `DELETE`, `PATCH`)  
2. **Tabel 3.1:** Properti Utilitas Flexbox dan Perilakunya  
3. **Tabel 8.1:** Matriks Perbandingan Tipe Data Primordial dan Referensi JavaScript  
4. **Tabel 19.1:** Perbandingan Database SQL (PostgreSQL) vs NoSQL (MongoDB)  
5. **Tabel 22.1:** Struktur Anatomi JSON Web Token (JWT)  
6. **Tabel 38.1:** Matriks Isolasi Transaksi Database (ACID Compliance)

---

# **FASE 1: FONDASI WEB & DASAR PENGEMBANGAN**

## **Bab 1: Arsitektur Web & Protokol HTTP/HTTPS `[WAJIB]`**

### **1\. Konsep & Analogi**

Arsitektur web beroperasi menggunakan model *Client-Server*. Analogi sederhana dari arsitektur ini adalah sistem pemesanan makanan di restoran:

* **Client (Browser):** Pelanggan yang duduk di meja dan membaca menu. Pelanggan membuat pesanan (*Request*).  
* **Server (Web Server):** Dapur restoran yang memproses bahan makanan dan menghasilkan hidangan.  
* **Protokol HTTP/HTTPS:** Bahasa interaksi dan aturan kesopanan antara pelanggan dan pelayan.

### **2\. Perintah Ubuntu Linux Bash**

Untuk menguji konektivitas dan melihat respons *header* HTTP dari sebuah server melalui terminal Ubuntu Linux:

```
# Melakukan permintaan HTTP HEAD untuk melihat header respons
curl -I https://example.com

# Mengirim HTTP GET request dengan detail verbose
curl -v https://jsonplaceholder.typicode.com/posts/1
```

### **3\. Tabel Perbandingan Metode HTTP**

| Metode HTTP | Sifat Idempotent | Memiliki Body | Tujuan Utama |
| :---- | :---- | :---- | :---- |
| `GET` | Ya | Tidak | Mengambil sumber daya data dari server. |
| `POST` | Tidak | Ya | Membuat sumber daya baru di server. |
| `PUT` | Ya | Ya | Memperbarui seluruh isi sumber daya. |
| `PATCH` | Tidak | Ya | Memperbarui sebagian data dari sumber daya. |
| `DELETE` | Ya | Tidak | Menghapus sumber daya dari server. |

### **4\. Kesalahan Umum & Best Practice**

* **Kesalahan:** Mengirimkan data sensitif (seperti kata sandi) menggunakan metode `GET` melalui URL query parameter.  
* **Best Practice:** Selalu gunakan protokol HTTPS (TLS/SSL) untuk enkripsi data *in-transit* dan gunakan metode `POST` dengan enkapsulasi pada *request body*.

---

## **Bab 2: HTML5 Semantik & Aksesibilitas Web (a11y) `[WAJIB]`**

### **1\. Konsep & Analogi**

Dokumen HTML semantik ibarat struktur buku yang tertata rapi. Elemen `<header>`, `<main>`, `<article>`, dan \<footer\> membantu Screen Reader dan mesin pencari (SEO) memahami hierarki konten secara tepat.

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profil Pengembang Web</title>
</head>
<body>
  <header>
    <h1>Portofolio Pengembang</h1>
    <nav>
      <ul>
        <li><a href="#proyek">Proyek</a></li>
        <li><a href="#kontak">Kontak</a></li>
      </ul>
    </nav>
  </header>
  
  <main>
    <article>
      <h2>Tentang Saya</h2>
      <p>Saya seorang rekayasawan web yang berfokus pada performa dan aksesibilitas.</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2026 Danish Arfa Wibowo. Hak Cipta Dilindungi.</p>
  </footer>
</body>
</html>
```

---

## **Bab 3: CSS3 Modern: Flexbox Layout Engine `[INTI]`**

### **1\. Konsep & Analogi**

Flexbox (Flexible Box) adalah tata letak satu dimensi (baris atau kolom). Analoginya seperti menata susunan buku dalam satu rak: Anda bisa mengatur jarak antar buku, menjejalkannya di tengah, atau meratakannya ke kiri dan kanan.

### **2\. Perintah Bash & Pengaturan Lingkungan**

```
# Membuat struktur direktori proyek dasar
mkdir -p proyek-flexbox/css
cd proyek-flexbox
touch index.html css/style.css
```

### **3\. Kode Contoh CSS Flexbox \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
.card-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
  background-color: #f8fafc;
  padding: 24px;
}

.card-item {
  flex: 1 1 300px;
  background-color: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  padding: 16px;
}
```

---

## **Bab 4: CSS3 Modern: Grid Layout System `[INTI]`**

### **1\. Konsep & Analogi**

CSS Grid adalah sistem tata letak dua dimensi (baris dan kolom secara bersamaan). Analoginya seperti papan catur atau tata letak halaman surat kabar, tempat artikel dan gambar diletakkan pada sel-sel spesifik.

### **2\. Kode Contoh CSS Grid \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
.dashboard-grid {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 20px;
}

.sidebar {
  grid-column: span 3;
}

.main-content {
  grid-column: span 9;
}

@media (max-width: 768px) {
  .sidebar, .main-content {
    grid-column: span 12;
  }
}
```

---

## **Bab 5: Responsive Web Design & Mobile-First Strategy `[INTI]`**

### **1\. Konsep & Analogi**

Strategi *Mobile-First* mendesain tata letak dari layar terkecil (smartphone) terlebih dahulu, kemudian menambahkan kompleksitas visual seiring bertambahnya lebar layar (tablet dan desktop).

### **2\. Kode CSS Media Queries \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
/* Base style untuk Mobile */
body {
  font-size: 14px;
  padding: 12px;
}

/* Tablet Breakpoint */
@media (min-width: 640px) {
  body {
    font-size: 16px;
    padding: 24px;
  }
}

/* Desktop Breakpoint */
@media (min-width: 1024px) {
  body {
    max-width: 1200px;
    margin: 0 auto;
  }
}
```

---

## **Bab 6: Git & GitHub Workflow untuk Pengembang `[WAJIB]`**

### **1\. Konsep & Perintah Ubuntu Linux Bash**

Git adalah sistem kontrol versi terdistribusi. Setiap perubahan direkam dalam bentuk *commit* pada repositori lokal sebelum diunggah ke repositori terpusat seperti GitHub.h

# **Inisialisasi repositori Git lokal**

git init

# **Mengatur konfigurasi identitas pengembang**

git config \--global user.name "Danish Arfa Wibowo"  
git config \--global user.email "danish@example.com"

# **Membuat branch baru dan pindah ke branch tersebut**

git checkout \-b feature/login-page

# **Menambahkan perubahan ke staging area dan membuat commit**

git add .  
git commit \-m "feat: tambahkan struktur HTML halaman login"

# **Menghubungkan ke remote repository dan push**

git remote add origin https\://github.com/danish/pos-app.git  
git push \-u origin feature/login-page

````

---

### Bab 7: Proyek Fase 1: Landing Page Profil Profesional `[INTI]`

#### 1. Spesifikasi Proyek
Membangun halaman web portofolio pribadi yang responsif, terstruktur secara semantik, dan memenuhi kriteria aksesibilitas (a11y).

#### 2. Lembar Cek Penilaian Rubrik Proyek
* [ ] Struktur HTML5 menggunakan elemen semantik (`<header>`, `<main>`, `<section>`, `<footer>`).
* [ ] Kontras warna memenuhi standar WCAG AA (rasio minimal 4.5:1).
* [ ] Tata letak responsif menggunakan Flexbox/Grid pada ukuran layar 320px, 768px, dan 1024px.
* [ ] Repositori Git rapi dengan pesan *commit* mengikuti konvensi *Conventional Commits*.

---

## FASE 2: JAVASCRIPT ES6+ & MANIPULASI DOM

### Bab 8: Dasar Sintaksis JavaScript & Tipe Data `[WAJIB]`

#### 1. Konsep & Analogi
JavaScript adalah bahasa pemrograman dinamis. Variabel berfungsi sebagai kotak penyimpanan data. Tipe data terbagi menjadi dua: Primordial (Primitive) dan Referensi (Reference).

#### 2. Kode Contoh [Diperiksa tekstual] [Diperiksa sintaksis]
```javascript
// Deklarasi Variabel Modern (ES6)
const namaPengembang = "Danish Arfa Wibowo"; // String (Immutable)
let jumlahProyek = 5;                        // Number
const isAktif = true;                       // Boolean
let dataKosong = null;                       // Null
let belumDefinisi;                          // Undefined

// Tipe Data Referensi
const profil = {
  nim: "261111037",
  prodi: "S1 Teknik Informatika"
};

console.log(`Pengembang: ${namaPengembang}, Total Proyek: ${jumlahProyek}`);
````

---

## **Bab 9: Kontrol Alur, Fungsi & Scope `[INTI]`**

### **1\. Konsep & Analogi**

Fungsi adalah blok kode terisolasi yang menerima masukan (*input*) dan mengembalikan keluaran (*output*). Scope mengatur tingkat aksesibilitas variabel.

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
// Arrow Function dengan Default Parameter
const hitungTotalHarga = (hargaSatuan, kuantitas = 1, diskon = 0) => {
  const subtotal = hargaSatuan * kuantitas;
  const totalDiskon = subtotal * diskon;
  return subtotal - totalDiskon;
};

// Penggunaan Kontrol Alur Evaluasi
const prosesPembayaran = (saldo, totalBelanja) => {
  if (saldo < totalBelanja) {
    throw new Error("Saldo tidak mencukupi untuk melakukan transaksi.");
  }
  return saldo - totalBelanja;
};

console.log("Total Transaksi:", hitungTotalHarga(50000, 2, 0.1));
```

---

## **Bab 10: Array Engine & Object Manipulation `[INTI]`**

### **1\. Konsep & Analogi**

Metode tingkat tinggi pada Array (`map`, `filter`, `reduce`) memungkinkan pemrosesan data deklaratif tanpa mutating data asli (*immutability*).

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
const daftarProduk = [
  { id: 1, nama: "Kopi Hitam", harga: 15000, stok: 10 },
  { id: 2, nama: "Teh Hijau", harga: 12000, stok: 0 },
  { id: 3, nama: "Roti Bakar", harga: 20000, stok: 5 }
];

// Filter produk yang memiliki stok > 0
const produkTersedia = daftarProduk.filter(item => item.stok > 0);

// Transformasi array menjadi format string nama
const namaProduk = produkTersedia.map(item => item.nama);

// Hitung total nilai inventaris stok
const totalNilaiStok = daftarProduk.reduce((acc, item) => {
  return acc + (item.harga * item.stok);
}, 0);

console.log("Total Inventaris:", totalNilaiStok);
```

---

## **Bab 11: Manipulasi DOM & Event Handling `[INTI]`**

### **1\. Konsep**

DOM (*Document Object Model*) adalah representasi pohon dari struktur HTML di dalam memori browser. JavaScript berinteraksi dengan DOM melalui metode seleksi dan event listener.

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
// Mengambil elemen dari DOM
const tombolSimpan = document.querySelector("#btn-save");
const inputNama = document.querySelector("#input-name");
const daftarOutput = document.querySelector("#list-output");

// Menambahkan Event Listener
tombolSimpan.addEventListener("click", (event) => {
  event.preventDefault();
  
  const nilaiInput = inputNama.value.trim();
  if (!nilaiInput) return;

  const itemBaru = document.createElement("li");
  itemBaru.textContent = nilaiInput;
  daftarOutput.appendChild(itemBaru);

  inputNama.value = "";
});
```

---

## **Bab 12: Asynchronous JavaScript: Promise & Async/Await `[WAJIB]`**

### **1\. Konsep & Analogi**

Operasi asinkronus memungkinkan eksekusi kode non-blocking. Analoginya seperti memesan kopi di kafe: Anda menerima nomor antrean (*Promise*) dan dapat melakukan aktivitas lain hingga kopi Anda selesai dibuat.

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
const ambilDataServer = (url) => {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      if (url) {
        resolve({ status: 200, data: "Data Sukses Dimuat" });
      } else {
        reject(new Error("URL tidak valid"));
      }
    }, 1000);
  });
};

// Menggunakan Async/Await dengan Handling Error Try/Catch
const eksekusiPengambilanData = async () => {
  try {
    const hasil = await ambilDataServer("https://api.example.com/data");
    console.log("Hasil:", hasil.data);
  } catch (error) {
    console.error("Terjadi Kesalahan:", error.message);
  }
};

eksekusiPengambilanData();
```

---

## **Bab 13: Fetch API & Interaksi REST API Client `[INTI]`**

### **1\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
const buatPostBaru = async (dataPost) => {
  try {
    const response = await fetch("https://jsonplaceholder.typicode.com/posts", {
      method: "POST",
      headers: {
        "Content-Type": "application/json; charset=UTF-8"
      },
      body: JSON.stringify(dataPost)
    });

    if (!response.ok) {
      throw new Error(`HTTP Error status: ${response.status}`);
    }

    const hasil = await response.json();
    return hasil;
  } catch (error) {
    console.error("Gagal mengirim data:", error);
    throw error;
  }
};
```

---

## **Bab 14: JavaScript Modules (ESM) & Tooling Dasar `[LANJUTAN]`**

### **1\. Konsep & Perintah Bash**

ES Modules mengizinkan pemisahan kode ke dalam berkas-berkas terisolasi menggunakan kata kunci `export` dan `import`.

```
# Inisialisasi proyek Node.js untuk dukungan ESM
npm init -y
npm pkg set type="module"
```

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
// Berkas: utils/math.js
export const tambah = (a, b) => a + b;
export const kurangi = (a, b) => a - b;

// Berkas: main.js
import { tambah, kurangi } from './utils/math.js';
console.log(tambah(10, 5));
```

---

## **Bab 15: Proyek Fase 2: Aplikasi Manajemen Tugas (Task Engine) `[INTI]`**

### **1\. Latihan Bertingkat**

* **Easy:** Buat fungsi untuk menambahkan tugas ke dalam *array* dan menampilkannya ke DOM.  
* **Intermediate:** Tambahkan fitur *filter* tugas (Selesai/Belum Selesai) dan simpan data ke `localStorage`.  
* **Challenge:** Implementasikan *drag-and-drop reordering* pada item tugas dan integrasikan dengan API publik mock server.

---

# **FASE 3: BACKEND ENGINE & DATABASE ENGINEERING**

## **Bab 16: Pengenalan Node.js & Runtime Environment `[WAJIB]`**

### **1\. Konsep**

Node.js adalah JavaScript runtime yang dibangun di atas mesin V8 Google Chrome, mengeksekusi kode JavaScript di luar peramban (browser) untuk kebutuhan server-side.

### **2\. Perintah Ubuntu Linux Bash**

```
# Mengunduh dan mengonfigurasi Node.js LTS via NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source ~/.bashrc
nvm install --lts
node -v
```

---

## **Bab 17: Express.js Framework & Routing Architecture `[INTI]`**

### **1\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
import express from 'express';
const app = express();
const PORT = 3000;

app.use(express.json());

app.get('/api/v1/health', (req, res) => {
  res.status(200).json({ status: 'OK', timestamp: new Date().toISOString() });
});

app.listen(PORT, () => {
  console.log(`Server berjalan di http://localhost:${PORT}`);
});
```

---

## **Bab 18: Restful API Design & Middleware Pipeline `[WAJIB]`**

### **1\. Konsep Middleware**

Middleware adalah fungsi yang memiliki akses ke objek permintaan (`req`), respons (`res`), dan fungsi `next` dalam siklus respons-permintaan aplikasi Express.

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
// Middleware Logger
const loggerMiddleware = (req, res, next) => {
  console.log(`[${new Date().toISOString()}] ${req.method} ${req.url}`);
  next();
};

app.use(loggerMiddleware);
```

---

## **Bab 19: Dasar Database Relasional & PostgreSQL `[WAJIB]`**

### **1\. Perintah Ubuntu Linux Bash**

```
# Instalasi PostgreSQL Server di Ubuntu
sudo apt update
sudo apt install postgresql postgresql-contrib -y

# Masuk ke prompt PostgreSQL
sudo -u postgres psql
```

---

## **Bab 20: Pemodelan Data & Relasi Tabel PostgreSQL `[INTI]`**

### **1\. Script SQL \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
CREATE TABLE produk (
  id SERIAL PRIMARY KEY,
  nama_produk VARCHAR(100) NOT NULL,
  harga NUMERIC(12, 2) NOT NULL CHECK (harga >= 0),
  stok INT NOT NULL DEFAULT 0 CHECK (stok >= 0),
  created_at TIMESTAMP WITH TIME ZONE DEFAULT CURRENT_TIMESTAMP
);

CREATE TABLE transaksi (
  id SERIAL PRIMARY KEY,
  total_bayar NUMERIC(12, 2) NOT NULL,
  created_at TIMESTAMP WITH TIME ZONE DEFAULT CURRENT_TIMESTAMP
);
```

---

## **Bab 21: Integrasi Node.js & Database Menggunakan ORM `[INTI]`**

### **1\. Kode Prisma ORM Schema \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
datasource db {
  provider = "postgresql"
  url      = env("DATABASE_URL")
}

generator client {
  provider = "prisma-client-js"
}

model Product {
  id        Int      @id @default(autoincrement())
  name      String
  price     Decimal  @db.Decimal(12, 2)
  stock     Int
  createdAt DateTime @default(now())
}
```

---

## **Bab 22: Autentikasi & Otorisasi: JWT & Bcrypt `[WAJIB]`**

### **1\. Konsep Keamanan**

Sandi pengguna **TIDAK BOLEH** disimpan dalam bentuk plain-text. Gunakan algoritma *hashing* seperti `bcrypt` dengan faktor garam (*salt factor*) minimal 10\.

### **2\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
import bcrypt from 'bcrypt';
import jwt from 'jsonwebtoken';

const SECRET_KEY = "kunci_rahasia_super_aman";

// Hashing Password
const hashPassword = async (passwordPlain) => {
  const saltRounds = 10;
  return await bcrypt.hash(passwordPlain, saltRounds);
};

// Generasi JWT Token
const generateToken = (payloadUser) => {
  return jwt.sign(payloadUser, SECRET_KEY, { expiresIn: '1h' });
};
```

---

## **Bab 23: Keamanan API & Prevensi Kerentanan (OWASP) `[WAJIB]`**

### **1\. Poin Mitigasi Kerentanan**

**PERHATIAN (Security Hardening):**

* **SQL Injection:** Hindari penggabungan string manual pada query SQL. Gunakan *parameterized queries* atau ORM.  
* **XSS (Cross-Site Scripting):** Sanitisasi input pengguna dan pasang header `Content-Security-Policy`.  
* **CORS:** Konfigurasikan asal domain (*origin*) secara spesifik, hindari `Access-Control-Allow-Origin: *` pada sistem transaksi.

---

## **Bab 24: Proyek Fase 3: REST API Point of Sale (POS) Engine `[INTI]`**

### **1\. Arsitektur Transaksi Server-Truth & Konkurensi**

Dalam proyek Point of Sale, penetapan harga produk dan ketersediaan stok harus diproses sepenuhnya di sisi server (*Server-Truth*). Klien hanya mengirimkan `product_id` dan `quantity`.

---

# **FASE 4: FRONTEND FRAMEWORK MODERN & STATE MANAGEMENT**

## **Bab 25: Pengenalan React.js & Arsitektur Berbasis Komponen `[WAJIB]`**

### **1\. Konsep**

React adalah pustaka JavaScript declarative berbasis komponen UI. Komponen mengisolasi logika dan tampilan menjadi potongan kode yang dapat digunakan kembali (*reusable*).

### **2\. Perintah Bash Ubuntu Setup**

```
# Membuat proyek React baru menggunakan Vite
npm create vite@latest pos-frontend -- --template react-ts
cd pos-frontend
npm install
npm run dev
```

---

## **Bab 26: JSX, Props, & State Management (useState, useReducer) `[INTI]`**

### **1\. Kode Contoh React Component \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
import React, { useState } from 'react';

interface ButtonProps {
  label: string;
  onClick: () => void;
}

const CustomButton: React.FC<ButtonProps> = ({ label, onClick }) => (
  <button onClick={onClick} className="px-4 py-2 bg-blue-600 text-white rounded">
    {label}
  </button>
);

export const Counter = () => {
  const [count, setCount] = useState<number>(0);

  return (
    <div>
      <p>Jumlah Hitungan: {count}</p>
      <CustomButton label="Tambah" onClick={() => setCount(count + 1)} />
    </div>
  );
};
```

---

## **Bab 27: React Lifecycle & Side Effects (useEffect) `[INTI]`**

### **1\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
import React, { useState, useEffect } from 'react';

export const DataFetcher = () => {
  const [data, setData] = useState<string | null>(null);

  useEffect(() => {
    let isMounted = true;

    fetch('https://api.example.com/status')
      .then(res => res.json())
      .then(result => {
        if (isMounted) setData(result.status);
      });

    return () => {
      isMounted = false; // Cleanup untuk menghindari memory leak
    };
  }, []);

  return <div>Status System: {data ?? 'Loading...'}</div>;
};
```

---

## **Bab 28: Form Handling & Validasi (React Hook Form / Zod) `[INTI]`**

### **1\. Kode Contoh \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
import { useForm } from 'react-hook-form';
import { z } from 'zod';
import { zodResolver } from '@hookform/resolvers/zod';

const schema = z.object({
  email: z.string().email({ message: "Format email tidak valid" }),
  password: z.string().min(8, { message: "Password minimal 8 karakter" }),
});

type FormData = z.infer<typeof schema>;

export const LoginForm = () => {
  const { register, handleSubmit, formState: { errors } } = useForm<FormData>({
    resolver: zodResolver(schema)
  });

  const onSubmit = (data: FormData) => console.log(data);

  return (
    <form onSubmit={handleSubmit(onSubmit)}>
      <input {...register("email")} placeholder="Email" />
      {errors.email && <p>{errors.email.message}</p>}
      
      <input type="password" {...register("password")} placeholder="Password" />
      {errors.password && <p>{errors.password.message}</p>}
      
      <button type="submit">Login</button>
    </form>
  );
};
```

---

## **Bab 29: Interaksi API Backend pada React (TanStack Query) `[LANJUTAN]`**

### **1\. Konsep**

TanStack Query (React Query) mengelola status pencarian server (*server state*), pencachean data, pembaruan otomatis, dan *invalidation*.

---

## **Bab 30: Routing Modern dengan React Router / Next.js App Router `[INTI]`**

### **1\. Konsep App Router (Next.js)**

Struktur folder menentukan rute halaman. Berkas `page.tsx` menjadi komponen utama rute, sementara `layout.tsx` membungkus rute turunan.

---

## **Bab 31: Rendering Strategy: SSR, SSG, & ISR `[LANJUTAN]`**

### **1\. Perbandingan Strategi Rendering**

* **SSR (Server-Side Rendering):** Halaman di-render pada server setiap ada permintaan. Cocok untuk data dinamis.  
* **SSG (Static Site Generation):** Halaman di-generate pada saat proses build. Cocok untuk konten statis/blog.  
* **ISR (Incremental Static Revalidation):** Memperbarui halaman statis di latar belakang tanpa me-rebuild seluruh situs.

---

## **Bab 32: Proyek Fase 4: Frontend Dashboard Point of Sale `[INTI]`**

### **1\. Spesifikasi Proyek**

Membangun antarmuka kasir interaktif yang memiliki pencarian produk instan, keranjang belanja dinamis, dan sinkronisasi status transaksi dengan REST API server.

---

# **FASE 5: DEPLOYMENT, ARSITEKTUR TINGKAT LANJUT & PRODUKSI**

## **Bab 33: Konteinerisasi Aplikasi dengan Docker `[LANJUTAN]`**

### **1\. Konsep & Analogi**

Docker membungkus aplikasi dan seluruh pustaka ketergantungannya ke dalam sebuah container terisolasi yang dapat berjalan seragam di lingkungan mana pun.

### **2\. Kode Dockerfile \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```
# Multi-stage Build untuk Produksi Node.js
FROM node:20-alpine AS builder
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
RUN npm run build

FROM node:20-alpine AS runner
WORKDIR /app
ENV NODE_ENV=production
COPY --from=builder /app/package*.json ./
COPY --from=builder /app/node_modules ./node_modules
COPY --from=builder /app/dist ./dist

EXPOSE 3000
CMD ["node", "dist/main.js"]
```

---

## **Bab 34: CI/CD Pipeline dengan GitHub Actions `[LANJUTAN]`**

### **1\. Konfigurasi GitHub Actions Workflow (`.github/workflows/deploy.yml`)**

```
name: CI/CD Pipeline

on:
  push:
    branches: [ "main" ]

jobs:
  test-and-build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Setup Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '20'
      - run: npm ci
      - run: npm test
      - run: npm run build
```

---

## **Bab 35: Web Server Hardening & Nginx Reverse Proxy `[LANJUTAN]`**

### **1\. Konfigurasi Nginx Server Block (`/etc/nginx/sites-available/pos-app`)**

```
server {
    listen 80;
    server_name pos.example.com;

    location / {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
    }
}
```

---

## **Bab 36: Monitoring, Logging, & Performance Tuning `[LANJUTAN]`**

### **1\. Konsep**

Penggunaan PM2 untuk *process management* di lingkungan Ubuntu Linux untuk menjamin ketersediaan aplikasi secara terus-menerus (*high availability*).

```
# Instalasi PM2 secara global
sudo npm install -g pm2

# Menjalankan aplikasi Node.js dalam mode Kluster
pm2 start dist/main.js -i max --name "pos-backend"

# Konfigurasi PM2 agar otomatis berjalan saat OS reboot
pm2 startup
pm2 save
```

---

## **Bab 37: Arsitektur Microservices vs Monolith Engine `[LANJUTAN]`**

### **1\. Perbandingan Arsitektur**

* **Monolith Engine:** Seluruh komponen aplikasi (Auth, Order, Inventory) digabungkan dalam satu basis kode dan satu proses eksekusi. Mudah di-deploy di awal, tetapi sulit dikembangkan saat tim membesar.  
* **Microservices:** Aplikasi dipecah menjadi layanan-layanan independen kecil yang berkomunikasi via HTTP API atau Message Broker (RabbitMQ/Kafka). Skalabilitas tinggi tetapi memiliki kompleksitas operasional yang besar.

---

## **Bab 38: Sistem Transaksi Terdistribusi & Transaksi Aman Server `[WAJIB]`**

### **1\. Konsep Kebenaran Harga di Server (*Server-Truth Pricing*)**

**PERHATIAN (Aturan Kritis Transaksi POS):**  
Klien/Frontend **TIDAK BOLEH** mengirimkan harga total atau harga satuan barang dalam payload transaksi HTTP. Klien HANYA mengirimkan ID Produk dan Jumlah (*Quantity*). Server harus mengambil harga aktual dari database untuk mencegah manipulasi data dari sisi klien.

### **2\. Kode Transaksi Database (PostgreSQL / Prisma) \[Diperiksa tekstual\] \[Diperiksa sintaksis\]**

```js
import { PrismaClient } from '@prisma/client';
const prisma = new PrismaClient();

export async function prosesTransaksiAman(items) {
  // Gunakan Database Transaction untuk menjamin ACID Compliance
  return await prisma.$transaction(async (tx) => {
    let totalTransaksi = 0;
    const detailTransaksi = [];

    for (const item of items) {
      // 1. Ambil data harga aktual dari Server Database (Server-Truth)
      const produk = await tx.product.findUnique({
        where: { id: item.productId }
      });

      if (!produk) {
        throw new Error(`Produk dengan ID ${item.productId} tidak ditemukan.`);
      }

      // 2. Validasi stok produk aman dari race-condition
      if (produk.stock < item.quantity) {
        throw new Error(`Stok produk ${produk.name} tidak mencukupi.`);
      }

      // 3. Potong stok produk di database
      await tx.product.update({
        where: { id: item.productId },
        data: { stock: produk.stock - item.quantity }
      });

      const subtotal = Number(produk.price) * item.quantity;
      totalTransaksi += subtotal;

      detailTransaksi.push({
        productId: item.productId,
        quantity: item.quantity,
        priceAtPurchase: produk.price
      });
    }

    // 4. Catat Header Transaksi
    const transaksiBaru = await tx.transaction.create({
      data: {
        totalAmount: totalTransaksi,
        items: {
          createMany: {
            data: detailTransaksi
          }
        }
      }
    });

    return transaksiBaru;
  });
}
```

---

## **Bab 39: Proyek Akhir: Production-Ready Fullstack POS System `[WAJIB]`**

### **1\. Deskripsi Proyek Akhir**

Membangun sistem *Point of Sale* (POS) fullstack tingkat produksi yang terintegrasi penuh:

* **Backend:** Express.js \+ PostgreSQL \+ Prisma ORM dengan Autentikasi JWT dan transaksi database ACID.  
* **Frontend:** React.js / Next.js dengan state management terisolasi dan sistem pembacaan barcode/input cepat.  
* **Deployment:** Dokumen Docker-Compose, disajikan via Nginx Reverse Proxy dengan TLS/SSL di OS Ubuntu Linux.

### **2\. Rubrik Evaluasi Kelulusan Proyek Akhir**

- [ ] **Keamanan:** Memenuhi validasi *Server-Truth* harga produk.  
- [ ] **Konkurensi:** Tidak terjadi kerentanan *race-condition* saat penurunan stok secara bersamaan.  
- [ ] **Performa:** Skala pengujian API menghasilkan batas latensi `< 200ms` untuk rute transaksi.  
- [ ] **Infrastruktur:** Aplikasi berjalan di container Docker dan dapat dipulihkan otomatis oleh PM2 / Docker Daemon.

---

## **BAGIAN PENUTUP**

### **1\. Glosarium Istilah**

* **ACID (Atomicity, Consistency, Isolation, Durability):** Empat properti utama yang menjamin keandalan transaksi database.  
* **CORS (Cross-Origin Resource Sharing):** Mekanisme keamanan browser untuk membatasi permintaan HTTP lintas domain.  
* **Idempotent:** Sifat operasi API di mana eksekusi berulang dengan masukan yang sama tidak mengubah status akhir sistem melebihi panggilan pertama.  
* **Server-Truth:** Prinsip arsitektur di mana validasi logika bisnis, perhitungan uang, dan penetapan status data sepenuhnya dikuasai oleh backend server, bukan frontend client.

### **2\. Cheat Sheet Perintah Bash Ubuntu & Git**

```
# --- PERINTAH BASH UBUNTU ---
# Melihat penggunaan disk dan memori sistem
df -h
free -m

# Mengubah hak akses berkas (Read, Write, Execute)
chmod 755 script.sh

# Memeriksa port yang terbuka dan listening
sudo netstat -tulpn | grep :3000

# --- PERINTAH GIT ---
# Membatalkan commit terakhir tanpa menghapus perubahan kode
git reset --soft HEAD~1

# Stash perubahan lokal sementara waktu
git stash
git stash pop
```

### **3\. Referensi Resmi & Bibliografi**

1. Mozilla Developer Network (MDN). *Web Docs: HTML, CSS, and JavaScript Tutorials*. https\://developer.mozilla.org/  
2. Node.js Documentation. *Node.js v20 Long Term Support API Reference*. https\://nodejs.org/docs/  
3. PostgreSQL Global Development Group. *PostgreSQL 16 Documentation*. https\://www\.postgresql.org/docs/  
4. React Documentation. *React Reference: Hooks and Architecture*. https\://react.dev/  
5. OWASP Foundation. *OWASP Top Ten Web Application Security Risks*. https\://owasp.org/Top10/

### **4\. Indeks Istilah**

* Async/Await, 12, 13  
* Bcrypt, 22  
* Containerization, 33  
* Docker, 33, 39  
* Express.js, 17, 18, 39  
* Flexbox, 3, 7  
* Grid CSS, 4, 7  
* HTTPS, 1, 35  
* JWT (JSON Web Token), 22, 39  
* Next.js, 30, 31  
* PostgreSQL, 19, 20, 38  
* React.js, 25, 26, 27, 32  
* Server-Truth, 24, 38, 39  
* Zod Schema, 28

### **5\. Lembar Cek List Kompetensi Industri**

```
[ ] Memahami Arsitektur Client-Server & Protokol HTTP
[ ] Menguasai HTML5 Semantik dan Aksesibilitas Web (a11y)
[ ] Mahir Tata Letak CSS Flexbox & CSS Grid Systems
[ ] Menguasai Manajemen Versi Kode dengan Git & GitHub Workflow
[ ] Memahami JavaScript ES6+, Asynchronous Promise, & Async/Await
[ ] Mampu Membangun RESTful API Berbasis Node.js & Express.js
[ ] Menguasai Pemodelan Database PostgreSQL & Operasi ORM
[ ] Menerapkan Autentikasi JWT & Hashing Kata Sandi Terenkripsi
[ ] Memahami Prinsip Keamanan Web OWASP & Mitigasi Vulnerability
[ ] Mampu Membangun Aplikasi Frontend SPA/SSR Berbasis React / Next.js
[ ] Menguasai Konteinerisasi Docker & Web Server Hardening Nginx
[ ] Menerapkan Arsitektur Transaksi Aman Berprinsip Server-Truth
```

