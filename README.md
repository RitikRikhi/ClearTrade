# ClearTrade - Advanced Trading Platform

ClearTrade is a comprehensive full-stack trading application designed to provide users with a seamless and intuitive trading experience. Built with the MERN stack (MongoDB, Express.js, React, Node.js), it features real-time market data simulation, portfolio management, secure user authentication, and a modern, responsive user interface.

## 🚀 Features

-   **User Authentication**: Secure Signup and Login functionality with JWT authentication.
-   **Dashboard**: Real-time overview of portfolio value, balance, and profit/loss.
-   **Market Data**: Live-simulated stock prices with interactive charts.
-   **Trading**: Buy and sell stocks instantly with real-time portfolio updates.
-   **Portfolio Management**: Track your holdings, view average buy prices, and monitor performance.
-   **Order History**: Detailed record of all your buy and sell transactions.
-   **Wallet & Funds**: Manage your trading capital with ease.
-   **Responsive Design**: A beautiful, mobile-friendly interface built with modern CSS and React.

## 🛠️ Tech Stack

-   **Frontend**: React.js, React Router, Recharts (for charts), CSS3.
-   **Backend**: Node.js, Express.js.
-   **Database**: MongoDB.
-   **Authentication**: JSON Web Tokens (JWT), Bcrypt.
-   **Deployment**: Vercel (Frontend & Backend).

## 📦 Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/cleartrade.git
    cd cleartrade
    ```

2.  **Install Dependencies**
    ```bash
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```

3.  **Environment Setup**
    Create a `.env` file in the `backend` directory:
    ```env
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    PORT=5000
    ```

4.  **Run the Application**
    ```bash
    # Run both backend and frontend concurrently (from root)
    npm run dev
    ```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.
