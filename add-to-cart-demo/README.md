# Add to Cart - React + Vite Demo

This is a simple project to practice **Add to Cart** functionality using React and Vite.

---

## Introduction

- Add products to the cart  
- View all items added  
- Remove items  
- Clear the cart

Using Redux Toolkit, all cart-related state will be **globally available**, avoiding complex component hierarchies or prop-drilling.

---

## Learning Objectives

By the end of this lab, you will be able to:

- Integrate React components with **Redux Toolkit**  
- Implement key E-Commerce features:
  - Add to cart  
  - Remove from cart  
  - Clear cart  
- Compose multiple React components into a single UI  
- Use **Redux state** globally across the app

---

## Prerequisites

To succeed in this lab, you should be familiar with:

- Basic knowledge of **React** and component composition  
- Intermediate-level **JavaScript**  
- Functional components and the `useState` hook in React  
- Fundamentals of **Redux Toolkit** (`createSlice`, `store`, etc.)

---

## Getting Started

Follow these steps to create a new React + Vite project and use this code.

---

### Create a new Vite + React project

```bash
npm create vite@latest add-to-cart-demo --template react
```

> Or with Yarn:

```bash
yarn create vite add-to-cart-demo --template react
```

Then move into your project:

```bash
cd add-to-cart-demo
```

---

### Install dependencies

Install base project and Redux Toolkit dependencies:

```bash
npm install @reduxjs/toolkit react-redux
```

> Or

```bash
yarn add @reduxjs/toolkit react-redux
```

---

### Replace `src` folder

Delete the existing `src` folder in the newly created Vite project.

Then copy and paste the `src` folder from this project into your Vite project, replacing the existing one.

---

### Start the development server

```bash
npm run dev
```

---

## Done!

Your Add to Cart demo should now be running locally on `http://localhost:5173`.

---

## 📁 Folder Structure

```
add-to-cart-demo/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Live Demo (Optional)

If hosted, include your live link here:

> Coming Soon or [View Live](https://your-demo-link.com)
