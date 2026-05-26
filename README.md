<div align="center">

# ⚛️ Counter 1.0

### *First steps with React — a simple counter app.*

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_7-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 📖 About

**Counter 1.0** is the first React project — built right after learning the basics of the React framework. It's a clean, minimal counter application that demonstrates the three core React fundamentals: component structure, the `useState` hook, and event handling.

Simple on purpose — the goal was to understand how React's state and re-rendering works before building anything more complex.

---

## ✨ Features

- **Increment** — Increases the counter value by 1
- **Decrement** — Decreases the counter value by 1
- **Reset** — Returns the counter to 0
- **Reactive Display** — Count value re-renders instantly on every state change
- **Accessible** — Buttons include `aria-label` attributes

---

## 🔍 Core Concept

```jsx
const [count, setCount] = useState(0)

const increment = () => setCount(count + 1)
const decrement = () => setCount(count - 1)
const reset     = () => setCount(0)
```

This single `useState` hook is the entire state model — the app re-renders whenever `count` changes.

---

## 🛠️ Tech Stack

| Tool | Version |
|---|---|
| React | 19.2.0 |
| Vite | 7.x |
| Language | JavaScript (JSX) |
| Linting | ESLint + React Hooks plugin |

---

## 📂 Project Structure

```
Counter-1.0/
├── index.html          # Vite HTML entry
├── vite.config.js      # Vite configuration
├── package.json        # Dependencies & scripts
├── eslint.config.js    # ESLint rules
└── src/
    ├── main.jsx        # React DOM root render
    ├── App.jsx         # Counter component (useState, 3 buttons)
    ├── App.css         # Component styles
    └── index.css       # Global base styles
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/Manan-2007/Counter-1.0.git
cd Counter-1.0
npm install
npm run dev
# Open http://localhost:5173
```

---

## 🎓 Context

> This was the very **first React project** — understanding components, JSX syntax, `useState`, and how Vite bootstraps a React app. See [Counter 2.0](https://github.com/Manan-2007/Counter-2.0) for the improved version built after going deeper into React.

---

<div align="center">

Made by **Manan** · [GitHub](https://github.com/Manan-2007)

</div>
