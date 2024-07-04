# Todo Application using Redux Toolkit

Welcome to the Todo Application! This is a simple and efficient to-do list application built with React, Redux Toolkit, and React Redux. It allows users to add, delete, and manage their tasks with ease.

## Features

- **Add Tasks**: Quickly add new tasks to your to-do list.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Task Management**: Mark tasks as complete or incomplete.
- **Redux Toolkit**: State management using Redux Toolkit for a seamless experience.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Ramavtar-Nagar/React-ReduxToolkit-Todo.git
    cd todo-app
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```
    or if you prefer yarn:
    ```bash
    yarn install
    ```

3. **Start the application**:
    ```bash
    npm start
    ```
    or with yarn:
    ```bash
    yarn start
    ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Add your tasks using the input field and the "Add Task" button.
3. Manage your tasks by marking them as complete or deleting them.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Redux](https://react-redux.js.org/)

## Contact

If you have any questions or suggestions, please feel free to contact me at [ramavtarnagar13.com].


## Project Structure

```plaintext
src/
├── app/
│   └── store.js      # Redux store configuration
├── components/
│   ├── AddTodo.js    # Component to add a new todo
│   └── Todos.js   # Component to display the list of todos
├── features/
│   └── todos/
│       ├── todosSlice.js  # Redux slice for todos
├── App.jsx           # Main app component
├── main.jsx         # Entry point for the React app
└── index.css        # Global styles

