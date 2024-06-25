# React Calculator Project

This project is a simple calculator built using React. It performs basic arithmetic operations like addition, subtraction, multiplication, and division. The project demonstrates the use of React functional components, hooks (`useState`), and event handling.

## Key Parts

### 1. State Management

We use the `useState` hook to manage the state of the calculator display. The `display` state holds the current value shown on the calculator screen.

```jsx
import React, { useState } from "react";

const Calculator = () => {
  const [display, setDisplay] = useState("");

  // Other code...
};
```
