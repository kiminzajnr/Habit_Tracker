# Habit Tracker

A habit tracker application built using Python Flask and MongoDB. The application allows users to track their habits daily, mark them as complete, and view them in a calendar-like format.

## Features

- Track Habits
- Mark Habits as Complete
- View Habit History

## Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** Python Flask
- **Database:** MongoDB

## Setup Instructions

### Prerequisites

- Python 3.x
- MongoDB
- pip

### Installation

1. **Clone the repository:**

   ```bash
   https://github.com/kiminzajnr/Habit_Tracker.git
   cd Habit_Tracker

2. Create an environment
    ```
    python3 -m venv .venv

3. Activate the environment
    ```
    . .venv/bin/activate

4. **Install the required packages:**
    ```
    pip install -r requirements.txt

5. **Set up environment variables:**  
    Create a `.env` file in the root directory of the project and add your MongoDB connection string:
    ```
    MONGODB_URI=your_mongodb_uri

6. **Run the application:**
    ```
    flask run