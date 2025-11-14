# Tugas Tracker - Frontend

## Deskripsi Project
Website Tugas Tracker adalah aplikasi untuk membantu mahasiswa mengelola tugas kuliah mereka. Aplikasi ini memungkinkan mahasiswa untuk:
- Mengelola daftar mata kuliah (CRUD)
- Mengelola tugas untuk setiap mata kuliah (CRUD)
- Melacak status pengerjaan tugas (Belum Dikerjakan, Sedang Dikerjakan, Selesai)

## Tech Stack
- **Frontend Framework:** React.js
- **Styling:** CSS / Tailwind CSS
- **API:** RESTful API (akan terhubung dengan backend)

## Struktur Folder
Pekan-Ristek-Final-Project-Front-End/
├── public/              # File statis (HTML, favicon, dll)
│   ├── index.html      # File HTML utama
│   └── ...
├── src/                # Source code utama
│   ├── components/     # Komponen React yang reusable
│   │   ├── CourseCard.js       # Card untuk menampilkan mata kuliah
│   │   ├── TaskCard.js         # Card untuk menampilkan tugas
│   │   ├── StatusBadge.js      # Badge status tugas
│   │   └── ...
│   ├── pages/          # Halaman-halaman aplikasi
│   │   ├── HomePage.js         # Halaman utama
│   │   ├── CoursePage.js       # Halaman daftar mata kuliah
│   │   ├── CourseDetail.js     # Halaman detail mata kuliah
│   │   ├── TaskPage.js         # Halaman daftar tugas
│   │   └── ...
│   ├── services/       # Service untuk komunikasi dengan API
│   │   └── api.js      # Konfigurasi dan fungsi API calls
│   ├── App.js          # Komponen utama aplikasi
│   ├── index.js        # Entry point aplikasi
│   └── App.css         # Styling global
├── package.json        # Dependencies dan scripts
└── README.md           # Dokumentasi project

## Penjelasan Struktur Folder

### **`public/`**
Berisi file-file statis yang tidak diproses oleh webpack. File index.html adalah template HTML utama aplikasi.

### **`src/`**
Folder ini berisi semua source code aplikasi React.

### **`src/components/`**
Berisi komponen-komponen React yang dapat digunakan kembali (reusable components):
- **CourseCard.js**: Komponen untuk menampilkan card mata kuliah
- **TaskCard.js**: Komponen untuk menampilkan card tugas
- **StatusBadge.js**: Komponen badge untuk status tugas (Belum/Sedang/Selesai)

### **`src/pages/`**
Berisi komponen-komponen yang merepresentasikan halaman-halaman utama aplikasi:
- **HomePage.js**: Halaman awal dengan overview semua tugas
- **CoursePage.js**: Halaman daftar semua mata kuliah
- **CourseDetail.js**: Halaman detail mata kuliah beserta tugas-tugasnya
- **TaskPage.js**: Halaman daftar semua tugas

### **`src/services/`**
Berisi kode untuk berkomunikasi dengan backend API:
- **api.js**: Fungsi-fungsi untuk fetch data, post data, update, dan delete

### **`src/App.js`**
Komponen utama yang mengatur routing dan struktur aplikasi secara keseluruhan.

### **`src/index.js`**
Entry point aplikasi, file pertama yang dijalankan saat aplikasi dimulai.

### **`package.json`**
File konfigurasi yang berisi informasi tentang dependencies, scripts, dan metadata project.

## Cara Menjalankan Project

1. Clone repository ini:
bash
   git clone https://github.com/noeandrew-jm/Pekan-Ristek-Final-Project-Front-End.git

2. Masuk ke folder project:
bash
   cd Pekan-Ristek-Final-Project-Front-End

3. Install dependencies:
bash
   npm install

4. Jalankan aplikasi:
bash
   npm start

5. Buka browser dan akses http://localhost:3000

## Status Development
- [x] Checkpoint 1: Inisialisasi project dan struktur folder
- [ ] Checkpoint 2: Implementasi frontend dengan API RISTEK
- [ ] Checkpoint 3: Integrasi dengan backend sendiri

## Author
**Nama:** Noe Andrew  
**NPM:** [Isi NPM Kamu]  
**Kelas:** [Isi Kelas Kamu]

---
Project ini dibuat untuk memenuhi tugas Final Project Web Development - RISTEK Fasilkom UI 2025
