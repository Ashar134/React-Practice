# Lab: Fetch Data using `useFetch`

## Overview

This lab demonstrates how to fetch and display data in a React application using a custom React hook named `useFetch`. By encapsulating data-fetching logic into a reusable hook, the code becomes cleaner, more modular, and easier to maintain.

## What I Learned

- How to use the `fetch` API to retrieve data from an external source in a React app.
- How to build a custom hook (`useFetch`) to handle asynchronous data fetching.
- How to use `useState` and `useEffect` to manage component state and side effects.
- How to dynamically render fetched data using JSX.
- How to display key information from the API such as:
  - Name
  - Importance
  - Benefits
  - Best time to intake
- How to manage loading and error states in a user-friendly way.

## Key Takeaways

- Custom hooks improve code reusability and separation of concerns.
- `useEffect` is essential for running async operations like data fetching on component mount.
- `useState` allows you to manage and render dynamic UI based on API responses.
- JSX can be used to conditionally display data once it’s successfully fetched.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
