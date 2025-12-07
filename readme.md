# Tugas Sesi 4 Hacktiv8 - AI Productivity and AI API Integration for Developers

## Deskripsi
Projek ini merupakan tugas dari sesi 4 pada kursus Hacktiv8 berjudul "AI Productivity and AI API Integration for Developers". Projek ini berfokus pada integrasi API dan penggunaan layanan AI dari Google's Gemini 2.5 Flash.

## Tujuan
- Mengintegrasikan API Google Gemini ke dalam aplikasi Node.js
- Membangun server yang dapat memproses berbagai jenis input (teks, gambar, dokumen, audio)
- Membuat endpoint-endpoint RESTful untuk berinteraksi dengan model AI
- Memahami konsep integrasi AI dalam aplikasi web

## Teknologi yang Digunakan
- Node.js
- Express
- Google's Gemini 2.5 Flash API
- Multer (untuk upload file)
- fs/promises (untuk operasi file)

## Fitur Utama
- Endpoint untuk memproses teks
- Endpoint untuk memproses gambar
- Endpoint untuk memproses dokumen
- Endpoint untuk memproses audio
- Upload file dengan multer
- Penanganan error yang baik

## Instalasi
1. Clone repository ini
2. Inisialisasi project dan install dependensi:
   ```
   npm init -y
   npm install express dotenv @google/genai multer
   ```
3. Buat file `.env` di root direktori dan tambahkan kunci API Gemini Anda:
   ```
   API_KEY=your_api_key_here
   ```
4. Jalankan server: `node index.js`

## Endpoint
Server berjalan di `http://localhost:3000` dan menyediakan berbagai endpoint untuk berinteraksi dengan model Gemini. Dapat dijalankan 