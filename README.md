# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# To-Do List App (React + Vite)

A minimal and efficient To-Do List application built with **React** and **Vite**, featuring real-time UI updates, modern component structure, and ESLint configuration for clean code.

This project demonstrates fundamental React concepts such as **state management**, **component composition**, **event handling**, and **conditional rendering**, ideal for beginners learning React or for building productivity tools.

---

## Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Persistent UI state during HMR
- Responsive and clean UI
- Modern React architecture

---

## Tech Stack

- **React 18**
- **Vite**
- **ESLint**
- **JavaScript (ES6+)**

Optional plugins you may configure:
- `@vitejs/plugin-react`
- `@vitejs/plugin-react-swc`

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```

The app will start with HMR enabled.

---

## Available Scripts

| Command            | Description                     |
|-------------------|---------------------------------|
| `npm run dev`     | Start dev server with HMR        |
| `npm run build`   | Create production build          |
| `npm run preview` | Preview built app locally        |

---

## Project Structure

```
src/
  components/
    TodoInput.jsx
    TodoList.jsx
    TodoItem.jsx
  App.jsx
  main.jsx
index.html
README.md
```

---

## How It Works

- Tasks are stored in component state using `useState`
- UI updates automatically when state changes
- User actions (add, delete, Select) trigger state mutations
- Components are kept modular for readability and reuse

---

## Future Enhancements

- LocalStorage persistence
- Due dates and priority tags
- Backend with CRUD API
- Filters (Completed, Pending, All)
- Drag-and-drop sorting

---

## License

This project is open-source and free to use for learning or public repositories.
