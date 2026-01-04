# 💳 Laravel Stripe Subscription Billing

A Laravel-based implementation of **Stripe Subscription Billing**, supporting plan selection, secure checkout, invoices, subscription lifecycle management, and Stripe SCA (Strong Customer Authentication).

This project demonstrates how to integrate **recurring payments** into a Laravel application using Stripe.

---

## 🚀 Overview

This application enables users to:
- Select subscription plans
- Subscribe using Stripe Checkout
- Access premium content based on active subscriptions
- View and download invoices
- Change or cancel subscriptions
- Handle Stripe SCA (3D Secure) flows

It is designed to showcase a **real-world SaaS billing system** using Laravel and Stripe.

---

## 🔑 Key Features

- ✅ User authentication
- 💳 Stripe subscription payments
- 📦 Plan selection & upgrades
- 🔐 Middleware-based subscription access control
- 📄 Invoice generation & download
- 🔄 Subscription cancellation & plan change
- 🛡️ Stripe SCA (Strong Customer Authentication) support
- 📊 Subscription status tracking

---

## 🧭 Application Routes & Functionalities

### Public & Auth Routes
- `/` – Welcome page
- `/home` – User dashboard
- `/planselect` – Subscription plan selection
- `/subscribe` – Initiate Stripe subscription payment

### Subscription Management
- `/premium` – Premium content (protected by subscription middleware)
- `/cancelsubscription` – Cancel active subscription
- `/change` – Change subscription plan

### Billing & Invoices
- `/invoice` – View invoices
- `/user/{id}` – Download invoice

### Stripe Payment Flow
- `/checkout` – Stripe checkout session
- `/paynow` – Process Stripe payment
- `/payinteger` – Payment page
- `/scademo` – Stripe SCA authentication demo

---

## 🛠️ Technology Stack

- **Backend:** Laravel (PHP)
- **Payments:** Stripe API
- **Database:** MySQL
- **Authentication:** Laravel Auth
- **Security:** Stripe SCA (3D Secure)
- **Frontend:** Blade Templates, Bootstrap, JavaScript

---

## 📂 Project Structure (High-Level)

```bash
app/
├── Http/
│ ├── Controllers/
│ │ └── HomeController.php
│ │ └── PayController.php
│ └── Middleware/
routes/
├── web.php
resources/
├── views/
database/
├── migrations/
```

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
    git clone https://github.com/your-username/Laravel-Stripe-Subscription-Billing.git
    cd Laravel-Stripe-Subscription-Billing
```

### Install Dependencies

```bash
    composer install
    npm install
```

### Environment Setup

```bash
   Create .env file and configure Stripe credentials:
   env

   Copy code

   STRIPE_KEY=your_stripe_public_key
   STRIPE_SECRET=your_stripe_secret_key
   STRIPE_WEBHOOK_SECRET=your_webhook_secret
```


### Database Migration

```bash
    Copy code
    php artisan migrate
```

### Run the Application

```bash    
    php artisan serve
    App will be available at:
    http://127.0.0.1:8000
```

🎯 Use Cases
   
    SaaS subscription billing
    
    Membership-based platforms
    
    Premium content access
    
    Stripe recurring payments in Laravel
    

📌 Learning Highlights

    Stripe Checkout & Subscriptions
    
    Secure payment handling
    
    Middleware-based access control
    
    Subscription lifecycle management
    
    Real-world Laravel billing architecture

📄 License

    This project is intended for educational and demonstration purposes.

---

# ✅ How This Helps Your Profile

✔ Shows **real SaaS billing experience**  
✔ Demonstrates **Stripe + Laravel expertise**  
✔ Aligns perfectly with **Senior Backend Engineer** roles  
✔ Recruiters instantly understand **business impact**

---

If you want next, I can:
- 🔥 Write **resume bullets** for this project
- 🔥 Create **LinkedIn project description**
- 🔥 Improve **controller naming & architecture explanation**
- 🔥 Suggest **screenshots/demo section**

Just say **next** 🚀
