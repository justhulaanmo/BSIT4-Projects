# 💆 Nids and Taray Beauty and Wellness Hub System

A comprehensive beauty and wellness hub management system built with **Laravel** and modern web technologies.

## 🌐 Live Site

🔗 [https://nids-and-taray-beauty-and-wellness-hub.onrender.com](https://nids-and-taray-beauty-and-wellness-hub.onrender.com)

---

## 👥 Group Members

| Name | Role |
|------|------|
| Bea Sarong | Member |
| Rudmark Renion | Member |
| Quin Ann Amigo | Member |
| Ashley Louise Chiu | Member |
| Lilibeth Bacohod | Member |

---

## 🛠️ Tech Stack

- **Backend:** Laravel (PHP)
- **Frontend:** Blade Templates, Vite
- **Database:** MySQL / SQLite
- **Deployment:** Render.com
- **Containerization:** Docker

---

## 🚀 Getting Started (Local Development)

### Prerequisites

- PHP >= 8.1
- Composer
- Node.js & npm
- MySQL or SQLite

### Installation

\`\`\`bash
# 1. Clone the repository
git clone https://github.com/justhulaanmo/Nids-and-Taray-Beauty-and-Wellness-Hub-System.git
cd Nids-and-Taray-Beauty-and-Wellness-Hub-System

# 2. Install PHP dependencies
composer install

# 3. Install Node dependencies
npm install

# 4. Copy environment file and configure it
cp .env.example .env
php artisan key:generate

# 5. Run database migrations
php artisan migrate

# 6. Build frontend assets and start the server
npm run dev
php artisan serve
\`\`\`

Open your browser at \`http://localhost:8000\`.

---

## 📁 Project Structure

\`\`\`
├── app/           # Laravel application logic (Models, Controllers, etc.)
├── config/        # App configuration files
├── database/      # Migrations, seeders, and factories
├── public/        # Publicly accessible files (entry point)
├── resources/     # Blade views, CSS, JS source files
├── routes/        # Web and API route definitions
├── storage/       # Logs, cache, and uploaded files
└── tests/         # Automated test suites
\`\`\`

---

## 📄 License

This project was developed for academic purposes as part of the **BSIT 4** curriculum.
