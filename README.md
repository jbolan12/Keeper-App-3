# Keeper-App-3

# Notes App (With Components)

This is a simple React application that allows users to create, display, and delete notes. The app is built using functional components and React hooks like `useState`. It features separate components for managing the header, footer, creating notes, and displaying them.

## Features

- Add new notes with a title and content.
- Display a list of created notes.
- Delete notes from the list.
- The app uses multiple reusable components: `Header`, `Footer`, `CreateArea`, and `Note`.

## Project Structure

- **`App.jsx`**: The main component that holds the state and integrates all other components. It manages the notes and handles adding and deleting them.
- **`Header.jsx`**: A component that represents the header of the app.
- **`Footer.jsx`**: A component that represents the footer of the app.
- **`Note.jsx`**: A component that represents each individual note.
- **`CreateArea.jsx`**: A component for the input fields where users can create new notes.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jbolan12/Keeper-App-3.git
    ```

2. Navigate into the project directory:
    ```bash
    cd notes-app
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage

To start the app locally:

1. Run the development server:
    ```bash
    npm start
    ```

2. Open your browser and go to [http://localhost:3000](http://localhost:3000) to view the app.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
