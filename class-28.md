## setState()
- setState() is the only legitimate way to update state after the initial state setup. 

## setState() important notes:
>- Update to a component state should be done using setState()
>- You can pass an object or a function to setState()
>- Pass a function when you can to update state multiple times
>- Do not depend on this.state immediately after calling setState() and make use of the updater function instead.

## Handling Events
- Handling events with React elements is very similar to handling events on DOM elements.
- With JSX you pass a function as the event handler, rather than a string.
- When you define a component using an ES6 class, a common pattern is for an event handler to be a method on the class.

## Forms
- HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state.
-  In React, mutable state is typically kept in the state property of components, and only updated with setState().
- Handling Multiple Inputs: When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## Converting a Function to a Class
- You can convert a function component like Clock to a class in five steps:
>- Create an ES6 class, with the same name, that extends React.Component.
>- Add a single empty method to it called render().
>- Move the body of the function into the render() method.
>- R eplace props with this.props in the render() body.
>- Delete the remaining empty function declaration.

## Components and Props
- Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
- components are like JavaScript functions, They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.
