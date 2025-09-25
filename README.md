# AttendanceHub  
> An attendance management system built with **Laravel** and **Livewire** for tracking attendance, check-ins/check-outs, and absences — keeping records organized and simplifying attendance management.

---

## Features
- Feature 1
- Feature 2
- Feature 3

---

## Tech Stack
- Laravel ^10.x  
- PHP ^8.x  
- Livewire ^3.x (or 2.x depending on your version)  
- Alpine.js (bundled with Livewire)  
- MySQL
- TailwindCSS

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


