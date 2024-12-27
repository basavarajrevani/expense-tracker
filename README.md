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

## Tech Stack

### Frontend
- React.js
- Material-UI
- Chart.js for data visualization
- Axios for API requests

### Backend
- Python
- FastAPI
- SQLAlchemy
- PostgreSQL database

## Prerequisites

- Python 3.8 or higher
- Node.js 14.x or higher
- PostgreSQL database

## Installation

1. Clone the repository
```bash
git clone [repository-url]
cd expense-tracker-project
```

2. Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
pip install -r requirements.txt
```

3. Frontend Setup
```bash
cd frontend
npm install
```

4. Database Setup
- Create a PostgreSQL database
- Update the database connection string in the backend configuration

## Environment Variables

Create a `.env` file in the backend directory with the following variables:
```
DATABASE_URL=postgresql://username:password@localhost:5432/expense_tracker
SECRET_KEY=your_secret_key
```

## Running the Application

1. Start the Backend Server
```bash
cd backend
uvicorn main:app --reload
```

2. Start the Frontend Development Server
```bash
cd frontend
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000
- API Documentation: http://localhost:8000/docs

## Usage

1. Register a new account or login with existing credentials
2. Add your expenses/income by clicking the "Add Transaction" button
3. View your spending patterns in the dashboard
4. Manage categories and track your budget
5. Generate and view reports

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the GitHub repository or contact the maintainers.
