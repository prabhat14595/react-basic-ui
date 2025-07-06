# React App – Beginner Starter

This is a beginner-friendly React.js project bootstrapped with [`create-react-app`](https://github.com/facebook/create-react-app).

It helps you understand the basic structure of a React app, how to run it, and how to start building your own components and pages.

---

## 📁 Project Structure

```
my-app/
├── node_modules/           # Project dependencies
├── public/                 # Static files (index.html, images, etc.)
├── src/                    # Source code (your components go here)
│   ├── App.css             # App-specific styles
│   ├── App.js              # Root component
│   ├── index.js            # Entry point of the app
│   ├── logo.svg            # Default React logo
│   └── ...
├── .gitignore              # Files to ignore in Git
├── package.json            # Project config and dependencies
├── README.md               # You’re reading it 🙂
└── yarn.lock / package-lock.json
```

---

## 🚀 Getting Started

### 1. Clone or Download This Project

```bash
git clone https://github.com/prabhat14595/react-basic-ui.git
cd my-app
```

Or, create your own using:

```bash
npx create-react-app my-app
cd my-app
```

### 2. Install Dependencies

Make sure you have **Node.js** and **npm** installed. Then run:

```bash
npm install
```

### 3. Start Development Server

```bash
npm start
```

This runs the app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload automatically if you make edits.

---

## 🧠 Key Concepts

### 🔹 Components

React apps are built using **components**. You can create a component like this:

```jsx
function Welcome() {
  return <h1>Welcome to My App!</h1>;
}
```

### 🔹 Props and State

Props allow you to pass data between components. State lets you store and manage data within a component.

```jsx
function Greeting({ name }) {
  return <p>Hello, {name}!</p>;
}

function App() {
  const [name, setName] = useState("React Beginner");
  return <Greeting name={name} />;
}
```

### 🔹 JSX Syntax

JSX lets you write HTML-like code inside JavaScript:

```jsx
return <h1>Hello World</h1>;
```

---

## 🔧 Useful Commands

| Command         | Description                     |
| --------------- | ------------------------------- |
| `npm start`     | Run app in development mode     |
| `npm run build` | Build app for production        |
| `npm test`      | Run tests                       |
| `npm run eject` | Reveal config (not reversible!) |

---

## 📚 Learn More

* [React Docs](https://reactjs.org/docs/getting-started.html)
* [Create React App Docs](https://create-react-app.dev/)
* [React Router](https://reactrouter.com/)
* [FreeCodeCamp React Course](https://www.freecodecamp.org/learn/front-end-development-libraries/react/)

---

## 🧼 Clean Up Tips (Optional)

After creating the app, you may want to clean the default boilerplate:

* Remove the `logo.svg`, `App.css`, and default content in `App.js`
* Start fresh with a new component structure

---

## 📦 Dependencies

* **React** – JavaScript library for building UI
* **ReactDOM** – Renders React into the DOM
* **react-scripts** – CRA scripts for development/build

---

## 💡 Tips

* Use **VS Code** for best experience
* Install the **React Developer Tools** extension for Chrome/Firefox
* Commit regularly with Git

---

## 🛠️ Next Steps

Want to grow further?

* Add **React Router** for multi-page navigation
* Learn **State Management** (Context, Redux)
* Deploy using **Vercel**, **Netlify**, or **GitHub Pages**

---

## 👨‍💻 Author

Created by \[Your Name] – follow me on [GitHub](https://github.com/your-username)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).