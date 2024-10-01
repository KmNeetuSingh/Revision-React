# 📝 Todo List Application--ContextApi
## Overview

This Todo List application demonstrates the implementation of the React Context API to manage global state effectively. The application allows users to add, display, and remove todo items, showcasing how to share data across components without prop drilling. 🚀

## Features

- **✅ Add Todos:** Users can input new todo items and add them to the list.
- **📜 Display Todos:** A dynamic list shows all added todos.
- **❌ Remove Todos:** Users can delete individual todo items.
- **🌐 Global State Management:** The Context API is used to manage and share todo state across components.

## Technologies Used

- React ⚛️
- Context API 🌍
- CSS for styling 🎨

## Installation

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-list-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and go to `http://localhost:3000`. 🌐

## Implementation

### Context API Structure

- **TodoContext.js:** Defines the context and provides the state and functions to manage the todo list.
- **TodoProvider.js:** A provider component that wraps the `App` component, making the todo state accessible to all child components.
- **TodoList.js:** Displays the list of todos and allows users to interact with individual items.
- **TodoForm.js:** A form for adding new todos to the list.

### Example Usage

1. Input a new todo in the form and click the "Add Todo" button. ➕
2. View the added todo in the list below. 👀
3. Click the "Remove" button next to any todo to delete it from the list. 🗑️

## Conclusion

By utilizing the Context API, this application simplifies state management and enhances scalability. The implementation demonstrates how to build a maintainable and efficient React application. 💪

