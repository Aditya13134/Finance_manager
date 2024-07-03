# Finance_manager

Finance Tracker is a web application designed to help users manage their finances by tracking income, expenses, and budget goals. Built using React, Node.js, Express, and Tailwind CSS, this app provides a seamless user experience with modern UI design and robust backend functionality, including user authentication.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (register, login, logout)
- Add, edit, and delete income and expense entries
- Categorize transactions for better tracking
- View monthly and annual summaries
- Responsive design with Tailwind CSS
- Secure backend with Express and Node.js

## Demo

Check out the live demo [here](#) (replace with your demo link).

## Installation

### Prerequisites

- Node.js
- npm or yarn

### Backend Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/finance-tracker.git
    cd finance-tracker/backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `backend` directory and add the following environment variables:

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

### Frontend Setup

1. Navigate to the `frontend` directory:

    ```bash
    cd ../frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `frontend` directory and add the following environment variable:

    ```env
    REACT_APP_API_URL=http://localhost:5000
    ```

4. Start the frontend development server:

    ```bash
    npm start
    ```

## Usage

1. Register a new account or login with an existing one.
2. Add your income and expense entries.
3. View and manage your transactions in the dashboard.
4. Check your financial summary to stay on top of your budget goals.

## Technologies Used

- **Frontend:**
  - React
  - Tailwind CSS

- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - JWT for authentication

## Contributing

We welcome contributions to enhance Finance Tracker! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
