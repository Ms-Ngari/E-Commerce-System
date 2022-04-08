# E-Commerce-System

## Overview
This project is a robust and feature-rich eCommerce platform built using the Laravel framework. It includes admin pages for managing products, orders, and user accounts, leveraging Livewire for dynamic components, AdminLTE for the admin panel design, and a free eCommerce front-end template.

## Features
- **User-Friendly Shop Interface:**
  - Browse and search products
  - Product categories and detailed views
  - Add products to the shopping cart
  - Checkout system with order processing

- **Admin Panel:**
  - Dashboard with statistics and insights
  - Manage products, categories, and orders
  - User account management
  - Order fulfillment status tracking

- **Technologies Used:**
  - Laravel Framework
  - Livewire for reactive UI components
  - AdminLTE for backend UI design
  - Shopping Cart integration
  - Free eCommerce UI template for the front end

## Installation
### Prerequisites
Make sure you have the following installed:
- PHP (>= 8.0)
- Composer
- MySQL or any other supported database
- Node.js & npm

### Steps
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd laravel-ecommerce-shop
   ```

2. **Install dependencies:**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Set up environment variables:**
   - Copy `.env.example` to `.env`
     ```bash
     cp .env.example .env
     ```
   - Update the `.env` file with your database configuration and other settings.

4. **Generate application key:**
   ```bash
   php artisan key:generate
   ```

5. **Run database migrations:**
   ```bash
   php artisan migrate --seed
   ```

6. **Serve the application:**
   ```bash
   php artisan serve
   ```

Visit `http://localhost:8000` to view the application.

## Usage
### Shop Page
- Browse products, add to cart, and proceed to checkout.

### Admin Panel
- Access the admin panel at `http://localhost:8000/admin`
- Default admin credentials (if seeded):
  - Email: `admin@example.com`
  - Password: `password`

## Development Notes
- **Livewire Components:** Dynamic components are used throughout the shop and admin pages.
- **AdminLTE Integration:** Provides a modern and responsive design for the admin dashboard.
- **Free Ecommerce Template:** Clean and intuitive front-end design.

## Contribution Guidelines
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
- [Laravel](https://laravel.com/)
- [Livewire](https://laravel-livewire.com/)
- [AdminLTE](https://adminlte.io/)
- [Ecommerce Free Templates](#)

## Support
For issues and feature requests, please open an issue on the [GitHub Repository](<repository-url>).

