# Laravel Application – Chirper by Josh Cirre

A simple social media application built while following the Laravel Bootcamp.

This project is called **Chirper** and allows users to register, log in, and create, edit, and delete short messages called **chirps**.

---

## 🚀 Features

* User registration and authentication
* User login and logout
* Create chirps
* Edit chirps
* Delete chirps
* Authorization and permissions
* Form validation
* Database migrations
* Eloquent ORM
* Blade templates
* Tailwind CSS styling

---

## 🛠️ Technologies Used

* PHP
* Laravel
* Composer
* MySQL / SQLite
* Blade
* Tailwind CSS
* Vite
* Node.js
* npm

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Paris2020/replica-insta.git
```

### 2. Navigate into the project

```bash
cd replica-insta
```

### 3. Install PHP dependencies

```bash
composer install
```

### 4. Install JavaScript dependencies

```bash
npm install
```

### 5. Create the environment file

```bash
cp .env.example .env
```

### 6. Generate the application key

```bash
php artisan key:generate
```

---

## 🗄️ Database Setup

Configure your database credentials in the `.env` file.

### Using SQLite

Update your `.env` file:

```env
DB_CONNECTION=sqlite
```

Create the SQLite database:

```bash
touch database/database.sqlite
```

Run the migrations:

```bash
php artisan migrate
```

---

## ▶️ Running the Application

Start the Laravel development server:

```bash
php artisan serve
```

In a separate terminal, start Vite:

```bash
npm run dev
```

The application will be available at:

```text
http://127.0.0.1:8000
```

---

## 📚 What I Learned

This project was built as part of the Laravel Bootcamp and helped me gain experience with:

* Laravel project structure
* Routing
* Controllers
* Models
* Database migrations
* Eloquent ORM
* Authentication
* Authorization
* CRUD operations
* Form validation
* Blade templating
* Tailwind CSS
* Vite and frontend asset compilation

---

## 🎓 Laravel Bootcamp

This project was created by following the Laravel Bootcamp learning materials.

The Laravel Bootcamp covers fundamental Laravel concepts and provides hands-on experience building a full-stack web application.

---

## 📄 License

This project was for educational and learning purposes.
