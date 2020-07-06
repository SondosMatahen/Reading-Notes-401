## Context
- Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.
- Context is designed to share data that can be considered “global” for a tree of React components.
- Context is primarily used when some data needs to be accessible by many components at different nesting levels.

### Attach to context  
- Wrap your component with, and use a function to “get” the context object itself  
- Statically declare a connection to the context provider and then use.  
