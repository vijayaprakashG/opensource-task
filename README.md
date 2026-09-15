# TaskFlow

## Productivity and Task Management Web Application

TaskFlow is a simple and responsive web-based productivity management application designed to help users organize tasks, manage deadlines, track productive habits, and monitor their overall progress from a single dashboard.

The project is developed using **HTML5, CSS3, and JavaScript**. It is a front-end application that can run directly in a web browser without requiring a database, backend server, or paid software.

---

## Project Overview

Managing daily tasks, academic activities, deadlines, and personal goals can become difficult when information is stored in different places.

TaskFlow provides a centralized productivity dashboard where users can:

* View their productivity statistics
* Create new tasks
* Search for tasks
* Filter tasks by category
* Manage work, study, and personal tasks
* Track upcoming deadlines
* Monitor productive habits
* View a simple profile interface
* Use light and dark themes
* Access the application from desktop or mobile devices

---

## Objectives

The main objectives of TaskFlow are:

1. To provide a simple task management interface.
2. To help users organize their daily activities.
3. To provide a dashboard for monitoring productivity.
4. To help users keep track of important deadlines.
5. To encourage consistent productive habits.
6. To provide a responsive and user-friendly web interface.
7. To demonstrate the use of open and freely available web technologies.

---

## Features

### 1. Productivity Dashboard

The dashboard displays important productivity information such as:

* Total Tasks
* Completed Tasks
* Pending Tasks
* Completion Rate

---

### 2. Task Management

Users can manage different types of tasks, including:

* Work
* Study
* Personal

Each task displays:

* Task name
* Description
* Category
* Priority
* Due information

---

### 3. Task Search

Users can search for tasks using the search box.

The application automatically filters the displayed tasks based on the entered search text.

---

### 4. Task Filtering

Tasks can be filtered according to category:

* All
* Work
* Study
* Personal

This makes it easier to find specific types of tasks.

---

### 5. Create New Task

Users can create a new task by entering:

* Task name
* Task category

The newly created task is dynamically added to the task list using JavaScript.

---

### 6. Upcoming Deadlines

The application provides a dedicated deadline section where users can view important upcoming activities such as:

* Project Submission
* Seminar Presentation
* Assignment Submission

---

### 7. Productive Habits

Users can view progress for different productive habits, including:

* Daily Study
* Reading
* Exercise

Progress bars are used to visually represent habit completion.

---

### 8. Dark Mode

TaskFlow includes a theme toggle that allows users to switch between:

* Light Mode
* Dark Mode

---

### 9. Profile

A simple profile modal is provided to display productivity and preference information.

---

### 10. Quick Start

The Quick Start option provides basic instructions explaining how to begin using TaskFlow.

---

### 11. Responsive Design

The application is designed to work on:

* Desktop computers
* Laptops
* Tablets
* Mobile devices

CSS media queries automatically adjust the layout for smaller screens.

---

## Technologies Used

| Technology | Purpose                                                   |
| ---------- | --------------------------------------------------------- |
| HTML5      | Structure of the web application                          |
| CSS3       | Styling, layout, animations, themes and responsive design |
| JavaScript | Task management and interactive functionality             |
| Git        | Version control                                           |
| GitHub     | Source code hosting and collaboration                     |

---

## Project Structure

Currently, the complete application is implemented in a single HTML file.

```text
TaskFlow/
│
├── index.html
└── README.md
```

The `index.html` file contains:

* HTML structure
* CSS styling
* JavaScript functionality

---

## How to Run the Project

### Method 1: Open Directly

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The TaskFlow application will open in your default web browser.

No installation is required.

---

### Method 2: Using Visual Studio Code

1. Open the project folder in **Visual Studio Code**.
2. Open `index.html`.
3. Install the **Live Server** extension if required.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. The application will open in your browser.

---

## How to Use

### View Dashboard

Scroll to the **Dashboard** section to view productivity statistics.

### Search Tasks

1. Go to the **Tasks** section.
2. Enter a task name in the search box.
3. Click **Search** or type directly into the search box.
4. Matching tasks will be displayed.

### Filter Tasks

Select one of the available categories:

```text
All
Work
Study
Personal
```

Only tasks belonging to the selected category will be displayed.

### Add a Task

1. Enter a task name.
2. Select a category.
3. Click **Add Task**.
4. The new task will appear in the task list.

### View Deadlines

Go to the **Deadlines** section to view upcoming project and academic deadlines.

### Track Habits

The **Habits** section displays progress bars for productive activities.

### Change Theme

Click the **Theme** button in the navigation bar to switch between light and dark modes.

### Quick Start

Click **Quick Start** to view basic instructions for using the application.

### Profile

Click the **Profile** button to view the demo profile information.

---

## FOSS Relevance

TaskFlow is suitable for a **Free and Open Source Software (FOSS)** academic project because it can be developed, studied, modified, distributed, and maintained using freely available technologies and open development tools.

The project uses standard web technologies such as:

* HTML5
* CSS3
* JavaScript
* Git
* GitHub

The source code can be shared publicly on GitHub, allowing other developers and students to:

* Study the source code
* Modify existing functionality
* Add new features
* Fix bugs
* Improve the user interface
* Create their own versions
* Collaborate through Git
* Contribute improvements

The application does not depend on proprietary software for its basic functionality.

---

## Advantages

* Simple and beginner-friendly
* Easy to understand
* Easy to modify
* Responsive user interface
* No database required
* No backend server required
* Runs directly in a web browser
* Task search functionality
* Task filtering functionality
* Dynamic task creation
* Light and dark themes
* Suitable for academic demonstration
* Can be hosted easily on GitHub
* Can be extended with additional features

---

## Limitations

The current version is a front-end demonstration and has some limitations:

* Tasks are not permanently stored.
* There is no database.
* There is no real user authentication.
* Profile information is only a demonstration.
* Deadline information is static.
* Habit information is static.
* Productivity statistics are sample values.
* Tasks are lost when the browser page is refreshed.

---

## Future Enhancements

The project can be further improved by adding:

* User registration and login
* Database integration
* User authentication
* Persistent task storage
* Task editing and deletion
* Task completion functionality
* Real-time productivity statistics
* Calendar integration
* Reminder notifications
* Email notifications
* Advanced deadline tracking
* Habit history
* Productivity charts
* Admin dashboard
* User profile management
* Cloud data storage
* Mobile application
* REST API
* Backend integration

---

## Suggested Future Architecture

A future version of TaskFlow can be developed using:

```text
Frontend
    |
    |-- HTML
    |-- CSS
    |-- JavaScript
    |
    ↓
Backend
    |
    |-- Node.js / Python / PHP
    |
    ↓
Database
    |
    |-- MySQL / PostgreSQL
```

This would allow tasks, users, deadlines, and habits to be permanently stored.

---

## GitHub Usage

The project can be maintained using Git and GitHub.

Example Git commands:

```bash
git init
git add .
git commit -m "Initial TaskFlow project"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

After uploading the project, other developers can clone the repository, modify the source code, and contribute improvements.

---

## License

This project can be distributed under the **MIT License**.

The MIT License allows users to:

* Use the software
* Copy the software
* Modify the software
* Distribute the software
* Use it for personal or commercial purposes

A separate `LICENSE` file should be included in the GitHub repository.

---

## Recommended Repository Structure

```text
TaskFlow/
│
├── index.html
├── README.md
└── LICENSE
```

---

## Academic Use

This project can be used as a demonstration project for subjects related to:

* Free and Open Source Software
* Web Development
* Internet Programming
* Front-End Development
* Software Engineering
* Open Source Development

---

## Conclusion

TaskFlow is a simple productivity management web application that provides task management, deadline tracking, habit monitoring, productivity statistics, search, filtering, and theme switching in a single interface.

The project demonstrates how a useful web application can be created using freely available web technologies and maintained using Git and GitHub. Its simple structure also makes it easy for students and developers to study, modify, extend, and contribute to the project.
