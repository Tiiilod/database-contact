<img width="497" height="1035" alt="Screenshot 2026-05-13 090456" src="https://github.com/user-attachments/assets/800deba4-89a9-4967-b118-73fb4f787001" />




apliaksidatabese

🗂️ Aplikasi Database SQLite Proyek Flutter sederhana untuk mengelola data menggunakan SQLite (sqflite) dengan menytimpan data nomor telepon dan nama. Aplikasi ini menunjukkan implementasi CRUD (Create, Read, Update, Delete) dengan database lokal, cocok untuk belajar dasar integrasi database di Flutter.

🚀 Fitur Tambah data baru ke database.

Lihat daftar data yang tersimpan.

Edit data yang sudah ada.

Hapus data dari database.

Database otomatis dibuat saat pertama kali aplikasi dijalankan.

📂 Struktur Proyek Code apliaksidatabese/ │── lib/ │ ├── main.dart # Entry point aplikasi │ ├── db_instance.dart # Setup & koneksi SQLite │ ├── data_model.dart # Model data │ ├── home_page.dart # Tampilan daftar data │ ├── add_edit_page.dart # Form tambah/edit data │── pubspec.yaml # Dependencies Flutter │── README.md # Dokumentasi proyek ⚙️ Instalasi Clone repository:

bash git clone https://github.com/tiiilod/database-contact.git cd database-contact/database-sqlite Install dependencies:

bash flutter pub get Jalankan aplikasi:

bash flutter run 📦 Dependencies sqflite – SQLite untuk Flutter

path_provider (pub.dev in Bing) – Lokasi penyimpanan database


