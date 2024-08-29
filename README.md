# Online Shop

This project is a Django-based e-commerce platform that provides a robust and scalable solution for online shopping. The platform includes essential e-commerce features such as a product catalog, shopping cart, and payment integration, along with advanced functionalities like asynchronous tasks, recommendation systems, and internationalization support.

## Features

- **Product Catalog:**
  - Comprehensive product catalog with categories and detailed product pages.

- **Shopping Cart:**
  - Session-based shopping cart that allows users to add, update, and remove products.

- **Payment Integration:**
  - Integrated with Stripe for secure online payments.
  - Webhook implementation for handling payment notifications and order processing.

- **Asynchronous Tasks:**
  - Asynchronous processing using Celery and RabbitMQ for tasks like order processing and notifications.

- **Custom Context Processor:**
  - Provides global access to the shopping cart across all templates.

- **Coupon System:**
  - Support for discount coupons with customizable rules.

- **PDF Invoice Generation:**
  - Automated PDF invoice creation using WeasyPrint for completed orders.

- **Recommendation Engine:**
  - Redis-based recommendation engine to suggest related products to users.

- **Internationalization and Localization:**
  - Comprehensive support for multiple languages and regions.
  - Translation management using Rosetta.
  - Language selector for users to choose their preferred language.

- **Admin Features:**
  - Custom Django admin actions for exporting orders and data to CSV files.

## Usage

- **Product Browsing:** Explore products through categories and detailed product pages.
- **Shopping Cart:** Add products to your cart and proceed to checkout.
- **Checkout and Payment:** Complete your purchase using Stripe's secure payment gateway.
- **Coupon System:** Apply discount coupons during checkout for eligible orders.
- **PDF Invoices:** Download PDF invoices for completed orders.
- **Product Recommendations:** Get product suggestions based on Redis-powered recommendations.
- **Language Selector:** Choose your preferred language using the language selector.

## Optimization and Performance

- **Asynchronous Tasks:** Celery and RabbitMQ handle background tasks for improved performance.
- **Redis Caching:** Redis is used for caching and recommendation engine, enhancing speed and user experience.
- **WeasyPrint:** Efficient PDF generation for invoices.

## Technologies Used

- **Django:** A high-level Python web framework.
- **Stripe:** For payment processing.
- **Celery & RabbitMQ:** For asynchronous task management.
- **Redis:** For caching and recommendation engine.
- **WeasyPrint:** For generating PDF invoices.
- **HTML/CSS:** For frontend development.
- **Rosetta:** For translation management and internationalization.
