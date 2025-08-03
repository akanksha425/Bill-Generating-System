# 🧾 Bill Generating System

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-informational)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey)
![Email Integration](https://img.shields.io/badge/Feature-Email%20Sending-success)

A simple yet efficient Python-based billing system with a graphical user interface (GUI) built using **Tkinter**, designed to generate itemized bills for small businesses or shops. The application also features **email integration** to directly send the bill receipt to the customer’s email address.

---

## 📌 Features

- 🖥️ **GUI Interface** using Tkinter  
- 🛒 Add/remove items, quantity, and price  
- 💰 Automatic calculation of subtotal, tax, and grand total  
- 📤 **Send bill to customer via email**  
- 💾 Save and retrieve previous bills from local storage  
- 🧾 Printable and scrollable receipt view  
- ⚙️ Easily extendable for more features like discounts, barcode scanning, etc.

---

## 🎥 Demo

> *[Include a screenshot or screen recording here if you have one]*  
> *(Use tools like ScreenToGif or OBS to record a quick demo and upload it as `.gif` or YouTube video)*

---

## 🏗️ Tech Stack

| Component     | Technology     |
|---------------|----------------|
| Language      | Python 3.x     |
| GUI Framework | Tkinter        |
| Database      | SQLite3        |
| Email         | `smtplib` for SMTP integration |
| IDE           | VS Code / PyCharm |

---

## ✉️ Email Integration

The application uses **Python’s `smtplib`** to send the generated bill to a customer’s email address. SMTP settings are configured securely, and the message body includes the full itemized receipt.

---

## 🚀 Getting Started

### 📦 Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- SQLite (also included in Python standard library)

### 🛠️ Installation

```bash
git clone https://github.com/akanksha425/Bill-Generating-System.git
cd Bill-Generating-System
python bill_app.py

---

📬 Contact
📧 sripathiakanksha425@gmail.com

🔗 LinkedIn

⭐ Show Your Support
If you found this project useful or inspiring, feel free to ⭐ star the repo and follow for more!
