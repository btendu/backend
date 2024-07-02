Certainly! Here's the entire README content formatted as a single code block:

```markdown
# MERN E-Commerce Project

This project is an e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Browse products by category
- Add products to cart
- User authentication and authorization
- Admin panel to manage products, categories, and orders

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/btendu/ecom.git
   cd ecom
   ```

2. **Install dependencies**

   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the `server` directory and add the following:

   ```plaintext
   PORT=5000
   MONGODB_URI=<your_mongodb_uri>
   JWT_SECRET=<your_jwt_secret>
   ```

   Replace `<your_mongodb_uri>` with your MongoDB connection URI and `<your_jwt_secret>` with a random string for JWT token.

4. **Run the application**

   ```bash
   # Start the server
   cd server
   npm start

   # Start the client (in another terminal)
   cd client
   npm start
   ```

   The client should open automatically in your default browser at `http://localhost:3000`.

## Usage

- Browse products, add them to cart, and proceed to checkout.
- Admin can manage products, categories, and orders through the admin panel.

## Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

## License

```

You can now copy this entire block and paste it directly into your `README.md` file. This will ensure all content is in one code snippet for easy inclusion in your project documentation.
