# 🩺 BumilFit

> **Personal Pregnancy Companion for Healthy Mother & Stunting-Free Generation**

[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com/BrezaMedico/bumilfit)
[![Category](https://img.shields.io/badge/Category-ITechnoCup%202026-blue?style=for-the-badge)](https://github.com/BrezaMedico/bumilfit)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/licenses/MIT)

**Submission ITechnoCup 2026 – Web Development**

**GitHub Repository:** https://github.com/BrezaMedico/bumilfit  
**Live Demo:** [Sesuaikan dengan link demo yang sudah di-hosting]

---

## 📑 Daftar Isi

- [👥 Tim Developer](#-tim-developer)
- [🎯 Tentang Proyek](#-tentang-proyek)
  - [Latar Belakang](#latar-belakang)
  - [Solusi yang Ditawarkan](#solusi-yang-ditawarkan)
  - [Tujuan Proyek](#tujuan-proyek)
- [✨ Fitur Unggulan](#-fitur-unggulan)
  - [Fitur Utama](#fitur-utama)
  - [Fitur Tambahan](#fitur-tambahan)
- [📸 Demo & Screenshot](#-demo--screenshot)
- [🛠️ Teknologi](#️-teknologi)
  - [Tech Stack](#tech-stack)
  - [Alasan Pemilihan Teknologi](#alasan-pemilihan-teknologi)
  - [Dependencies Utama](#dependencies-utama)
- [🏗️ Arsitektur Sistem](#️-arsitektur-sistem)
  - [System Architecture](#system-architecture)
  - [Database Schema](#database-schema)
  - [Folder Structure](#folder-structure)
- [⚙️ Instalasi & Setup](#️-instalasi--setup)
- [🚀 Penggunaan](#-penggunaan)
- [📚 API Documentation](#-api-documentation)
- [🧪 Testing](#-testing)
- [📄 Lisensi](#-lisensi)

---

# 👥 Tim Developer

| Nama | Role | GitHub |
|---|---|---|
| **Breza Artha Medico** | Full Stack Developer | https://github.com/BrezaMedico |
| **Halipah Mubarok** | Technical Writer & UI/UX Designer | https://github.com/Shiin14 |
| **M. Fayyadh Al Barr H** | System Analyst & UI/UX Designer | https://github.com/Jaxc5 |

---

# 🎯 Tentang Proyek

## Latar Belakang

Stunting merupakan salah satu tantangan kesehatan di Indonesia. Upaya pencegahan stunting perlu dilakukan sejak periode **1.000 Hari Pertama Kehidupan (HPK)**, termasuk sejak masa kehamilan.

Dalam praktiknya, ibu hamil dapat menghadapi beberapa permasalahan, seperti:

- Kurangnya kepatuhan dalam mengkonsumsi Tablet Tambah Darah (TTD), vitamin, dan suplemen.
- Informasi mengenai kehamilan dan nutrisi yang tidak terstruktur serta adanya informasi atau mitos yang dapat menyesatkan.
- Jadwal pemeriksaan kehamilan atau **Antenatal Care (ANC)** yang dapat terlewat.
- Kesulitan dalam memantau aktivitas kesehatan dan kebutuhan nutrisi selama kehamilan.

Berdasarkan permasalahan tersebut, dibutuhkan sebuah platform digital yang dapat membantu ibu hamil dalam memantau aktivitas kesehatan, memperoleh informasi, mengingatkan jadwal penting, serta mendukung pemenuhan kebutuhan nutrisi selama kehamilan.

## Solusi yang Ditawarkan

**BumilFit** merupakan aplikasi web yang dirancang sebagai **personal pregnancy companion** untuk membantu ibu hamil menjalani masa kehamilan dengan lebih terarah.

BumilFit menyediakan berbagai fitur seperti:

- Smart Health Reminder berbasis To-Do List.
- Pengingat konsumsi TTD, vitamin, dan suplemen.
- Pengingat minum air dan aktivitas olahraga ringan.
- Pengingat pemeriksaan kehamilan atau ANC.
- Kalkulator kehamilan dan Estimated Due Date (EDD).
- Kalkulator kebutuhan gizi harian.
- Cek kandungan gizi makanan/minuman melalui foto atau kamera.
- Konsultasi dengan dokter.
- Pembelian produk kesehatan seperti vitamin, suplemen, dan obat melalui aplikasi.
- Notifikasi pengingat melalui WhatsApp.
- AI Chatbot untuk memberikan informasi umum seputar kehamilan dan kesehatan.

BumilFit diharapkan dapat **berkontribusi dalam upaya pencegahan stunting sejak masa kehamilan** dengan membantu meningkatkan kesadaran dan keteraturan ibu hamil dalam menjaga kesehatan serta memenuhi kebutuhan nutrisi.

## Tujuan Proyek

BumilFit dikembangkan dengan tujuan untuk:

1. Membantu ibu hamil menerapkan pola hidup sehat dan memenuhi kebutuhan nutrisi harian secara lebih terarah.
2. Membantu mengingatkan berbagai aktivitas kesehatan selama kehamilan.
3. Membantu ibu hamil memantau konsumsi TTD, vitamin, suplemen, air, dan aktivitas fisik ringan.
4. Membantu ibu hamil mengetahui usia kehamilan dan perkiraan tanggal persalinan (EDD).
5. Memberikan akses informasi kesehatan dan nutrisi yang lebih mudah.
6. Mendukung upaya pencegahan stunting sejak masa kehamilan.
7. Menghubungkan pengguna dengan layanan konsultasi dokter dan produk kesehatan.

### Sustainable Development Goals (SDGs)

#### SDG 8 — Decent Work and Economic Growth

BumilFit dapat mendukung ekosistem ekonomi digital melalui keterlibatan UMKM, apotek lokal, penyedia produk kesehatan, serta layanan pengiriman atau kurir.

#### SDG 9 — Industry, Innovation and Infrastructure

BumilFit memanfaatkan teknologi digital dalam bidang HealthTech melalui fitur seperti smart reminder, kalkulator EDD, kalkulator gizi, AI, serta transaksi produk kesehatan secara online.

#### SDG 11 — Sustainable Cities and Communities

BumilFit berupaya menyediakan layanan kesehatan digital yang lebih mudah diakses oleh ibu hamil dan keluarga.

---

# ✨ Fitur Unggulan

## Fitur Utama

| Fitur | Deskripsi |
|---|---|
| 📝 **Smart Health Reminder** | To-Do List untuk membantu pengguna mencatat dan menyelesaikan aktivitas kesehatan seperti konsumsi TTD, vitamin, suplemen, minum air, olahraga ringan, dan pemeriksaan ANC. |
| 🤰 **Kalkulator Kehamilan & EDD** | Menampilkan usia kehamilan dan Estimated Due Date (EDD) berdasarkan usia kehamilan yang dimasukkan pengguna saat melakukan registrasi. |
| 🥗 **Kalkulator Gizi** | Membantu menghitung kebutuhan nutrisi harian pengguna selama masa kehamilan. |
| 📸 **Cek Gizi** | Membantu pengguna memperoleh informasi mengenai kandungan gizi makanan atau minuman melalui upload foto atau pemindaian menggunakan kamera. |
| 👨‍⚕️ **Konsultasi Dokter** | Menyediakan akses untuk melakukan konsultasi dengan dokter. |
| 🤖 **AI Chatbot** | Membantu memberikan informasi umum seputar kehamilan dan kesehatan menggunakan teknologi AI. |

> **Catatan:** Informasi dari AI Chatbot bersifat umum dan tidak menggantikan diagnosis maupun konsultasi langsung dengan tenaga kesehatan.

## Fitur Tambahan

### Action-Oriented Tracking

Pengguna tidak hanya mendapatkan informasi, tetapi juga dapat melakukan tracking aktivitas kesehatan melalui sistem To-Do List dan menandai aktivitas yang telah selesai.

### Early Stunting Prevention Focus

Fitur-fitur BumilFit dirancang untuk membantu meningkatkan perhatian terhadap kesehatan dan nutrisi sejak masa kehamilan sebagai bagian dari upaya pencegahan stunting.

### Lightweight & Responsive

Antarmuka dirancang agar mudah digunakan, ringan, dan responsif pada berbagai ukuran perangkat.

### Sistem Subscription

BumilFit menggunakan model monetisasi **Hybrid Monetization**, yaitu kombinasi antara komisi transaksi dan layanan berlangganan.

| Paket | Benefit |
|---|---|
| **Basic** | Konsultasi dokter gratis selama 1 minggu |
| **Pro** | Konsultasi dokter gratis selama 1 bulan |
| **Premium** | Konsultasi dokter gratis selama 3 bulan + cek gizi menggunakan kamera/upload foto |
| **Premium+** | Konsultasi dokter gratis selama 9 bulan + cek gizi menggunakan kamera/upload foto |

### Model Monetisasi

Pendapatan BumilFit dapat berasal dari:

- Komisi transaksi pembelian TTD, vitamin, suplemen, dan produk kesehatan melalui partner.
- Biaya layanan/platform yang berkaitan dengan proses logistik atau pengiriman.
- Pendapatan dari paket subscription/premium.

---

# 📸 Demo & Screenshot

## Live Demo

**URL:** [Sesuaikan dengan link demo yang sudah di-hosting]

## Screenshot Aplikasi

### Halaman Utama

![Homepage](assets/screenshots/homepage.png)

[Sesuaikan dengan path screenshot Homepage yang digunakan pada repository]


### Smart Health Reminder

![Smart Health Reminder](assets/screenshots/reminder.png)

[Sesuaikan dengan path screenshot Smart Health Reminder yang digunakan pada repository]


### Kalkulator Gizi & Cek Gizi

![Nutrition Calculator](assets/screenshots/nutrition-calculator.png)

[Sesuaikan dengan path screenshot Kalkulator Gizi yang digunakan pada repository]

### Konsultasi Dokter

![Doctor Consultation](assets/screenshots/doctor-consultation.png)

[Sesuaikan dengan path screenshot Konsultasi Dokter yang digunakan pada repository]

## Video Demo

**Video Demo:** [Sesuaikan dengan link video demo yang sudah di-upload]

---

# 🛠️ Teknologi

## Tech Stack

### Frontend

| Teknologi | Penggunaan |
|---|---|
| React | Library utama untuk membangun antarmuka aplikasi |
| TypeScript | Type safety pada pengembangan aplikasi |
| Vite | Development server dan build tool |
| Tailwind CSS | Styling dan responsive UI |
| Zustand | Global state management |
| Lucide React | Icon pada antarmuka |
| Canvas Confetti | Efek visual pada interaksi tertentu |

### Backend & API

| Teknologi | Penggunaan |
|---|---|
| Node.js | Runtime backend |
| Express.js | Framework untuk REST API |
| TypeScript | Type safety pada backend |
| Prisma ORM | Interaksi dengan database |
| JWT | Authentication |
| BCrypt | Password hashing |
| Google Gemini API | AI dan fitur berbasis kecerdasan buatan |

### Database

| Teknologi | Penggunaan |
|---|---|
| Neon PostgreSQL | Cloud PostgreSQL database |

### Supporting Tools

| Teknologi | Penggunaan |
|---|---|
| Axios | HTTP Client |
| Zod | Data validation |
| Git | Version control |
| GitHub | Repository dan collaboration |

## DevOps & Tools

| Bagian | Teknologi |
|---|---|
| Version Control | Git & GitHub |
| Deployment | Vercel / Render |
| CI/CD | [Sesuaikan dengan CI/CD yang benar-benar digunakan] |

## Alasan Pemilihan Teknologi

### React + TypeScript

Digunakan untuk membangun antarmuka yang modular, interaktif, dan lebih mudah dipelihara dengan dukungan type safety dari TypeScript.

### Vite

Digunakan sebagai build tool karena menyediakan development environment yang cepat dan proses build yang efisien.

### Tailwind CSS

Digunakan untuk mempercepat proses pengembangan UI serta membantu membuat tampilan yang responsive.

### Node.js + Express.js

Digunakan untuk membangun backend dan RESTful API yang menangani proses autentikasi, data pengguna, transaksi, serta komunikasi dengan database.

### PostgreSQL + Neon

Digunakan sebagai database relasional untuk menyimpan data pengguna, profil kehamilan, aktivitas, transaksi, dan data aplikasi lainnya.

### Prisma ORM

Digunakan untuk mempermudah pengelolaan database dan interaksi antara backend dengan PostgreSQL.

### Zustand

Digunakan untuk mengelola state global aplikasi, termasuk state yang berkaitan dengan shopping cart.

### Google Gemini API

Digunakan untuk mendukung fitur berbasis AI seperti AI Chatbot dan analisis informasi gizi.

## Dependencies Utama
```
{ 
    "dependencies": {
        "react": "^x.x.x",
        "typescript": "^x.x.x",
        "vite": "^x.x.x",
        "tailwindcss": "^x.x.x",
        "zustand": "^x.x.x",
        "axios": "^x.x.x",
        "zod": "^x.x.x",
        "lucide-react": "^x.x.x", 
        "express": "^x.x.x",
        "prisma": "^x.x.x",
        "jsonwebtoken": "^x.x.x", 
        "bcrypt": "^x.x.x" 
    }
 } 
[x.xx.sesuaikan dengan versi]
```
---

# 🏗️ Arsitektur Sistem

## System Architecture

```text
┌──────────────────────────────┐
│          User / Bumil        │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│      React Frontend          │
│      + Tailwind CSS          │
└──────────────┬───────────────┘
               │
               │ REST API
               ▼
┌──────────────────────────────┐
│      Express.js Backend      │
│                              │
│  ┌────────────────────────┐  │
│  │ Authentication / JWT   │  │
│  ├────────────────────────┤  │
│  │ Controllers            │  │
│  ├────────────────────────┤  │
│  │ Services               │  │
│  ├────────────────────────┤  │
│  │ Routes                 │  │
│  └────────────────────────┘  │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│          Prisma ORM          │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│       Neon PostgreSQL        │
│                              │
│  Users / Profiles            │
│  Activities / Orders         │
│  Application Data            │
└──────────────────────────────┘

External Services:
├── Google Gemini API
└── WhatsApp Notification Service
    └── [Sesuaikan dengan service/API WhatsApp yang benar-benar digunakan]

---

## Database Schema

> **Catatan:** Detail ERD/database schema belum tersedia pada dokumentasi yang diberikan.

~~~text
User
 │
 ├── Profile
 │
 ├── Activities
 │
 └── Orders

[Sesuaikan dengan relasi tabel dan model Prisma yang benar-benar digunakan]
~~~


## Folder Structure

~~~text
BumilFit/
├── frontend/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── data/
│       ├── hooks/
│       ├── lib/
│       ├── pages/
│       ├── router/
│       ├── store/
│       ├── App.tsx
│       └── main.tsx
│
├── backend/
│   ├── prisma/
│   └── src/
│       ├── controllers/
│       ├── lib/
│       ├── middlewares/
│       ├── routes/
│       ├── services/
│       ├── app.ts
│       └── server.ts
│
├── .env.example
├── .gitignore
├── package.json
└── README.md
~~~

---

# ⚙️ Instalasi & Setup

## Prerequisites

Pastikan perangkat telah memiliki:

- Node.js v18+ atau v20+
- npm
- Git
- PostgreSQL / Neon PostgreSQL
- API Key Google Gemini


## Langkah Instalasi

### 1. Clone Repository

~~~bash
git clone https://github.com/BrezaMedico/bumilfit.git
cd BumilFit
~~~

### 2. Install Dependencies

~~~bash
cd frontend
npm install
~~~

Kemudian:

~~~bash
cd ../backend
npm install
~~~

### 3. Konfigurasi Environment Variable

Salin template dari `backend/.env.example` ke `backend/.env`:
```env
DATABASE_URL="postgresql://user:password@host:port/database?sslmode=require"
PORT=5000
FRONTEND_URL=http://localhost:5173
JWT_SECRET="your-secret-key-here"
GEMINI_API_KEY="your-gemini-api-key-here"
```

#### Frontend (`frontend/.env`)
Salin template dari `frontend/.env.example` ke `frontend/.env`:
```env
VITE_GEMINI_API_KEY="your-gemini-api-key-here"
```


> **Penting:** Jangan commit file `.env` yang berisi API key, password, JWT secret, atau credential lainnya ke repository.


### 5. Setup Prisma

Masuk ke folder backend:

~~~bash
cd backend
~~~

Generate Prisma Client:

~~~bash
npx prisma generate
~~~

Push database schema:

~~~bash
npx prisma db push
~~~

[Sesuaikan dengan migration command jika implementasi final menggunakan Prisma Migration]

### 6. Jalankan Aplikasi

#### Backend (Development Server):
```bash
cd backend
npm run dev
```

#### Frontend (Development Server):
```bash
cd frontend
npm run dev
```

Kemudian buka aplikasi melalui browser:
http://localhost:5173


---

# 🚀 Penggunaan

## Menjalankan Aplikasi

Setelah frontend dan backend berhasil dijalankan:

1. Buka browser.
2. Akses:
   
   ~~~text
   http://localhost:5173
   ~~~

3. Lakukan registrasi akun.
4. Masukkan data kehamilan yang diperlukan.
5. Gunakan fitur yang tersedia pada dashboard.

## User Guide

### Untuk Pengguna Umum

#### 1. Registrasi

Pengguna melakukan registrasi dengan mengisi:

- Nama
- Email
- Password
- Usia kehamilan saat registrasi
- Riwayat penyakit
- Data lain yang dibutuhkan oleh aplikasi


#### 2. Melihat Informasi Kehamilan

Setelah registrasi, sistem menampilkan:

- Usia kehamilan
- Estimated Due Date (EDD)

Data tersebut ditentukan berdasarkan usia kehamilan yang dimasukkan saat registrasi.

#### 3. Menggunakan Smart Health Reminder

Pengguna dapat melihat aktivitas kesehatan melalui To-Do List, seperti:

- Konsumsi TTD
- Konsumsi vitamin/suplemen
- Minum air
- Olahraga ringan
- Dll

Pengguna dapat menandai aktivitas yang telah selesai.

#### 4. WhatsApp Reminder

Pengguna dapat menerima pengingat aktivitas kesehatan melalui WhatsApp.


#### 5. Kalkulator Gizi

Pengguna dapat menggunakan kalkulator untuk membantu mengetahui kebutuhan nutrisi harian.

#### 6. Cek Gizi

Pengguna dapat:

1. Mengunggah foto makanan/minuman.
2. Menggunakan kamera.
3. Melihat informasi hasil analisis.


#### 7. Konsultasi Dokter

Pengguna dapat mengakses layanan konsultasi dengan dokter melalui aplikasi.


#### 8. Membeli Produk Kesehatan

Pengguna dapat:

1. Memilih produk kesehatan.
2. Memasukkan produk ke keranjang.
3. Melakukan checkout.
4. Menyelesaikan transaksi.


#### 9. Subscription

Pengguna dapat memilih paket premium sesuai kebutuhan:

- Basic
- Pro
- Premium
- Premium+

---

# 📚 API Documentation

## Base URL

### Development

~~~text
http://localhost:5000
~~~

### Production

~~~text
[Sesuaikan dengan Base URL API production yang digunakan]
~~~

## API Endpoints

> Daftar endpoint detail belum tersedia pada dokumentasi yang diberikan. Isi tabel berikut berdasarkan route backend yang benar-benar digunakan.

| Method | Endpoint | Description | Authentication |
|---|---|---|---|
| [Sesuaikan] | [Sesuaikan] | [Sesuaikan] | [Sesuaikan] |
| [Sesuaikan] | [Sesuaikan] | [Sesuaikan] | [Sesuaikan] |
| [Sesuaikan] | [Sesuaikan] | [Sesuaikan] | [Sesuaikan] |
| [Sesuaikan] | [Sesuaikan] | [Sesuaikan] | [Sesuaikan] |

## Example Request

~~~text
[Sesuaikan dengan endpoint API yang benar-benar digunakan]
~~~

Contoh format:

~~~json
{
  "[Sesuaikan dengan field API]": "[Sesuaikan dengan value]"
}
~~~

---

# 📄 Lisensi

Project ini menggunakan **MIT License**.

~~~text
MIT License

Copyright (c) 2026 BumilFit

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
~~~

<div align="center">

## 🤰 BumilFit

**Personal Pregnancy Companion for Healthy Mother & Stunting-Free Generation**

Developed for **ITechnoCup 2026 – Web Development**

**GitHub:** [https://github.com/BrezaMedico/bumilfit](https://github.com/BrezaMedico/bumilfit)

**Email:** [bumilfit@gmail.com](mailto:bumilfit@gmail.com)

**Website:** [Sesuaikan dengan website resmi BumilFit jika tersedia]

---

**© 2026 BumilFit Team. All Rights Reserved.**

</div>

