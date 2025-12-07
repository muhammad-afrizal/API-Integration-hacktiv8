# API Integration Hacktiv8 - Gemini Flash API Server

## Deskripsi
Projek ini adalah server Node.js yang mengintegrasikan Google's Gemini 2.5 Flash API untuk memproses berbagai jenis input seperti teks, gambar, dokumen, dan audio. Server ini menyediakan endpoint-endpoint RESTful untuk berinteraksi dengan model AI.

## Struktur File
- `index.js`: Berisi logika utama aplikasi Express dan integrasi dengan Gemini AI
- `.env`: File konfigurasi untuk menyimpan variabel lingkungan dan kunci API
- `package.json`: Definisi dependensi dan skrip aplikasi
- `README.md`: Dokumentasi ini

## Fitur Utama
- Endpoint REST untuk berbagai jenis input (teks, gambar, dokumen, audio)
- Upload file dengan multer
- Integrasi dengan model Gemini 2.5 Flash
- Penanganan error yang baik
- Konfigurasi melalui environment variables

## Teknologi yang Digunakan
- Node.js
- Express
- Google's Gemini 2.5 Flash API
- Multer (untuk upload file)
- fs/promises (untuk operasi file)

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
Server berjalan di `http://localhost:3000` dan menyediakan berbagai endpoint untuk berinteraksi dengan model Gemini.