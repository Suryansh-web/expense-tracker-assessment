# expense-tracker-assessment


A full-stack expense tracking application built with **React (Vite)** and **Node.js (Express)**. Manage your daily expenses with ease, visualize spending categories, and filter your history.

## Features

-   **Add Expenses**: Quickly add expenses with amount, date, category, and description.
-   **View History**: See a list of all your expenses, sorted by date.
-   **Filtering & Sorting**: Filter expenses by category and toggle sort order (Newest/Oldest).
-   **Total & Insights**: Real-time calculation of total spending and a "Top Spending" category breakdown.
-   **Delete Expenses**: Remove unwanted entries with a single click.
-   **Data Persistence**: All data is stored in a local SQLite database.
-   **Robust API**: Backend handles input validation, idempotency (prevents duplicate submissions), and CORS.
-   **Responsive UI**: Modern, clean interface styled with Tailwind CSS v4.

## Tech Stack

-   **Frontend**: React.js, Vite, Tailwind CSS v4, Axios
-   **Backend**: Node.js, Express.js, SQLite3
-   **Tools**: Postman/Curl (for API testing), Git

## Prerequisites

-   Node.js (v14 or higher)
-   npm (Node Package Manager)

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Suryansh-web/expense-tracker-assessment.git
cd expense-tracker-assessment
```

### 2. Backend Setup

Navigate to the backend directory and install dependencies:

```bash
cd backend
npm install
```

Start the backend server:

```bash
node server.js
```

The server will run on `http://localhost:3000`. It will automatically create the `expense_tracker.db` SQLite database file.
