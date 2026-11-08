# Installation Guide – openSIS College Edition

## 1. Introduction

This guide explains how to install and configure
openSIS College Edition for local development.

## 2. Requirements

The application requires a compatible environment:

- Windows or Linux
- Apache Web Server
- PHP (compatible with the selected openSIS release)
- MySQL or MariaDB
- Web browser
- XAMPP (for Windows local development)

Check the original openSIS documentation for
the exact PHP and database requirements.

## 3. Installation Using XAMPP

### Step 1: Install XAMPP

Download and install XAMPP.

### Step 2: Download the Project

Clone the repository:

    git clone https://github.com/Metekia/openSIS-College-Edition.git

### Step 3: Configure the Application

Place the project in:

    C:\xampp\htdocs\openSIS-College-Edition

### Step 4: Configure the Database

1. Start Apache and MySQL.
2. Open phpMyAdmin.
3. Create a dedicated development database.
4. Configure the application database connection.
5. Follow the applicable openSIS database installation procedure.

### Step 5: Start the Application

Open:

    http://localhost/openSIS-College-Edition/

Complete the installation and configuration
according to the application setup process.

## 4. Security Recommendations

- Never publish database passwords.
- Never upload production database backups.
- Use sample data for demonstrations.
- Use a separate development database.
- Restrict access to administrative accounts.
- Configure HTTPS for production deployments.

## 5. Troubleshooting

For installation problems, check:

- Apache error logs.
- PHP error logs.
- MySQL service status.
- Database connection settings.
- PHP extension compatibility.

## 6. Important Notice

Installation requirements may differ between
openSIS releases and customized deployments.

Verify compatibility before production installation.
