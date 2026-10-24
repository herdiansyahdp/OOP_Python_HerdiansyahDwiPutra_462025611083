# 🐍 Python Object-Oriented Programming

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,100:7c3aed&height=200&section=header&text=Python%20OOP%20Projects&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="Python OOP Projects banner"/>
</p>

<p align="center">
  <strong>Kumpulan latihan dan project Python untuk mempelajari konsep Object-Oriented Programming (OOP), dari dasar class dan object hingga penerapan dalam aplikasi web.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Framework-Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/Focus-Object--Oriented%20Programming-7C3AED?style=for-the-badge" alt="OOP"/>
  <img src="https://img.shields.io/badge/Type-Academic%20Projects-2563EB?style=for-the-badge" alt="Academic Projects"/>
</p>

---

## 📖 About This Repository

Repository ini berisi dokumentasi tugas, latihan, dan project dari mata kuliah **Pemrograman Berorientasi Objek (PBO)** menggunakan Python.

Materi disusun secara bertahap untuk memahami cara menyusun program dengan class dan object, mengelola data melalui encapsulation, menerapkan inheritance dan polymorphism, serta menangani kesalahan menggunakan custom exceptions.

Repository ini juga memiliki **Final Project** berupa aplikasi web untuk mengelola pengajuan dokumentasi acara kampus dengan Python dan Flask.

---

## ✨ What's Inside?

| Bagian | Fokus Pembelajaran |
|---|---|
| 📘 Pertemuan 2 | Class, object, constructor, dan instance attributes |
| 🧩 Pertemuan 3 | Instance methods, static methods, dan conditional logic |
| 🪄 Pertemuan 4 | Magic methods seperti `__str__` dan perbandingan object |
| 🔐 Pertemuan 5 | Encapsulation dan pengelolaan akses atribut |
| 🧬 Pertemuan 6 | Inheritance, multiple inheritance, dan Method Resolution Order (MRO) |
| 🔄 Pertemuan 7 | Polymorphism dan method overriding |
| 🛡️ Pertemuan 8 | Custom exceptions dan validasi data |
| 🚀 Final Project | Aplikasi web pengadaan dokumentasi multimedia berbasis Flask |

---

## 🧠 OOP Concepts

### 1. Classes & Objects
Mempelajari cara mendefinisikan class sebagai cetak biru dan membuat object dengan atribut serta perilakunya sendiri.

### 2. Methods & Magic Methods
Menggunakan instance method, static method, serta magic methods untuk mengatur representasi object dan perilaku perbandingan.

### 3. Encapsulation
Membatasi akses langsung ke atribut tertentu dan mengatur aksesnya melalui method atau property.

### 4. Inheritance
Mewariskan atribut dan method dari class induk ke class turunan, termasuk memahami multiple inheritance dan urutan pencarian method melalui MRO.

### 5. Polymorphism
Menggunakan antarmuka method yang sama dengan implementasi berbeda sesuai jenis object.

### 6. Custom Exceptions
Membuat exception khusus untuk menangani kesalahan validasi sesuai kebutuhan aplikasi.

---

## 🚀 Final Project — Sistem Pengadaan Dokumentasi Multimedia

Final project repository ini adalah aplikasi web untuk membantu UPT Multimedia and Public Relations mengelola pengajuan kebutuhan dokumentasi acara kampus.

Aplikasi dibuat menggunakan **Python, Flask, HTML/Jinja2, CSS, JavaScript, dan penyimpanan JSON**.

### Fitur utama

- 🔑 Login admin dan logout
- 📊 Dashboard daftar acara
- 🗓️ Tambah, edit, dan hapus data acara
- 📸 Pengelolaan layanan Fotografi, Videografi, Broadcast, Drone, dan LED
- 👥 Database anggota beserta status tugas
- 🧰 Pendataan petugas dan peralatan pada setiap layanan
- 📚 Riwayat acara dan tampilan ringkasan
- 💾 Penyimpanan data acara dan anggota ke file JSON
- 🛡️ Validasi input serta custom exceptions

### Konsep OOP dalam Final Project

Project ini menggabungkan beberapa materi yang dipelajari, seperti **abstraction, inheritance, polymorphism, encapsulation, magic methods, static methods, dan custom exceptions**. Pemisahan file `app.py` dan `models.py` juga membantu memisahkan routing web dari model serta logika aplikasi.

---

## 🛠️ Technologies

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white" alt="JSON"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
</p>

---

## 📁 Repository Structure

```text
OOP_Python_HerdiansyahDwiPutra_462025611083/
│
├── Pertemuan_2/
│   └── main.py
│
├── Pertemuan_3/
│   ├── main.py
│   └── requirements.txt
│
├── Pertemuan_4/
│   └── main.py
│
├── Pertemuan_5/
│   └── main.py
│
├── Pertemuan_6/
│   └── inheritance_lab.py
│
├── Pertemuan_7/
│   └── polymorphism.py
│
├── Pertemuan_8/
│   └── exception_handling_lab.py
│
├── FinalProject/
│   ├── app.py
│   ├── models.py
│   ├── requirements.txt
│   ├── README.md
│   ├── templates/
│   ├── static/
│   └── data/                 # Dibuat otomatis saat aplikasi dijalankan
│
├── .gitignore
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone repository

```bash
git clone https://github.com/herdiansyahdp/OOP_Python_HerdiansyahDwiPutra_462025611083.git
cd OOP_Python_HerdiansyahDwiPutra_462025611083
```

### 2. Jalankan latihan per pertemuan

Pastikan Python sudah terpasang. Pilih folder materi yang ingin dipelajari, lalu jalankan file Python-nya.

Contoh:

```bash
python Pertemuan_2/main.py
```

Untuk file latihan lain, ganti path sesuai file yang ingin dijalankan.

### 3. Jalankan Final Project

Masuk ke folder final project:

```bash
cd FinalProject
```

Buat dan aktifkan virtual environment (opsional, tetapi direkomendasikan):

**Windows PowerShell**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**Linux / macOS**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependency:

```bash
pip install -r requirements.txt
```

Jalankan aplikasi:

```bash
python app.py
```

Buka alamat lokal yang ditampilkan oleh Flask di terminal untuk mengakses aplikasi melalui browser.

> **Catatan:** Final Project ini merupakan project pembelajaran. Sebelum digunakan di lingkungan produksi, sesuaikan konfigurasi autentikasi dan secret key, serta gunakan konfigurasi deployment yang aman. Jangan gunakan kredensial contoh untuk deployment publik.

---

## 🎯 Learning Goals

Melalui repository ini, target pembelajaran yang ingin dicapai adalah:

- Memahami prinsip dasar pemrograman berorientasi objek.
- Menyusun class dan object secara terstruktur.
- Menggunakan inheritance dan polymorphism untuk membuat kode lebih fleksibel.
- Menerapkan encapsulation dan validasi untuk menjaga data.
- Menangani error dengan exception yang sesuai.
- Menggabungkan konsep OOP menjadi aplikasi Python yang lebih nyata.
- Membiasakan penggunaan Git dan GitHub sebagai dokumentasi perkembangan belajar.

---

## 🔭 Future Improvements

Beberapa ide pengembangan lanjutan untuk repository dan Final Project:

- Menambahkan unit test untuk materi latihan dan model aplikasi.
- Memindahkan penyimpanan JSON ke database.
- Menggunakan environment variables untuk secret key dan kredensial.
- Menambahkan role dan pengelolaan akun admin.
- Membuat dokumentasi screenshot setiap fitur aplikasi.
- Menambahkan fitur laporan serta penyaringan data acara.

---

## 👨‍💻 Author

<p align="center">
  <strong>Herdiansyah Dwi Putra</strong><br/>
  Mahasiswa Teknik Informatika
</p>

<p align="center">
  <a href="https://github.com/herdiansyahdp">
    <img src="https://img.shields.io/badge/GitHub-herdiansyahdp-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile"/>
  </a>
</p>

---

## ⭐ Support

Repository ini merupakan dokumentasi perjalanan belajar Python dan Object-Oriented Programming.

Kalau project ini bermanfaat, jangan lupa memberikan ⭐ pada repository!

<p align="center">
  <i>Learn step by step. Build with objects. Improve with practice. 🐍</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,100:1e1b4b&height=100&section=footer" alt="Footer banner"/>
</p>
