# Task_Management
A simple Task Management WebApp built with React.js. This Webapp allows users to add and delete tasks, helping them keep track of their to-do list in an easy and interactive way.
🚀 Features

    ✅ Add Tasks: Users can add new tasks by entering text into an input field and clicking the "Add Task" button.
    ✅ View Tasks: The app displays a dynamic list of all the tasks added by the user.
    ✅ Delete Tasks: Users can delete any task from the list by clicking the "Delete" button next to the respective task.
    ✅ Input Validation: Prevents users from adding empty tasks.
    ✅ Clean UI: A simple, intuitive, and responsive user interface with basic CSS styling.

🏗️ Project Structure

src/
├── App.js          # Root component that renders the entire app
├── TaskDashboard.js # Handles the task input, adding, and listing
├── index.js        # React entry point
└── index.css       # Basic styling (optional)

Feel free to add screenshots here later if you want!
🛠️ Tech Stack

    Frontend: React.js (Functional Components & Hooks)
    State Management: useState hook
    Styling: CSS (or Bootstrap if you used it)

🎯 How It Works

    Task Input & Add
    Users can type their task in the input box and click "Add Task". The app checks to ensure the input isn’t empty before adding the task to the list.

    Task List Display
    All tasks are displayed in a list format below the input box. Each task shows its description and a Delete button.

    Delete Task
    When a user clicks "Delete", the corresponding task is removed from the task list dynamically.

⚙️ Getting Started

Follow these instructions to run the project locally.
1. Clone the repository

git clone https://github.com/yourusername/task-management-app.git

2. Navigate to the project directory

cd task-management-app

3. Install dependencies

npm install

4. Run the development server

npm start

The app should now be running on http://localhost:3000.
🧩 Component Breakdown
App.js

    Root component that renders the TaskDashboard.

TaskDashboard.js

    Manages the tasks array.
    Contains the input field and "Add Task" button.
    Renders the list of tasks and delete buttons.
    Handles the logic for adding and deleting tasks.

📌 Future Improvements (Optional Ideas)

    Edit/update tasks.
    Persist tasks in localStorage or a backend.
    Add task completion status with a checkbox.
    Add due dates or categories.
    Improve UI with animations or additional styling.

📄 License

This project is open-source and free to use under the MIT License.
