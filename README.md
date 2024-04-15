# e-Shop Application

## Overview

The e-Shop application is an online shopping platform built using Angular/TypeScript on the frontend and Express.js on the backend. It leverages Angular Material and Tailwind CSS for UI design and integrates with the Fake Store API (https://fakestoreapi.com/) to fetch product data. Additionally, the application provides a checkout process integrated with Stripe for processing payments.

## Prerequisites

Before running the e-Shop application, ensure you have the following prerequisites installed:

```bash
Node.js
Angular CLI (version 14.2.0)
Stripe account (for payment processing)
```

## Getting Started

1. Navigate to the project directory:

   ```bash
   cd e-shop
   ```

2. Install dependencies for both the frontend and backend:

   ```bash
      npm install
   cd server
   npm install
   ```

## Development Server

To run the development server, follow these steps:

1. Start the backend server:

   ```bash
   cd server
   npm start
   ```

2. Start the frontend development server:

   ```bash
   cd ../
   ng serve
   ```

3. Navigate to [http://localhost:4200/](http://localhost:4200/) in your web browser to access the e-Shop application.

## Build

To build the project, run the following command:

```bash
ng build
```

The build artifacts will be stored in the `dist/` directory.

## Stripe Integration

The checkout process in the e-Shop application is integrated with Stripe for processing payments. To integrate your Stripe account:

1. Sign up for a Stripe account at [https://stripe.com/](https://stripe.com/).
2. Obtain your Stripe API keys.
3. Configure the Stripe API keys in the backend of your e-Shop application.

## Contributing

Contributions to the e-Shop application are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the MIT License. Feel free to modify and distribute the code for your own purposes.
