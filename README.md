# Laravel Backend - Food Market

This repository contains the backend for the **Food Market** application, built with Laravel and integrated with Midtrans for payment gateway support.

## 🚀 Features

- Laravel 8.x with Jetstream (Livewire stack)
- Secure authentication using Laravel Sanctum
- Seamless integration with Midtrans payment gateway
- Modular structure and API-ready
- CORS and RESTful API support

## ⚙️ Requirements

- PHP >= 7.3
- Composer
- MySQL or compatible database
- Node.js & npm

## 🧭 Installation

Clone the repo and set up the Laravel project:

```bash
git clone https://github.com/your-username/food-market-laravel.git
cd food-market-laravel
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
```

## 💡 Frontend Assets

To install JavaScript dependencies and compile frontend assets:

```bash
npm install
npm run dev
```

## 💳 Midtrans Integration

Register at Midtrans to get your server key.

Update your `.env` with the following:

```env
MIDTRANS_SERVER_KEY=your_server_key
MIDTRANS_IS_PRODUCTION=false
```

## 🛠️ Scripts

- `php artisan serve` – Run Laravel dev server  
- `php artisan migrate` – Run database migrations  
- `php artisan db:seed` – Seed sample data  
- `npm run dev` – Compile frontend assets (development)  
- `npm run prod` – Compile frontend assets (production)  

## 📁 Directory Overview

- `app/` – Core application logic  
- `routes/` – API and web route definitions  
- `resources/` – Blade views and frontend assets  
- `config/` – App configuration  
- `database/` – Migrations and seeders  

## 📜 License

This project is licensed under the MIT License.
