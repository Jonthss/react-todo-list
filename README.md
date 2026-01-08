# Simple React Todo List

A basic Todo List application built to practice React fundamentals. It features a custom dark theme and saves data to the browser's Local Storage.

## Features

* **Add Items:** Create new tasks via a text input.
* **Toggle Status:** Mark items as completed or active using a custom checkbox.
* **Delete Items:** Remove tasks from the list.
* **Local Storage:** Tasks are saved automatically and persist after page reloads.

## Technologies Used

* **React:** Uses functional components and Hooks (`useState`, `useEffect`).
* **CSS:** Pure CSS with no external UI libraries. Uses HSL colors and modern selectors like `:has()`.

## Project Structure

* `App.jsx`: Main logic, state management, and Local Storage synchronization.
* `NewTodoForm.jsx`: Component for the input field and adding new items.
* `TodoList.jsx`: Renders the list of items.
* `TodoItem.jsx`: Individual list item component with checkbox and delete button.

## How to Run

1.  Clone the repository.
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Run the project:
    ```bash
    npm run dev
    ```

## License

MIT
