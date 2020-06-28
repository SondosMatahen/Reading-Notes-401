## Testing
- React App uses Jest as its test runner. 
- Snapshot tests are a very useful tool whenever you want to make sure your UI does not change unexpectedly.
-  you can use a test renderer to quickly generate a serializable value for your React tree.
- Shallow rendering is useful to constrain yourself to testing a component as a unit, and to ensure that your tests aren't indirectly asserting on behavior of child components.
- Static Rendering API: Use enzyme's render function to generate HTML from your React tree, and analyze the resulting HTML structure.
- Full Rendering API : Full DOM rendering is ideal for use cases where you have components that may interact with DOM APIs or need to test components that are wrapped in higher order components.

## Selenium automates browsers
- Primarily it is for automating web applications for testing purposes, but is certainly not limited to just that.
- Boring web-based administration tasks can also be automated as well.

## React Deployment
- React in development mode uses a node service to create a live website that refreshes as you write code.
