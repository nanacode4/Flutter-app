
# Flutter Login App with Firebase

A simple Flutter application implementing user authentication (register/login) using Firebase Authentication.

## ✨ Features

- Firebase-based user authentication
- Login & Registration with:
  - Full Name
  - Email Address
  - Password
- Input validation for all fields
- Dynamic welcome message on Home page
- Logout functionality that signs out the user and redirects to Login page

## 📱 Screens

- **Login Page**  
  Users can log in using their email and password. Includes validation and error handling.

- **Register Page**  
  New users can sign up by providing full name, email, and password. Stores display name in Firebase and Firestore.

- **Home Page**  
  Greets the user with their full name:  
  `"Hey, <FullName>! You're successfully logged in."`  
  Includes a logout button.

## 🔧 Technologies Used

- [Flutter](https://flutter.dev/)
- [Firebase Authentication](https://firebase.google.com/products/auth)
- [Cloud Firestore](https://firebase.google.com/products/firestore)
- Dart

## 🚀 Getting Started

### 1. Clone the project

```bash
git clone https://github.com/nanacode4/Flutter-app.git
cd Flutter-app

