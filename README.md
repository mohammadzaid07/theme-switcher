# 🎨 Theme Switcher App (Dark/Light Mode)

A simple React application that demonstrates how to implement **theme switching (light/dark)** using **React Context API** and **Tailwind CSS**.

## 🌐 Live Demo

🔗 [Click here to try it out](https://mohammadzaid07.github.io/theme-switcher/)

## 🚀 Features

- ⚛️ Built with React + Vite
- 🌗 Light/Dark mode switch
- 🎨 Uses Tailwind CSS’s dark mode classes
- 🧠 Global theme state managed via React Context API

## 🛠️ Tech Stack

- React
- Tailwind CSS
- React Context API
- Vite

## 💡 How It Works

1. The current theme (`light` or `dark`) is stored in a React state.
2. Theme context provides `lightTheme` and `darkTheme` functions globally.
3. A `useEffect` hook updates the `html` tag's class based on the selected theme.
4. Tailwind's dark mode styles respond accordingly.

## 🎛️ Components

- **ThemeBtn**: A toggle button that switches between light and dark mode.
- **Card**: A sample card to demonstrate how styles adapt to the selected theme.
