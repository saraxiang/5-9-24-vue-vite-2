# Vue 3 + Vite + Tailwind CSS Flashcard App

This project is a flashcard application built with Vue 3, Vite, and styled using Tailwind CSS.

## Project Setup

To get started with this project, clone the repository and install the dependencies:

```bash
git clone https://github.com/saraxiang/5-9-24-vue-vite-2.git
cd 5-9-24-vue-vite-2
npm install
```

This will install Vue 3, Vite, and all other necessary dependencies to run the application.

## Running the Development Server

To start the development server, run:

```bash
npm run dev
```

This will serve the application on `http://localhost:5173/`.

## Tailwind CSS Setup

Tailwind CSS has been added to the project for styling. The configuration files `tailwind.config.js` and `postcss.config.js` have been initialized in the project root.

## Building for Production

To build the application for production, run:

```bash
npm run build
```

This will create a production-ready build in the `dist` folder.

## Application Functionality

- **View Flashcards**: The main page displays all flashcards. Each flashcard shows a front and a back value.
- **Create Flashcards**: A separate page allows users to create new flashcards by entering values for the front and back. A "Save Flashcard" button submits the new flashcard.

## Usage

- Navigate to the main page to view all flashcards.
- Use the navigation bar to switch between viewing all flashcards and creating a new flashcard.
- On the "Create Flashcard" page, enter the front and back values for the new flashcard and click "Save Flashcard" to add it to the list.

## Project Structure

The project follows the standard Vue 3 project structure, with components located in the `src/components` directory and views in the `src/views` directory.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request with your proposed changes.

## License

This project is open-sourced under the MIT license.
