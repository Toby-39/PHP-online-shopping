E-Commerce Website — Gaming Peripherals Store

A full-stack e-commerce platform built with PHP and MySQL, supporting member shopping and an admin management dashboard, selling gaming mice, keyboards, audio gear, and accessories.

 Features
- **Member portal**: browse 20 products across 4 categories, place orders, view order history, manage wishlist
- **Admin portal**: manage products and orders, view a Top 5 Best-Selling Products analytics dashboard
- **Order lifecycle**: 6-stage order tracking (Pending → Paid → Processing → Shipped → Delivered / Cancelled)
- **Payment integration**: PayPal checkout with order and capture ID tracking
- **Account security**: login lockout after repeated failed attempts, OTP verification, token-based password reset

 Tech Stack
- PHP
- MySQL (7-table relational schema: admins, categories, member, orders, order_items, products, wishlist)

 Database Schema
See [`amit1014_assignment.sql`](./amit1014_assignment.sql) for the full schema, including foreign key constraints and indexes.

 What I Learned
This project pushed me beyond basic CRUD into thinking about account security end-to-end: failed-login tracking, time-limited reset tokens, and OTP expiry are the kind of edge cases that matter in real production systems, not just happy-path testing.
