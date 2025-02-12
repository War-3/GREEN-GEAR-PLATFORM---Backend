# Agriculture Equipment Rental Platform

## Overview
The **Agriculture Equipment Rental Platform** is a web application that allows farmers and renters to sign up, log in, browse agricultural equipment, add items to their cart, book equipment, choose delivery locations, and make secure payments.

## Features
- **User Authentication**: Farmers and renters can sign up and log in securely.
- **Equipment Booking**: Users can browse and book available agricultural equipment.
- **Shopping Cart**: Users can add equipment to their cart before making a booking.
- **Payment Integration**: Secure payment processing using Flutterwave and Paystack.
- **Delivery Selection**: Renters can specify their preferred delivery location.
- **Email Notifications**: Confirmation emails sent using Nodemailer.

## Technologies Used
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JWT (JSON Web Tokens)
- **Hosting:** TBD (e.g., Heroku, Vercel, or AWS)

### Dependencies
```json
{
  "dependencies": {
    "axios": "^1.7.8",
    "bcryptjs": "^2.4.3",
    "cors": "^2.8.5",
    "crypto": "^1.0.1",
    "crypto-js": "^4.2.0",
    "dotenv": "^16.4.5",
    "express": "^4.21.1",
    "express-validator": "^7.2.0",
    "flutterwave-node-v3": "^1.1.12",
    "fs": "^0.0.1-security",
    "fs2": "^0.3.15",
    "jsonwebtoken": "^9.0.2",
    "moment": "^2.30.1",
    "mongoose": "^8.7.3",
    "multer": "^1.4.5-lts.1",
    "nodemailer": "^6.9.16",
    "paystack-api": "^2.0.6",
    "uuid": "^11.0.3"
  },
  "devDependencies": {
    "nodemon": "^3.1.7"
  }
}
```

## Installation & Setup
### Prerequisites
- Node.js
- MongoDB (local or cloud-based)
- A payment gateway account (Flutterwave or Paystack)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/War-3/GREEN-GEAR-PLATFORM---Backend.git
   cd agriculture-equip-rental
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and add necessary environment variables:
   ```plaintext
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   FLUTTERWAVE_SECRET=your_flutterwave_secret_key
   PAYSTACK_SECRET=your_paystack_secret_key
   ```
4. Start the development server:
   ```sh
   npm Start
   npm run dev
   ```

## Usage
- Visit `http://localhost:8040` to access the platform.
- Sign up or log in as a farmer or renter.
- Browse and book available equipment.
- Add equipment to the cart and proceed with payment.
- Select a delivery location and confirm the order.


## Contribution
Feel free to contribute by submitting pull requests or opening issues.

## License
This project is licensed under the MIT License.

## Contact
For inquiries, reach out via [onyekweluwalter@gmail.com].

