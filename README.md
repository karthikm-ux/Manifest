# Manifest

**A desktop shopping application built with Electron, HTML, CSS, and JavaScript.**

Manifest is a desktop e-commerce application designed to provide a simple shopping experience for browsing gadgets, exploring product details, managing a shopping cart, and tracking orders.

## Features

- **User Authentication** – User registration and login.
- **Product Catalog** – Browse a collection of laptops and mobile phones.
- **Product Search** – Search gadgets and filter products by category.
- **Product Details** – View product specifications, descriptions, and prices.
- **Shopping Cart** – Add products, update quantities, and remove items.
- **Checkout** – Demonstration checkout with UPI and Pay on Delivery options.
- **User Profile** – View account information and personal details.
- **Order History** – Keep track of previously placed orders.
- **Local Data Storage** – Store application data using browser localStorage.

## Tech Stack

| Technology | Purpose |
|---|---|
| Electron.js | Desktop application framework |
| HTML5 | Application structure |
| CSS3 | Styling and UI design |
| JavaScript | Application functionality |
| Node.js | Runtime environment |
| localStorage | Local data persistence |

## Project Structure

```text
Manifest/
├── cart/
├── common/
├── homepage/
├── login/
├── product/
├── profile/
├── search/
├── index.js
├── package.json
├── package-lock.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/karthikm-ux/Manifest.git
```

**2. Navigate to the project directory**

```bash
cd Manifest
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the application**

```bash
npm start
```

## Application Modules

| Module | Description |
|---|---|
| Login | User registration and authentication |
| Homepage | Main shopping interface |
| Search | Search and filter available gadgets |
| Product | Product details and specifications |
| Cart | Shopping cart and checkout |
| Profile | User information and order history |
| Common | Shared utilities, navigation, products, and storage |

## Project Limitations

Manifest is currently a local desktop application prototype.

- User and shopping data are stored locally.
- Checkout and payment options are demonstrations, not real payment processing.
- No production backend or online database is configured.
- Authentication is intended for demonstration purposes, not production security.

Do not use real passwords, payment details, or sensitive personal information with this prototype.

## Future Improvements

- Backend and database integration.
- Secure authentication and authorization.
- Real payment gateway integration.
- Product inventory management.
- Order tracking and notifications.
- Cloud synchronization.
- Application packaging and distribution.

## Author

**Karthik M**

GitHub: [@karthikm-ux](https://github.com/karthikm-ux)

## License

This project currently declares the ISC license in its package metadata. See the repository for licensing details.

---

If you find this project interesting, consider giving the repository a star.
