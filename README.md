
# Project Poliklinik Laravel 9.x

Proyek ini adalah aplikasi berbasis Laravel 9. Dokumentasi ini mencakup langkah-langkah untuk menjalankan proyek.


## Prasyarat

- PHP >= 8.1
- Composer
- MySQL (atau database lainnya yang didukung Laravel)


## Cara Menjalankan Proyek

 1. Clone Repositori Salin repositori ini ke perangkat Anda:
    ```bash
    git clone https://github.com/username/repository-name.git
    cd repository-name
    ```
 2. Instalasi dan konfigurasi 
 a. Instal Dependensi : composer install  
 b. Salin File .env : cp .env.example .env  
 c. Konfigurasi Database, Edit file .env dan sesuaikan pengaturan database:            DB_CONNECTION=mysql DB_HOST=127.0.0.1 DB_PORT=3306 DB_DATABASE=nama_database DB_USERNAME=username_database DB_PASSWORD=password_database  
 d. Generate Application Key: php artisan key:generate

 3. Migrasi Database
    ```bash
    php artisan migrate
    ```
 4. Jalankan Server Lokal
    ```bash
    php artisan serve
    ```
 5. Jalankan TailwindCSS
    ```bash
    npm run dev
    ```
 6. Buka browser dan akses: http://localhost:8000

