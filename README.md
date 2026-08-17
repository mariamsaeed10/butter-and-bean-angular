# ☕ Butter & Bean

> A modern and interactive Coffee & Bakery website built with Angular.

Butter & Bean is a creative coffee and bakery website designed to provide a smooth, elegant, and enjoyable shopping experience.

The project was developed as a final project during my Angular Web Development training, combining the concepts and skills I learned throughout the training into one complete application.

---

## ✨ Features

### 🏠 Home Page
- Modern and creative landing page
- Attractive hero section
- Smooth animations
- Responsive design
- Coffee & bakery themed UI

### ☕ Menu
The menu contains different categories:

- Hot Drinks ☕
- Cold Drinks 🧊
- Donuts 🍩
- Pastries 🥐

Each product includes:

- Product image
- Name
- Description
- Price
- Quantity controls
- Add to Cart button

### 🛒 Shopping Cart

- Add products to cart
- Increase / decrease quantity
- Remove products
- Calculate subtotal
- Calculate total
- Save cart data using LocalStorage
- Animated cart interactions

### 🔎 Search

Users can search for products easily through the menu.

### 👤 Authentication

- Login page
- Signup page
- Form validation
- User information
- Logout functionality
- User data stored using LocalStorage

### 🌙 Dark Mode

The website supports Dark Mode with a smooth visual transition.

### ❌ 404 Not Found

A custom animated Not Found page for invalid routes.

### 🔔 Notifications

Custom animated popups and notifications for:

- Product added to cart
- Successful signup
- Login errors
- Validation errors
- Other user actions

---

## 🛠️ Technologies Used

- Angular
- TypeScript
- HTML5
- SCSS / CSS
- Angular Router
- FormsModule
- LocalStorage
- Font Awesome
- CSS Animations
- Responsive Web Design

---

## 📚 Angular Concepts Used

During the development of this project, I practiced:

- Components
- Standalone Components
- Angular Routing
- Data Binding
- Event Binding
- Property Binding
- Structural Control Flow
- `@for`
- `@if`
- Interfaces
- TypeScript Classes
- Forms
- Form Validation
- LocalStorage
- Component-based architecture

---

## 📂 Project Structure

```text
Butter-And-Bean/
│
├── src/
│   ├── app/
│   │   ├── home/
│   │   ├── menu/
│   │   ├── cart/
│   │   ├── login/
│   │   ├── signup/
│   │   ├── notfound/
│   │   └── ...
│   │
│   ├── assets/
│   │   ├── HotDrinks/
│   │   ├── ColdDrinks/
│   │   ├── Donuts/
│   │   ├── Pastries/
│   │   └── ...
│   │
│   ├── index.html
│   ├── main.ts
│   └── styles.scss
│
├── angular.json
├── package.json
├── package-lock.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.spec.json
├── .gitignore
└── README.md
