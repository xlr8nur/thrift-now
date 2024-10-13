# Thrift Now

**Thrift Now** is a modern web application designed to facilitate the buying and selling of second-hand items. Built with a user-friendly interface, it allows users to list items for sale, browse through available products, and make secure purchases or trades.

## Features

- **User Authentication**: Sign up and log in securely.
- **Item Listings**: Add, edit, or remove items for sale.
- **Category Search**: Browse items by category or search directly.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Secure Transactions**: Support for secure online payments.

## Technologies Used

- **Frontend**: ReactJS, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payments**: Stripe API

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (v14 or higher)
- MongoDB
- Stripe API keys

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/xlr8nur/thrift-now.git
   ```

2. Navigate to the project directory:

   ```bash
   cd thrift-now
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables by creating a `.env` file in the root directory. Include:

   ```
   MONGODB_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_key
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open your browser and visit `http://localhost:3000`.

### Testing

Run the test suite using:

```bash
npm test
```

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

---

For any further questions, please reach out to [repo owner](mailto:xlr8nur@protonmail.com).
