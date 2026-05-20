# School Payment System

> ⚠️ **ARCHIVED** — Built for a vocational school competency exam (UKOM), 2023.

A simple PHP-based school tuition (SPP) payment management system with a companion Java NetBeans desktop app.

## ✨ Features

- **Student Management** — Add, edit, delete student records
- **Payment Recording** — Record and track tuition payments
- **Payment Reports** — Generate payment reports and summaries
- **Class Management** — Organize students by class
- **Authentication** — Simple login system for admin/staff access

## 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| PHP | Server-side scripting (web version) |
| Java (NetBeans) | Desktop application version |
| MySQL | Database |
| HTML/CSS | Frontend (no framework, plain) |
| Bootstrap | Basic styling template |

## 📂 Structure

```
index.php        Login page
register.php     Registration
koneksi.php      Database connection
logout.php       Logout
dashboard.php    Admin dashboard
laporan.php      Payment reports
siswa/           Student management
kelas/           Class management
spp/             Tuition fee management
petugas/         Staff management
transaksi/       Payment transactions
lsp/             Java NetBeans desktop app version
template/        Layout templates
inc/             Includes and configs
```

Note: The `lsp/` folder contains a Java NetBeans desktop application version of the same system.

## 🚀 Running It

Requirements: PHP 7+, MySQL, Apache/XAMPP

```
git clone https://github.com/Lenxza1/School-Payment-System.git
```

Import the database, update `koneksi.php` with your credentials, and serve with XAMPP.

## 📄 License

Archived for educational and portfolio purposes.
