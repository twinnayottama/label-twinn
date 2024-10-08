# Label-Twinn

**Label-Twinn** is a Laravel-based application designed to generate and print blue labels for packaging products at **PT Tunas Widji Inti Nayottama**.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Generate blue labels for product packaging.
- Customizable label format based on product details.
- Export and print labels in PDF format.
- User-friendly interface to manage label data.
  
## Requirements
Before you begin, ensure you have met the following requirements:
- **PHP** >= 8.0
- **Composer** (PHP Dependency Manager)
- **Laravel** 10.x
- **MySQL** (or any other supported database)
- A web server such as **Apache** with **Laragon**

## Installation
Follow these steps to install the project locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/label-twinn.git
   cd label-twinn
2. **Install Dependencies:**
   - **Install PHP dependencies via Composer:**
     ```bash
     composer install
   - **Install frontend dependencies using NPM:**
      ```bash
     npm install && npm run dev
3. **Set Up Environment: Copy the .env.example to create a .env file:**
   - **Set Up Environment**
     ```bash
     cp .env.example .env
   - **Update the following fields in .env:**
     - Database credentials (DB_DATABASE, DB_USERNAME, DB_PASSWORD)
     - Other environment-specific settings
4. **Generate Application Key:**
   ```bash
   php artisan key:generate
5. **Migrate the Database: Run migrations to create the required database tables:**
   ```bash
   php artisan migrate
6. **Seed Database (Optional): If you want to populate the database with some initial data:**
   ```bash
   php artisan db:seed
7. **php artisan serve**
   ```bash
   php artisan serve

## Configuration
**Make sure to configure the following settings in the .env file:**
    - APP_URL: Set this to your application's URL.
    - Database: Ensure your database connection is properly set up.
If you're deploying this application, remember to configure the web server (Apache/Nginx) and ensure proper file permissions.

## Usage
1. **Access the Application: Once the server is running, you can access the app at:**
   ```bash
   http://localhost:8000
2. **Printing Labels:**
   - s
