# CBT BIMBEL ZIKIE

Proyek React + Vite yang disiapkan dari kode aplikasi yang diberikan.

## Menjalankan di komputer (opsional)
1. Instal Node.js versi LTS.
2. Buka terminal di folder proyek.
3. Jalankan `npm install`.
4. Jalankan `npm run dev`.

## Deploy melalui Vercel
- Framework Preset: Vite
- Build Command: `npm run build`
- Output Directory: `dist`
- Root Directory: `./`

## Catatan penting
- Kode masih memakai Supabase URL dan publishable key dari file sumber.
- Jangan pernah menambahkan `service_role` key ke kode browser atau GitHub.
- Pastikan Row Level Security (RLS) dan policies sudah benar untuk semua tabel sebelum membuka aplikasi untuk umum.
- Skema yang disertakan di dalam aplikasi menggunakan kolom `students.password`; tinjau desain autentikasi dan jangan menyimpan password siswa dalam bentuk teks biasa.
- File gambar kop surat `/image_3fe900.png` tidak disertakan pada unggahan awal. Default gambar dikosongkan; unggah kop/logo dari pengaturan aplikasi jika diperlukan.
- Nama aplikasi diubah menjadi CBT BIMBEL ZIKIE dan kelas warna hijau antarmuka diganti ke indigo. Identitas institusi MIN 4 MAGELANG pada pengaturan sekolah tidak otomatis dihapus.
