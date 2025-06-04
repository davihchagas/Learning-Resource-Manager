# Learning-Resource-Manager

A lightweight and modular web application built with Vue.js 3 for organizing and displaying learning resources. Users can add, view, and store various types of educational materials with ease, using a clean component-based architecture.

## 🛠 Features
- Add and Save Resources: Easily input learning materials with titles, descriptions, and links.

- Dynamic Resource List: Automatically updates the interface when new items are added.

- Reusable UI Components: Custom-designed base components such as cards, buttons, dialogs, and headers for consistent styling.

- Dialog Interaction: Prompt users with modal dialogs for actions like deletion or confirmation.

- Separation of Concerns: Clear structure separating layout, logic, and styling.

## 🧱 Built With
- Vue.js 3

- Component-based architecture

- Scoped styles (optional if your repo uses them)

- Manual state handling (no Vuex or Pinia)

## 📁 Project Structure Highlights
- App.vue: Root component orchestrating the application.

- main.js: Application entry point and global component registration.

- components/: Includes:

- UI/: Base UI components (card, button, dialog)

- layouts/: Header layout

- Other components like AddResource.vue, LearningResource.vue, and StoredResource.vue for logic and display.

## 🚀 How to run

npm install <br>
npm run serve
