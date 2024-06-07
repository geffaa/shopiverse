# Shopiverse - E-commerce Website

Welcome to Shopiverse, a full-stack e-commerce website creation project designed to offer an intuitive and enjoyable online shopping experience for users. This project encompasses essential features like user registration, login, logout, product search, browsing product catalog, shopping cart management, checkout process, and secure purchases.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Register, login, and logout functionalities.
- **Product Catalog**: Browse and search for products.
- **Shopping Cart**: Add, remove, and view items in the shopping cart.
- **Checkout Process**: Seamless checkout and order processing.
- **Payment Integration**: Secure payment processing with Stripe.

## Technologies Used

### Front-end
- **Nuxt.js**: A powerful Vue.js framework for building modern web applications.
- **Tailwind CSS**: A utility-first CSS framework for designing responsive and attractive UI components.

### Back-end
- **Prisma Flow (Supabase)**: An open-source database toolkit and API for managing back-end data.

### Payment Processing
- **Stripe**: A comprehensive suite of APIs for handling secure online payments.

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (version 12 or higher)
- npm (version 6 or higher) or yarn
- Supabase account and project setup
- Stripe account for payment processing

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/shopiverse.git
    cd shopiverse
    ```

2. **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following variables:
    ```env
    SUPABASE_URL=your-supabase-url
    SUPABASE_KEY=your-supabase-key
    STRIPE_SECRET_KEY=your-stripe-secret-key
    ```

4. **Run the application:**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

    The application should now be running on `http://localhost:3000`.

## Usage

1. **User Registration and Login:**
   - Register a new user account or login with existing credentials.

2. **Browse Products:**
   - Explore the product catalog and search for specific items.

3. **Manage Cart:**
   - Add products to the shopping cart, update quantities, or remove items.

4. **Checkout:**
   - Proceed to checkout, enter shipping information, and complete the purchase securely using Stripe.

## Contributing

We welcome contributions to Shopiverse! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template to better fit your project's specifics and any additional details you would like to include.
