# Backend (BE)

IntroductionProyek Backend ini dibuat menggunakan bahasa pemrograman Go dengan framework Raiden. Tujuan dari proyek ini adalah untuk menyediakan layanan backend yang dapat menangani permintaan dari aplikasi CMS dan Mobile dengan performa tinggi dan skalabilitas yang baik.

Teknologi yang Digunakan

Bahasa Pemrograman: Go

Framework: Raiden

Database: Supabase (PostgreSQL)

Lainnya: Supabase SDK untuk Go

Struktur folder
├── cmd
│   └── main.go         # Entry point aplikasi
├── internal
│   ├── config          # Konfigurasi aplikasi
│   ├── handlers        # Handler untuk endpoint API
│   ├── models          # Definisi model data
│   └── services        # Logika bisnis utama
├── pkg
│   └── utils           # Fungsi utilitas
└── go.mod              # File dependensi Go
