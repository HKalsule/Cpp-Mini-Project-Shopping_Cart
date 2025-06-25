# 🛒 C++ Electronics Shopping System

This project is a beginner-friendly, console-based **shopping system in C++** that simulates a small electronics store. Users can browse a menu of devices, select quantities of items to buy, and receive automatic discounts based on their purchase quantity.

---

## 📦 Features

- 📱 Categorized Product Listing:
  - Smartphones
  - Foldables
  - Headphones
  - Smart Watches
- 🛍️ Add items to your cart
- 🧮 Calculate total bill
- 💸 Apply discounts dynamically:
  - 5% discount for buying 2–3 items
  - 10% discount for buying 4 or more items
- 🧾 View final cart summary and savings

---

## 📂 File Overview

- `Products` class  
  ➤ Represents a single product (name, price, quantity)  
  ➤ Contains method to calculate total price for that product

- `ShoppingSystem` class  
  ➤ Holds all products  
  ➤ Manages user interactions like viewing menu, purchasing items  
  ➤ Applies appropriate discounts based on total items bought

- `main()` function  
  ➤ User interaction loop  
  ➤ Collects input and shows billing details

---

## 📋 Product Categories

**Smartphones (Items 1–6)**
- iPhone 15
- iPhone 15 Pro
- Samsung S23
- Samsung S23 Plus
- Google Pixel 8
- Google Pixel 8 Pro

**Foldables (Items 7–10)**
- Samsung Z Fold 6
- Samsung Z Flip 6
- OnePlus Open
- Google Pixel Fold

**Headphones (Items 11–16)**
- AirPods
- AirPods Pro
- Samsung Buds
- Samsung Buds Pro
- Pixel Buds
- Pixel Buds Plus

**Smart Watches (Items 17–20)**
- Apple Watch Series 8
- Apple Watch Ultra
- Galaxy Watch 4
- Pixel Watch 2

---

## 💰 Discount Rules

| Total Items Bought | Discount Applied |
|--------------------|------------------|
| 0 – 1              | 0%               |
| 2 – 3              | 5%               |
| 4 or more          | 10%              |

---

## 🖥️ Sample Output

```text
Product Menu:

Smartphones
1. iPhone 15 - 80000 INR
2. iPhone 15 Pro - 120000 INR
...

Foldables
7. Samsung Z Fold 6 - 180000 INR
...

0. Checkout
-------------------------------
Enter the number of the device you want to purchase (or 0 to finish): 1
Enter the quantity: 2
2 iPhone 15 added to the cart.

Do you want to continue shopping? (Y/N): N

Cart Contents:

iPhone 15 - Quantity: 2

Total Bill Amount: 160000 INR
Discount Applied: 8000 INR
Final Bill Amount: 152000 INR
