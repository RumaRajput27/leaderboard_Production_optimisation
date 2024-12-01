This application allows users to register, log in, add expenses, and view a leaderboard of total expenses.

Features:
User Registration: Users can register by providing a username, email, and password. This data is stored securely in the database.
User Login: After registration, users can log in using their email and password. A JWT token is provided for authentication.
Add Expense: Logged-in users can add expenses by providing a description, amount, and date. The expenses are linked to the user's account.
Leaderboard: Displays a leaderboard showing users ranked by their total expenses, providing a competitive edge to track spending.

Setup:
Install dependencies with npm install.
Set up the .env file with your database credentials.
Run the server using npm start.
Visit the app at http://localhost:3000 for the full experience.
