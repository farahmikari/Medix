
## 🏥 Medix — Clinic Management Application
<img width="1024" height="1024" alt="logo" src="https://github.com/user-attachments/assets/ca5e0e83-1403-44bd-b20d-05a10b61a68f" />

**Medix** is a system designed to manage **medium-sized multi-specialty medical clinics** .
It aims to automate daily operational tasks, including:

- Medical staff management  
- Appointment and booking management  
- Patient medical records management  
- Billing and invoicing management

______________________________________________________________

## 🚀 Features
1. Authentication
2. Requesting and receiving medical reports  
3. Appointment punctuality points  
4. Appointment booking system automation  
5. Notification system  
6. Medical records automation
7. Bills Management
8. Accessibility

______________________________________________________________

## 🛠️ Flutter & Dart Version

Your environment must meet the following minimum requirements:

  dart: ">=3.7.2 <4.0.0"
  flutter: ">=3.29.0"
  
______________________________________________________________

## 🧩 State Management & Local Storage

This project uses:

- **Bloc** for state management  
- **Shared Preferences** for local data persistence (saving user info, tokens, etc.)
- **Dio** (API Communication)
- **Firebase** (Notification)
  
______________________________________________________________

## 🚀 How to Run the Complete System (XAMPP + Backend + Frontend)
1. Before running the backend, make sure XAMPP services are running:  
- Start **Apache**  
- Start **MySQL**  
2. Then first run Backend Laravel project (following the steps explained below)
3. Finally run Frontend Flutter project (following the steps explained below)

______________________________________________________________

## 📦 Installation and Run Flutter Project
   ```bash
   # clone project
   git clone https://github.com/farahmikari/Medix.git

   # Navigate into the project
   cd Medix

   # Install dependencies
   flutter pub get

   # Run flutter application
   flutter run   
   ```
______________________________________________________________

## 🖥️ Backend framework

Laravel 11

______________________________________________________________

## 🔗 Backend Setup
The backend source code is available here in **main* branch  :
https://github.com/FarahRam04/MEDIX.git

To run the backend project :
  ```bash
  # clone project 
  git clone https://github.com/FarahRam04/MEDIX.git

  # Navigate into the project
  cd MEDIX

  # Install dependencies
  composer install

  # Generate application key
  php artisan key:generate

  # Run database migrations
  php artisan migrate

  # Create the environment file (The `.env` file is not included in the repository for security reasons.)
  cp .env.example .env
   # Open the newly created .env file and update the following values
   APP_URL=http://127.0.0.1:8000
   DB_DATABASE=your_database_name
   DB_USERNAME=your_username
   DB_PASSWORD=your_password

  # Run migrations + seed database
  php artisan migrate:fresh --seed

  # Link storage Folder
  php artisan storage:link

  # Start the Laravel development server
  php artisan serve
  ```
______________________________________________________________

## 🔗 API Base URL
  ```bash
  # update the flutter app baseURL in class EndPoints
  http://127.0.0.1:8000

  ```
______________________________________________________________

## 👥 Team Members

- **Ahmad Jouhar** Flutter Developer
https://github.com/Ahmad-Jouhar-1
 
- **Farah Mikari** Flutter Developer
https://github.com/farahmikari
  
- **Farah Ramadan** Laravel Developer
https://github.com/FarahRam04
  
- **Reham Mahmoud** Laravel Developer
https://github.com/reham270
  
______________________________________________________________
