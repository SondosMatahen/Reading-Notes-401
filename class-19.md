## Message Queues:
- A message queue is a form of asynchronous service-to-service communication used in serverless and microservices architectures.
- Messages are stored on the queue until they are processed and deleted. 
- Each message is processed only once, by a single consumer.

## What is a message?
- A message is a package of information categorized by queue and event
- queue: Which general bucket does this message belong 
- event: What event has happened
- payload: data associated with the event

## Real Time vs Queued Messaging
>- messages brokered by the server.
>- They come in are processed and are immediately broadcast out to subscribers.
>- Should a subscriber at any point lose connection with the server
>- any messages broadcast by the server will clearly be missed by the client.
>-These are known as “Real Time” messaging systems.

##Namespace:
- It is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your codebase includes multiple libraries.
