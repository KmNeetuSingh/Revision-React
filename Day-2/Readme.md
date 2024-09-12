# React Components and Props

## Introduction
React is a JavaScript library for building user interfaces. It emphasizes creating **reusable components** to construct dynamic UIs. Components use **props** (properties) to receive data, enhancing reusability and flexibility.

---

## Components
A React component is a function or class that returns JSX (JavaScript XML) to define the UI structure. Components make UIs modular, maintainable, and reusable.

### Example:
```jsx
function Greet({ text, name }) {
  return <p>{text}, {name}</p>;
}
```

---

## Props
Props are the way components receive data from their parent. They are passed as attributes, making components dynamic. Props are read-only, ensuring a one-way data flow.

### Example:
```jsx
<Greet text="Happy Birthday" name="Bruce" />
<Greet text="Good Morning" name="Rachel" />
```

---

## Component Composition
React apps are built as a component tree, where the root component (e.g., `App`) contains child components. This hierarchy enables dividing the UI into smaller, reusable pieces.

---

## Conclusion
React's component-based architecture, combined with props, simplifies the creation of flexible, maintainable UI elements. Components encapsulate logic and presentation, while props enable data passing, ensuring efficient UI construction.

---

## Resources
- [React Official Documentation](https://reactjs.org/docs/components-and-props.html)
- [JSX](https://reactjs.org/docs/introducing-jsx.html)
