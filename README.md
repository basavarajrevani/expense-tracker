# Expense Tracker

A full-stack web application for tracking personal expenses and managing your budget effectively.

## Features

- Track daily expenses and income
- Categorize transactions
- View expense statistics and reports
- Manage multiple expense categories
- Responsive design for desktop and mobile use
- Secure user authentication
- Data visualization with charts and graphs
- Categorize based on category
  
## Tech Stack

### Frontend
- React.js
- Material-UI
- Chart.js for data visualization
- Axios for API requests

### Backend
- Node.js
- Express.js
- MongoDB
- JWT for authentication

## Prerequisites

- Node.js 14.x or higher
- MongoDB
- npm (Node Package Manager)

## Installation

1. Clone the repository or download the project files
```bash
git clone https://github.com/yourusername/expense-tracker-project.git
cd expense-tracker-project
```

2. Backend Setup
```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file in the backend directory and add:
# DATABASE_URL=mongodb://localhost:27017/expense_tracker
# SECRET_KEY=your_secret_key
# PORT=8000

# Start the backend server
npm start
```

3. Frontend Setup
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start the frontend development server
npm start
```

## Environment Variables

Create a `.env` file in the backend directory with the following variables:
```
DATABASE_URL=mongodb://localhost:27017/expense_tracker
SECRET_KEY=your_secret_key
PORT=8000
```

## Running the Application

1. Start MongoDB service on your system

2. Start the Backend Server
```bash
cd backend
npm start
```

3. Start the Frontend Development Server
```bash
cd frontend
npm start
```

## Usage

1. Register a new account or login with existing credentials
2. Add your expenses/income by clicking the "Add Transaction" button
3. View your spending patterns in the dashboard
4. Manage categories and track your budget
5. Generate and view reports


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the GitHub repository or contact the maintainers.
