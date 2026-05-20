# School Payment System

> ⚠️ **ARCHIVED** — This was my very first web development project, created in 2023 when I was just starting my programming journey. The code is rough, the architecture is messy, and that's exactly the point — it shows where I started.

A simple PHP-based school tuition (SPP) payment management system built for a vocational school competency exam (UKOM) project.

## 🕰️ Context

This project marks the **beginning of my programming career**. Looking back, the code is full of rookie mistakes — inline PHP mixed with HTML, no MVC pattern, no framework, plain procedural everything. But that's what makes it special. Every developer starts somewhere, and this is where I started.

Since then I've grown to work with:
- Flutter & Dart for cross-platform mobile apps
- TypeScript & Node.js for backend APIs
- Unity C# for game development
- Modern frameworks like Astro, Next.js, and Express

Compare this project with my later work on [pick-girl-mobile](https://github.com/Lenxza1/pick-girl-mobile) or [pick-girl-api](https://github.com/Lenxza1/pick-girl-api) to see the growth.

## ✨ What It Does

- **Student Management** — Add, edit, delete student records
- **Payment Recording** — Record and track tuition payments
- **Payment Reports** — Generate payment reports and summaries
- **Class Management** — Organize students by class
- **Authentication** — Simple login system for admin/staff access

## 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| **PHP** | Server-side scripting |
| **MySQL** | Database |
| **HTML/CSS** | Frontend (no framework, plain) |
| **Bootstrap** | Basic styling (template-based) |

## 📂 Structure

```
├── index.php              # Login page
├── register.php           # Registration
├── koneksi.php            # Database connection
├── logout.php             # Logout
├── dashboard.php          # Admin dashboard
├── laporan.php            # Payment reports
├── siswa/                 # Student management
├── kelas/                 # Class management
├── spp/                   # Tuition fee management
├── petugas/               # Staff management
├── transaksi/             # Payment transactions
├── lsp/                   # LSP-related features
├── template/              # Layout templates
└── inc/                   # Includes & configs
```

## 🚀 Running It

```bash
# Requirements: PHP 7+, MySQL, Apache/XAMPP

# 1. Clone the repo
git clone https://github.com/Lenxza1/School-Payment-System.git

# 2. Import the database (if available)
# 3. Update koneksi.php with your database credentials
# 4. Serve with XAMPP or any PHP server
```

## 📸 Then vs Now

| Aspect | This Project | Recent Projects |
|--------|-------------|----------------|
| Language | PHP (procedural) | TypeScript, Dart, C# |
| Architecture | Inline PHP + HTML | REST API + separate client |
| Database | Raw MySQL queries | Prisma ORM |
| Auth | Custom (plain) | JWT + bcrypt |
| Frontend | Bootstrap templates | Flutter, React/Astro |
| Testing | None | Structured testing |

## 📄 License

Archived for educational and portfolio purposes.
