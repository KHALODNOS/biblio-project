# 📚 Books Library

A modern and interactive web application for managing, browsing, and discovering books. Built with **Laravel 12** and **Livewire**, the platform delivers a fast and seamless user experience with real-time updates and intuitive book management features.

## ✨ Features

### 📖 Book Management

- Create, edit, update, and delete books.
- Upload and manage book cover images.
- Organize books using categories and tags.

### 🔍 Smart Search & Filtering

- Real-time search powered by Livewire.
- Filter books by categories and tags instantly.
- Sort books by:
    - Title
    - Price
    - Publication Date

### 🌍 Multilingual Support

- Easily switch between multiple languages.
- Localization-ready architecture.

### 📧 Email Integration

- Send book information directly via email.
- Built-in mail configuration support.

### 🎨 Modern UI

- Responsive design for desktop, tablet, and mobile devices.
- Clean and modern interface built with Tailwind CSS.

## 🛠️ Tech Stack

| Technology   | Description                      |
| ------------ | -------------------------------- |
| Laravel 12   | Backend Framework                |
| Livewire     | Real-Time Frontend Interactivity |
| Tailwind CSS | Styling & Responsive Design      |
| SQLite       | Lightweight Database             |
| PHP          | Server-Side Language             |

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/younesabourrig01/Books-Library.git
cd Books-Library
```

### 2. Install Dependencies

```bash
composer install
npm install
npm run build
```

### 3. Configure Environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Configure Database

Update the database settings in the `.env` file according to your environment.

### 5. Run Migrations and Seed Data

```bash
php artisan migrate --seed
```

### 6. Create Storage Link

```bash
php artisan storage:link
```

### 7. Start the Application

```bash
php artisan serve
```

Visit:

```text
http://127.0.0.1:8000
```

## 📂 Project Structure

```text
app/
resources/
routes/
database/
storage/
public/
```

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository, create a feature branch, and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
