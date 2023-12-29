# Setting up and Running the Payment Server

This guide will walk you through the steps required to set up and run the payment server for the art gallery mobile app.

## Prerequisites

Before you begin, make sure you have the following:

- A Stripe account
- Node.js and npm installed on your machine

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd stripe-server
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Configuration

1. Create a `.env` file in the root directory of the project.

2. Add the following environment variables to the `.env` file:

   ```plaintext
   STRIPE_PUBLISHABLE_KEY=<your-stripe-publishable-key>
   STRIPE_SECRET_KEY=<your-stripe-secret-key>
   ```

   Replace `<your-stripe-publishable-key>` and `<your-stripe-secret-key>` with your actual Stripe API keys.

## Running the Server

To start the payment server, run the following command:

```bash
node server.js
```
