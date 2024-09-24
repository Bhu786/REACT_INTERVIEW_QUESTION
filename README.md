# REACT_INTERVIEW_QUESTION

1. What is React?
2. What are components in React?
3. What is JSX?
4. What is the virtual DOM?
5. What are props?
6. What is state in React?
7. How do you handle events in React?
8. What are hooks in React?
9. What is the purpose of useEffect?
10. What is context in React?
11. How do you manage state in large applications?
12. What are higher-order components (HOCs)?
13. What are render props?
14. What is code splitting?
15. How can you optimize performance in a React app?
16. What are some common performance issues in React?
17. How do you handle forms in React?
18. What is the difference between controlled and uncontrolled components?
19. How do you test React components?
20. What are some common debugging techniques in React?
21. What are error boundaries?
22. How do you implement routing in a React app?
23. What is the significance of keys in lists?
24. How do you perform API calls in React?
25. What are some lifecycle methods in React?



# React FAQ

### 1. What is React?
React is a JavaScript library for building user interfaces, primarily for single-page applications, using a component-based architecture.

### 2. What are components in React?
Components are reusable, independent building blocks of a React application that return elements to be rendered on the UI.

### 3. What is JSX?
JSX (JavaScript XML) is a syntax extension for JavaScript that looks like HTML and is used to describe the UI structure in React.

### 4. What is the virtual DOM?
The virtual DOM is a lightweight copy of the actual DOM that React uses to optimize updates and re-rendering of components efficiently.

### 5. What are props?
Props (short for properties) are used to pass data from one component to another, making components dynamic and reusable.

### 6. What is state in React?
State is an internal data storage mechanism for components, allowing them to manage dynamic data and re-render when the state changes.

### 7. How do you handle events in React?
Events in React are handled using functions passed to components as props, typically using an onEvent syntax (e.g., onClick).

### 8. What are hooks in React?
Hooks are functions that let you "hook" into React's state and lifecycle features without writing class components (e.g., useState, useEffect).

### 9. What is the purpose of useEffect?
useEffect allows you to perform side effects (e.g., fetching data, manipulating the DOM) in functional components, running after render or when dependencies change.

### 10. What is context in React?
Context provides a way to share data (like theme, user, or settings) across the component tree without passing props manually at every level.

### 11. How do you manage state in large applications?
State in large applications is managed using tools like Redux, Context API, or other state management libraries to centralize and manage complex state logic.

### 12. What are higher-order components (HOCs)?
HOCs are functions that take a component as an argument and return a new component, adding additional functionality or behavior.

### 13. What are render props?
Render props are a technique where a component’s children is a function, allowing you to dynamically render content based on the state or props.

### 14. What is code splitting?
Code splitting is an optimization technique that loads only the necessary parts of the app when needed, improving performance by reducing initial load time.

### 15. How can you optimize performance in a React app?
You can optimize performance by using techniques like memoization (React.memo), lazy loading, code splitting, and avoiding unnecessary re-renders.

### 16. What are some common performance issues in React?
Common issues include unnecessary re-renders, inefficient use of state, large bundle sizes, and excessive DOM updates.

### 17. How do you handle forms in React?
Forms in React are handled using controlled components, where form inputs' values are managed by the component's state, or uncontrolled components with refs.

### 18. What is the difference between controlled and uncontrolled components?
Controlled components rely on React state to control form inputs, while uncontrolled components manage their own state using the DOM.

### 19. How do you test React components?
React components are tested using tools like Jest and React Testing Library to write unit tests and simulate user interactions.

### 20. What are some common debugging techniques in React?
Common techniques include using React Developer Tools, logging with console.log, and checking for errors in the browser console.

### 21. What are error boundaries?
Error boundaries are React components that catch JavaScript errors in their child components' tree and display a fallback UI instead of crashing.

### 22. How do you implement routing in a React app?
Routing is implemented using libraries like react-router-dom, enabling navigation between different pages or views in a single-page application.

### 23. What is the significance of keys in lists?
Keys help React identify which items in a list have changed, been added, or removed, optimizing the update process.

### 24. How do you perform API calls in React?
API calls are performed using fetch, axios, or similar libraries, often within useEffect to load data when a component mounts.

### 25. What are some lifecycle methods in React?
Some common lifecycle methods include componentDidMount, componentDidUpdate, and componentWillUnmount, typically used in class components.
