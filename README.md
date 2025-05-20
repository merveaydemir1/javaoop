# Online Shopping System

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Quick Start](#quick-start)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
   - [Running the Application](#running-the-application)  
4. [Project Structure](#project-structure)  
5. [Usage Examples](#usage-examples)  
6. [AI Tool Usage Report](#ai-tool-usage-report)  
7. [Project Report](#project-report)  
8. [Contributing](#contributing)  
9. [Authors & Acknowledgments](#authors--acknowledgments)  
10. [License](#license)  

---

## 1. Overview

The **Online Shopping System** is a Java Swing-based desktop application designed to simulate a real-world e-commerce experience.  
- **Customers** can browse product categories, add items to their shopping cart or wishlist, place orders, and submit product reviews.  
- **Admins** have elevated privileges to add, update, or remove products, manage stock levels, and monitor order processing.

This project demonstrates core OOP principles (encapsulation, inheritance, polymorphism, abstraction) and includes a clear GUI, modular service layers, and data persistence in memory.

---

## 2. Features

- **Secure Authentication**  
  Users can register and log in securely; sessions are tracked in-memory.

- **Product Catalog & Categories**  
  Browse products organized by categories; view detailed descriptions and pricing.

- **Shopping Cart & Wishlist**  
  Add/remove items to cart or wishlist; view totals and item counts at any time.

- **Order Placement & History**  
  Checkout with current cart contents; view past orders with statuses and timestamps.

- **Review & Rating System**  
  Submit star ratings and comments on purchased products; read community feedback.

- **Admin Dashboard**  
  Add new products, edit existing entries, adjust stock levels, and remove discontinued items.

- **Search Service**  
  Filter products by name or category keywords.

- **Payment Module Stub**  
  Simulated payment processing interface to illustrate extensibility.

---

## 3. Quick Start

### 3.1 Prerequisites

- **Java Development Kit (JDK) 11+**  
  Ensure `java` and `javac` commands are on your PATH.

- **Apache Maven 3.x (optional)**  
  For automated builds and dependency management.

- **Git**  
  To clone and manage repository versions.

### 3.2 Installation

1. **Clone Repository**  
   ```bash
   git clone https://github.com/yourusername/online-shopping-system.git
   cd online-shopping-system

## AI Tool Usage Report
ChatGPT was used throughout the project to:
- Generate UML class relationships and responsibilities
- Draft boilerplate Java class templates
- Resolve compilation errors and design issues
- Improve GUI structure and usability
- Document README and project report

## Project Report
**Introduction:**  
The system is designed as an object-oriented simulation of a modern online shopping environment. The main objective is to provide functionalities for both customers and administrators.

**UML Design:**  
See [UML Diagram](umlfinal.png)

**Methodology:**  
Encapsulation and inheritance were heavily used. Classes were modularized by responsibility (e.g., `user`, `model`, `service`). Java Swing was used for the GUI.

**Results:**  
The application simulates browsing, adding/removing products from the cart, placing orders, managing stocks, and customer reviews.

## Contributing
We welcome contributions!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request

Follow our coding conventions and include meaningful commit messages.

## Authors & Acknowledgments
- **Fitnat Koç** – Main Developer – [LinkedIn](https://linkedin.com/in/fitnatkoc)
- Contributions inspired by examples and documentation from:
  - Stack Overflow
  - GeeksForGeeks
  - Oracle Docs

## License
This project is licensed under the MIT License - see the LICENSE file for details.
"""

# Append to

