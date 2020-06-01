## Routing:
- Routing refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing.
- These routing methods specify a callback function called when the application receives a request to the specified route (endpoint) and HTTP method.
-In fact, the routing methods can have more than one callback function as arguments. With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.

## Express 4.00:
- Express 4.0 comes with the new Router. Router is like a mini express application. It doesn't bring in views or settings, but provides us with the routing APIs like .use, .get, .param, and route.
- We will house our routes in the server.js file.
- We'll only need one dependency, Express.

## Express Router:
- What exactly is the Express Router? It is a mini express application without all the bells and whistles of an express application, just the routing stuff. Let's take a look at exactly what this means. We'll go through each section of our site and use different features of the Router.
