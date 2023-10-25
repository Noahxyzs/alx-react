React.js, often referred to as React, is a JavaScript library for building user interfaces1. It’s used to build single-page applications and allows us to create reusable UI components1.

Here’s a simple example of a React component:

JavaScript
AI-generated code. Review and use carefully. More info on FAQ.

import React from 'react';
import ReactDOM from 'react-dom/client';

function Hello(props) {
  return <h1>Hello World!</h1>;
}

const container = document.getElementById("root");
const root = ReactDOM.createRoot(container);
root.render(<Hello />);
This code creates a function component called Hello that returns a single React element. This element is a simple piece of the UI1.

React doesn’t prescribe how to do routing and data fetching. To build an entire app with React, you might need a full-stack React framework like Next.js or Remix2.

If you’re new to React, you might find the React tutorial on W3Schools helpful. It provides examples and exercises that can help you understand and learn how to use React
