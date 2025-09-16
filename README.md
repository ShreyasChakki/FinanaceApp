# FinSmart - Your Personal Finance Assistant With Ai Suggestions

FinSmart is a comprehensive financial management application that helps users track expenses, set savings goals, and get AI-powered financial insights to make better money decisions.

## Features

- **User Authentication**
  - Secure login and registration
  - Profile management

- **Expense Tracking**
  - Log daily expenses with categories
  - View spending patterns
  - Filter transactions by date, category, and type

- **Savings Goals**
  - Create and manage financial goals
  - Track progress towards targets
  - Set deadlines and priorities

- **Financial Dashboard**
  - Visualize your financial data
  - Get an overview of your spending habits
  - Monitor monthly budgets

- **Smart Insights**
  - AI-powered financial recommendations
  - Spending analysis
  - Budget optimization suggestions

## Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS templates, Tailwind CSS, JavaScript
- **Database**: MongoDB
- **Authentication**: Session-based authentication

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/finsmart.git
   cd finsmart
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables in a `.env` file:
   ```
   PORT=3000
   MONGODB_URI=your_mongodb_connection_string
   SESSION_SECRET=your_session_secret
   ```

4. Start the application:
   ```
   npm start
   ```

   For development with auto-restart:
   ```
   npm run dev
   ```

5. Access the application at `http://localhost:3000`

## Usage

1. Register for a new account or log in with existing credentials
2. Add your income sources and regular expenses
3. Set up savings goals with target amounts and deadlines
4. Track your daily expenses by adding transactions
5. View insights and reports to understand your spending habits
6. Adjust your financial habits based on recommendations

## Project Structure

```
├── config/         # Configuration files
├── controllers/    # Route handlers
├── middleware/     # Custom middleware
├── models/         # Database models
├── public/         # Static assets
├── routes/         # Express routes
├── utils/          # Helper functions
├── views/          # EJS templates
├── app.js          # Main application file
└── package.json    # Project dependencies
```

## Screenshots

[Add screenshots of your application here]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Tailwind CSS for the beautiful UI components
- Express.js community for the excellent documentation
- MongoDB for the flexible database solution