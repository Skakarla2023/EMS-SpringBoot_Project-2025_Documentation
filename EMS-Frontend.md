# EMS Frontend technologies

## ReactJS18

- In ReactJS we use these for the frontend of this application:
    - Functions
    - Props
    - States
    - Components
    - Hooks
    - Event Handling
    - Axios
    - Routers

- ReactJS is a JavaScript library, not a programming language, used for building user interfaces, especially for single-page applications.
- React is primarily used for building the frontend or user interface of web applications.
- React applications are built using reusable components that manage their own state and can be composed to create complex UIs.
- React is a JavaScript library used to build dynamic and interactive user interfaces for web applications using reusable components.

### 🔹 Function (in React)

- In React, a function is used to create a functional component.
- Think of it like a recipe that tells React what to show on the screen.

✅ Example:

```jsx
function Welcome() {
  return <h1>Hello!</h1>;
}
```

This Welcome function returns some HTML-like code (called JSX) that displays "Hello!" on the screen.

### 🔹Props

- Props (short for properties) are a way to pass data from one component to another, usually from a parent component to a child component.
- Props let you make your components reusable and dynamic.
- Props are used to pass data to components.
- They make components dynamic and reusable.
- Props are read-only and passed from parent to child.
- Think of props like arguments you pass to a function. In React, you pass props to custom components like this:

```jsx
<Welcome name="Satwika" />
```

Here, name="Satwika" is a prop passed to the Welcome component.



### 🔹 State

- State is used to store data that can change, like a count, form input, etc.
- If the state changes, the component automatically updates.
- State is a special built-in feature in React that allows a component to hold and manage changing data.
- It lets your component remember information and react to user actions like clicks or input.
- State is a built-in feature in React,It’s a JavaScript object (or value) used to store data inside a component, and this data can change over time.
- So, state acts like a dynamic data container that controls how your app behaves or looks.


### 🔹 Component

- A component is like a reusable building block of your webpage—just like LEGO blocks.
- It can be as small as a button or as big as a full page.

✅ Example:

```jsx
function Header() {
  return <h1>Employee Management System</h1>;
}
```

- You can reuse ```<Header /> ```anywhere in your app. 
- There are two types:

  #### Functional Components (most common now):
  
  - Functional components are plain JavaScript functions that return JSX (React elements).


  - Example:
  ```jsx
  function Welcome(props) {
    return <h1>Hello, {props.name}</h1>;
  }
  ```
  - Features:
      - Simple syntax
      - Can use Hooks (like useState, useEffect) to add state and side effects.
      - Recommended for most modern React development

  #### Class Component (older style)



### 🔹Hooks

- Hooks are special functions provided by React that let you use features like state, side effects, context, etc., in functional components.
- A hook is a built-in function from React.
- It “hooks into” React’s features, like managing state, running effects, or accessing context.
- They always start with the word use (like useState, useEffect, etc.).
- They're just functions that start with use.
- Only call hooks inside React function components or custom hooks.


### 🔹Event Handling

- Event handling in React means writing code to respond to user actions, such as:

  - Clicking a button

  - Typing in an input box

  - Submitting a form

  - Hovering over an element

### 🔹Axios

-  Axios is a JavaScript library for making HTTP requests, allowing your application to communicate with servers and APIs to fetch or send data

### 🔹Routers

- React Router, on the other hand, is a library specifically designed for navigation within single-page applications (SPAs), enabling you to create different views (or "routes") for different URLs. 

## HTML-5

- HTML provides the basic structure of the web pages in this project. It defines elements like forms, input fields, buttons, and tables for displaying employee data. React uses this structure (written in JSX) to render the UI dynamically.

## TypeScript

- JavaScript is a simple and fast programming language mainly used to make websites interactive. It also works outside the browser, like in Node.js for server-side tasks. In JavaScript, you don’t need to declare variable types—they are handled during program execution.
- TypeScript:
  -  TypeScript is made by Microsoft and is free to use.
  -  It is a superset of JavaScript that adds extra features.
  -  Any JavaScript code will also work in TypeScript.
  -  The main difference is TypeScript lets you define types for variables and functions.
  -  This helps catch mistakes before running the code (at compile-time).
  -  It’s very useful for big projects because it makes the code easier to manage and understand.
  -  TypeScript code is converted into normal JavaScript so browsers can run it.

    
### 🟡 JavaScript 

1. You write JavaScript code in .js files.
2. This code is directly run by browsers (like Chrome, Firefox) or by tools like Node.js.
3. The browser has a built-in JavaScript engine (like V8 in Chrome) that reads, interprets, and runs the code line by line.

✅ No need for extra steps — just write and run.

### 🔵 TypeScript

1. You write TypeScript code in .ts files.
2. TypeScript cannot run directly in the browser.
3. It first goes through a transpilation process using the TypeScript compiler (tsc).
4. This converts the .ts file into a .js file.
5. The output .js file is then run just like normal JavaScript, in the browser or Node.js.

⚠️ You need to compile TS before running.

## Bootstrap-5(for CSS)

- Bootstrap is a free and popular front-end framework used to design responsive and mobile-friendly websites quickly. It provides ready-made components like buttons, forms, navbars, and grids, all styled with CSS and enhanced with JavaScript. Developers use Bootstrap to make their websites look clean and professional without writing a lot of custom CSS.
