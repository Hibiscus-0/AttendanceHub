# AttendanceHub  
> An attendance management system built with **Laravel** and **Livewire** for tracking attendance, check-ins/check-outs, and absences — keeping records organized and simplifying attendance management.

---

## Features
- Feature 1
- Feature 2
- Feature 3

---

## 🛠 Tech Stack  
![Laravel](https://img.shields.io/badge/Laravel-v10.x-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-v8.x-777BB4?logo=php&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-v3.x-4E56A6?logo=laravel&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?logo=alpine.js&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwind-css&logoColor=white)

---

## Requirements
Make sure you have the following installed:  
- PHP >= 8.x  
- Composer  
- Node.js & NPM  
- MySQL

---

## Installation

### 1. Clone the repository
```bash
git clone hhttps://github.com/Hibiscus-0/AttendanceHub.git
cd AttendanceHub
```

### 2. Install PHP Dependencies
```bash
composer install
```

### 3. Install Node Dependencies
```bash
npm install
```

### 4. Environment Setup
Copy `.env.example` to `.env` and configure:
```bash
cp .env.example .env
php artisan key:generate
```

### 5. Database Setup
- Create a database
- Update `.env` DB settings  
- Run migrations
```bash
php artisan migrate
```
### 6. Build Frontend Assets
```bash
npm run dev
```
(or `npm run build` for production)


