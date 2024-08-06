![Screenshot 2024-08-06 100913](https://github.com/user-attachments/assets/32d27a91-db68-4242-bd75-e4a7e3746a5b)

# ToDo Application

## Overview

This ToDo application is built using React.js and demonstrates core functionalities such as adding, editing, deleting, and toggling the completion status of tasks. The app also integrates with the browser's local storage to persist data across page reloads, ensuring that user data is maintained.

## Features

- **Add Tasks**: Create new tasks with a unique ID.
- **Edit Tasks**: Update existing tasks with an editing interface that toggles on click.
- **Delete Tasks**: Remove tasks from the list.
- **Toggle Completion**: Mark tasks as completed or incomplete by clicking on the task.
- **Local Storage Integration**: Save tasks to and load tasks from local storage for data persistence.

## Components

- **`TodoWrapperLocalStorage`**: The main container component managing the todo list state and local storage integration.
- **`TodoForm`**: A form component for adding new tasks.
- **`Todo`**: Displays individual tasks with options to edit, delete, or toggle completion.
- **`EditTodoForm`**: Provides an interface for editing existing tasks.

## Technologies

- **React.js**: JavaScript library for building user interfaces.
- **FontAwesome**: Icons used for edit and delete actions.
- **Local Storage**: For persistent data storage.

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Install Dependencies
   ```bash
   npm install
3. Run the application:
   ```bash
   npm start

