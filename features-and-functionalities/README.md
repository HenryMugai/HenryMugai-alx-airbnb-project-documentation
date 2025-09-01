# Airbnb Clone - Features and Functionalities

This document captures the key features and functionalities of the Airbnb Clone backend system.

## Core Functionalities
1. **User Management**
   - Registration (guest/host)
   - Login & Authentication (JWT, OAuth)
   - Profile management

2. **Property Listings**
   - Add/Edit/Delete listings
   - Store details: title, description, location, price, amenities, availability

3. **Search & Filtering**
   - Search by location, price range, amenities, number of guests
   - Pagination support

4. **Booking System**
   - Create bookings with date validation
   - Cancel bookings
   - Track booking status (pending, confirmed, canceled, completed)

5. **Payments**
   - Secure payments via Stripe/PayPal
   - Payouts to hosts
   - Multi-currency support

6. **Reviews & Ratings**
   - Guests leave reviews/ratings
   - Hosts respond to reviews

7. **Notifications**
   - Email + in-app notifications (bookings, cancellations, payments)

8. **Admin Dashboard**
   - Manage users, listings, bookings, payments

## Technical Requirements
- RESTful API
- PostgreSQL database
- JWT Authentication
- Role-based access control (guest, host, admin)
- Cloud storage for images
- Error handling & logging
- Scalable, secure, performant

---

📌 See `features.png` for a visual representation of the system features (created with Draw.io).
