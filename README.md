# React To-Do List

A simple and responsive To-Do List application built with React. This project allows users to add, edit, and delete tasks, with the data being persisted in the browser's local storage.

## Features

- Add new tasks to the list.
- Edit existing tasks.
- Delete tasks from the list.
- Tasks are saved in the browser's local storage, so they persist across page reloads.
- Responsive and user-friendly design.

## Project Structure

react_to_do_list/<br>
├── public/<br>
│ └── index.html # HTML template<br>
├── src/<br>
│├── App.js # Main application component<br>
│ ├── App.css # Global styles<br>
│ ├── index.js # Entry point for React<br>
│ ├── components/<br>
│ │ ├── Main.js # Main container component<br>
│ │ ├── Main.css # Styles for Main component<br>
│ │ ├── Form/<br>
│ │ │ ├── index.js # Form component for adding/editing tasks<br>
│ │ │ └── Form.css # Styles for Form component<br>
│ │ ├── Tasks/<br>
│ │ │ ├── index.js # Tasks component for displaying the task list<br>
│ │ │ └── tasks.css # Styles for Tasks component<br>
├── .editorconfig # Editor configuration<br>
├── .gitignore # Git ignore file<br>
├── eslint.config.mjs # ESLint configuration<br>
├── package.json # Project dependencies and scripts<br>

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/react_to_do_list.git
   cd react_to_do_list

2. Install dependencies:

  ```sh
  npm install

3. Start the development server:

  ```sh
  npm start

## Scripts

- npm start: Starts the development server.
- npm run build: Builds the app for production.
- npm test: Runs the test suite.
- npm run eject: Ejects the app configuration (use with caution).

## Technologies Used

- React: Frontend library for building user interfaces.
- React Icons: For adding icons to the application.
- PropTypes: For type-checking React props.
- CSS: For styling the application.

## ESLint Configuration

The project uses ESLint for linting with the following configurations:

- @eslint/js: JavaScript linting rules.
- eslint-plugin-react: React-specific linting rules.
- globals: Browser global variables.

## Local Storage

The application uses the browser's local storage to persist tasks. Tasks are saved automatically whenever they are added, edited, or deleted.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.
