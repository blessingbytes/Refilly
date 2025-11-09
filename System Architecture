#  System Architecture - Refillly (Gas Refills)

## Overview
Refillly is a web and mobile platform connecting users with gas refill vendors. Users can schedule cylinder refills at home, track usage, and pay digitally. The system is secure, scalable, and designed for reliability.

## Frontend
- **Web:** React.js
- **Mobile:** React Native
- **Components:** 
  - Gas Refill Scheduler
  - Home Refill Service Interface
  - Vendor Locator Map
  - Payment Interface
  - User Dashboard / Usage Insights

## Backend
- **Server:** Node.js with Express
- **Responsibilities:**
  - Handle API requests from web/mobile
  - Authentication & authorization
  - Manage refill schedules, user & vendor data
  - Payment processing

## Database
- **MongoDB / PostgreSQL**
- **Collections/Tables:**
  - Users: { name, contact, address, gas type, usage history }
  - Vendors: { name, location, capacity, safety certifications, ratings }
  - Orders: { userID, vendorID, cylinder type, quantity, schedule, status }
  - Payments: { orderID, amount, status }

## Communication Flow
1. User places a gas refill order via web or mobile.
2. Backend validates order and checks vendor availability.
3. Payment gateway processes transaction.
4. Vendor receives order notification and confirms.
5. User receives real-time updates on refill status and delivery time.

 
## Feasibility
- Scalable backend to handle multiple users and vendors.
- Secure API endpoints for user and payment data.
- Integration with Google Maps for vendor locations ensures timely delivery.
- Mobile-first design for ease of scheduling and tracking refills.


