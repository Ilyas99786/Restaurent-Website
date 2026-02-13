# 🍔 ForFoodies — Restaurant Ordering Website (HTML, CSS & JavaScript)

ForFoodies is a premium-style restaurant ordering website built using **pure HTML, CSS, and JavaScript**.  
It includes a complete **Customer + Supplier(Admin)** system with real-time order management, cart tracking, UPI QR payment, invoice generation, and order status updates.

---

## 📸 Preview

> My landing page screenshot.

![ForFoodies Landing Page]("<img width="1843" height="888" alt="Screenshot 2026-02-13 132720" src="https://github.com/user-attachments/assets/3d48d572-0e3a-409a-9376-358e68aa5f6d" />")


---

## 🚀 Features

### 👤 Customer Side
- Browse restaurant menu items
- Search items instantly
- Select quantity before placing an order
- Add and track orders from Cart
- Order tracking timeline:
  **Pending → Preparing → Delivered**
- Cancel order (only while pending)
- Online Payment (UPI QR) option
- Payment confirmation checkbox ("I have paid")
- Invoice receipt shown in cart
- Download invoice as PDF
- Order history section (Delivered + Cancelled orders)

---

### 👨‍🍳 Supplier Side (Admin Role)
- Add new menu items
- Edit item price anytime
- Delete out-of-stock items
- View all customer orders
- Order controls:
  - Mark Preparing
  - Mark Delivered (Completed)
  - Cancel Order
- Dashboard analytics:
  - Total Orders
  - Delivered Orders
  - Cancelled Orders
  - Total Revenue

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (Dark Premium UI)
- **JavaScript (Vanilla JS)**
- **LocalStorage** (for data persistence)

---

## 📂 Project Structure

```bash
ForFoodies/
│── index.html
│── styles.css
│── script.js
│── qr.jpeg
└── assets/
    └── landing-page.png
## ⚙️ How to Run Locally

# Clone the repository:

git clone https://github.com/your-username/forfoodies.git


# Open the folder:

cd forfoodies


# Run with Live Server
(Recommended: VS Code Live Server extension)

## 💳 Online Payment (UPI QR)

ForFoodies supports UPI QR payment simulation.

✔ When customer selects Online Payment (UPI QR):

QR Code appears

UPI ID is shown

Payable amount updates automatically based on quantity

"I have paid" confirmation is required before order submission

## 🧾 Invoice & PDF Download

Every order generates:

Invoice receipt inside cart

Option to download invoice as PDF using browser print-to-pdf

## 🔐 Roles
# Customer

Used for ordering food and tracking orders.

# Supplier

Used for managing items and orders.

## 🌟 Future Improvements (Optional)

Add food images for each item

Sort by price (low to high)

Multiple restaurants support

Backend integration using Node.js / Spring Boot

Payment gateway integration

## 👨‍💻 Author

Ilyas
Engineering Student | Web Developer
