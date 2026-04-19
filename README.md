# Kanban Application

A professional Task Management System built with **Microsoft Access**, designed to streamline project workflows using the Kanban methodology. This application allows teams to track progress, manage projects, and organize tasks through structured states: *To Do*, *In Progress*, *Testing*, and *Done*.

## Key Features

- **Project Tracking:** Create and manage multiple projects with specific descriptions and timelines.
- **Task Management:** Assign tasks to users, set priorities, and track deadlines.
- **Kanban Workflow:** Organized sub-forms for visualizing tasks based on their current status.
- **User Roles:** Dedicated tables for managing team members and their specific roles (Developer, Tester, Manager, etc.).
- **Reporting System:** Automated reports for project lists, task distributions, and status summaries.

## Technology Stack

- **Database Engine:** Microsoft Access (.accdb)
- **Architecture:** Relational Database Model
- **Components:** Tables, Queries, Forms (Main & Sub-forms), and Reports.

## Database Schema

The application is built on a relational structure including:
- `UTILIZATORI` (Users): Stores team member info and roles.
- `PROIECTE` (Projects): General project details and deadlines.
- `TASKURI` (Tasks): Individual work items linked to users and projects.
- `STARE` (Status): Defines the Kanban stages.
- `PRIORITATE` (Priority): Categorizes task urgency.

## Installation & Usage

1. **Prerequisites:** You must have Microsoft Access installed on your machine.
2. **Download:** Clone this repository or download the `.accdb` file.
3. **Launch:** Open `AplicațieKanban.accdb`.
4. **Navigation:** Use the provided forms to add new projects or move tasks through the Kanban board.
5. **View Reports:** Access the "Reports" section to generate printable summaries of your project progress.

##  Documentation
A detailed technical documentation (in Romanian) is available in the repository as `DocumentațieAplicațieKanban.pdf`, covering the table structures and interface design.

---
*Developed as a technical project for database management and workflow optimization.*
