# Expense-Tracker
# Transaction Tracker

A simple Node.js/Express/MongoDB application for tracking expenses and income, with user authentication, blog-style transaction entries, and a modern Bootstrap UI.
1. Setup and Run Instructions
Prerequisites
- Node.js (v16+ recommended)
- MongoDB (local or Atlas)
- npm
Installation

1. Clone the repository
   ```bash
   git clone <your-repo-url>
   cd Transactiontracker
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   - Create a `.env` file in the root directory.
   - Add the following (adjust as needed):
     ```
     MONGODB_URI=mongodb://localhost:27017/transactiontracker
     JWT_SECRET=your_jwt_secret
     PORT=3000
     ```

4. **Start the application**
   - For development (with auto-reload):
     ```bash
     npm run dev
     ```
   - For production:
     ```bash
     npm start
