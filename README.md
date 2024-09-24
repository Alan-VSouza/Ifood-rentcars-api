# iFood RentCars API

This project is an API for managing car rentals, developed using Node.js with TypeScript and Express. It was created as a group effort by multiple contributors. The API includes features such as rate limiting, security headers, and data validation.

## Features

- **Car Rental Management**: Enables customers to rent cars with various operations such as booking, listing available cars, and returning rented vehicles.
- **User Authentication**: Provides user authentication for accessing protected resources.
- **Data Validation**: Uses **Zod** for schema validation of request data.
- **Security**: Utilizes **Helmet** for setting HTTP headers and **Express Rate Limit** for preventing excessive requests.
- **API Status Codes**: Uses **http-status-codes** to standardize responses.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **TypeScript**: A statically typed superset of JavaScript.
- **Express**: Web framework for building the API.
- **Zod**: TypeScript-first schema declaration and validation library.
- **Helmet**: Helps secure Express apps by setting various HTTP headers.
- **Express-Rate-Limit**: Basic rate-limiting middleware for Express.

## Requirements

- **Node.js** version 20.9 or later.

## Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Alan-VSouza/Ifood-rentcars-api.git
```

2. Install dependencies:

```bash
npm install
```

### Running the Project

To run the project in development mode:

```bash
npm run dev
```

For production mode, first build the project:

```bash
npm run build
```

Then start the production server:

```bash
npm run start
```

## Scripts

- **`npm run dev`**: Runs the project in development mode with hot reloading.
- **`npm run build`**: Compiles the TypeScript files to JavaScript.
- **`npm run start`**: Starts the API in production mode.
- **`npm run lint`**: Runs ESLint for linting the code.
- **`npm run lint:fix`**: Fixes lint issues automatically.

## Project Structure

- **`src/`**: Contains the main source code.
- **`dist/`**: Contains the compiled code.
- **`tests/`**: Contains unit tests for the API.

## Future Improvements

- **Database Integration**: Currently, the project does not persist data. In future versions, a database can be integrated to store rental information.
- **Additional Security**: Implement more advanced security measures like OAuth or JWT for user authentication.
- **Dockerization**: Add a Dockerfile to containerize the application.

## Contributors

This project was developed by a group of contributors. For any questions or inquiries, feel free to reach out via the repository's issues or contact any of the contributors listed.
