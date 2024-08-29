# Django-Based E-Commerce Platform

This is a Django-based e-commerce platform that includes a product catalog, session-based shopping cart, and Stripe payment integration. The platform also features asynchronous task handling, a Redis-based recommendation engine, and comprehensive internationalization.

## Features

- **Product Catalog:**
  - Organized and searchable product listings.
  - Detailed product pages with descriptions, prices, and images.

- **Session-Based Shopping Cart:**
  - Users can add, update, and remove items from their cart during their session.
  - Cart contents are maintained across user sessions.

- **Stripe Payment Integration:**
  - Secure payment processing via Stripe.
  - Webhook integration for real-time payment notifications.

- **Asynchronous Tasks with Celery and RabbitMQ:**
  - Background task processing for time-intensive operations like sending emails or generating invoices.

- **Custom Context Processor:**
  - Provides global access to the shopping cart across all templates.

- **Webhook for Payment Notifications:**
  - Real-time updates on payment status, ensuring smooth order processing.

- **Custom Django Admin Actions:**
  - Admin interface includes custom actions like exporting order data to CSV.

- **Coupon System:**
  - Support for discount codes that can be applied at checkout.

- **PDF Invoice Generation:**
  - Generate and email PDF invoices using WeasyPrint.

- **Redis-Based Recommendation Engine:**
  - Provides personalized product recommendations based on user behavior.

- **Internationalization and Localization:**
  - Fully supports multiple languages and currencies.
  - Translation management using Rosetta.
  - Includes a language selector for users to switch between languages.
