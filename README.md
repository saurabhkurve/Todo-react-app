# Todo App

Welcome to the Todo App, a minimalist yet powerful tool to keep track of your tasks. Built with simplicity and efficiency in mind, this app leverages the power of React, utilizing its Context API and `useContext` hook to manage global state, ensuring that your todos are accessible throughout the component tree without prop drilling. Moreover, it incorporates `localStorage` to save your todos, making them persist across sessions for a seamless user experience.

## Features

- **Add, Toggle, and Remove Todos**: Easily add new tasks, mark them as complete, or remove them from your list.
- **Persistence**: Thanks to `localStorage`, your todos stay saved between browser sessions.
- **State Management with Context API**: Utilizes React's Context API and `useContext` hook for efficient state management across components.
- **Minimalist Design**: A clean, user-friendly interface that helps you focus on the tasks at hand.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Before you begin, ensure you have the latest version of [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/todo-app.git](https://github.com/saurabhkurve/Todo-react-app.git 

2. Install NPM packages
   ```sh
    npm install 

3. Start the development server
   ```sh
    npm run dev

This runs the app in development mode. Open http://localhost:3000 to view it in your browser.


### Usage
To add a new todo, simply type in your task in the input field and press enter. Your task will immediately appear in the list below. Click on a task to toggle its completed status, or click the 'X' button to remove it from the list.

### How It Works
- Context and useContext: This app uses a `TodoContext` to pass down the todos state and state-updating functions (add, toggle, remove) through the component tree, avoiding the need to prop drill.
- Local Storage: The app uses the `useEffect` hook to synchronize the todos state with localStorage, ensuring that todos persist across browser sessions.

### Link to Project
Experience the Todo App live: [Todo App](https://todolistbysk.netlify.app/)


### Contact
 - [Twitter](https://twitter.com/saurabh_kurve)
 -  [Linkedln](https://www.linkedin.com/in/saurabhkurve/)
