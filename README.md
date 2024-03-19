# Context API Basic Project

This project aims to demonstrate the fundamental usage of React's Context API in a simple and understandable manner. Through a basic login application, it illustrates how Context API facilitates the management and sharing of state across different components without the need for prop drilling.

## Purpose of Context API

Context API in React provides a way to pass data through the component tree without having to pass props manually at every level. It is particularly useful for sharing state among components that are far apart in the component hierarchy.

## Project Overview

The project consists of three main components:

1. **UserContext**: Defines a context using `React.createContext()` to store user-related information.
2. **UserContextProvider**: Wraps the application with a context provider to supply the user data to components.
3. **Login** and **Profile**: Components that interact with the user context. Login allows users to input their credentials, while Profile displays a welcome message for authenticated users.

## How it Works

1. **UserContext**: Created using `React.createContext()` to define a context.
2. **UserContextProvider**: Utilizes `useState` to manage the user state. It provides the user data through the context provider.
3. **Login Component**: Utilizes `useContext` hook to access the user context. When the user submits their credentials, it updates the user state using the `setUser` function provided by the context.
4. **Profile Component**: Retrieves user data from the context using `useContext`. If no user is logged in, it displays a message prompting the user to login.

## Why it's Simple

This project simplifies the understanding of complex state management concepts by breaking them down into digestible parts. By demonstrating how Context API eliminates the need for prop drilling and centralizes state management, it lays a foundation for understanding more advanced state management techniques in React.

## How to Run

To run the project:

1. Clone the repository.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Open your browser and visit `http://localhost:3000` to view the application.

## Conclusion

By following along with this basic project, developers can grasp the essence of React's Context API and its role in simplifying state management within React applications. This project serves as a starting point for understanding more complex state management patterns and their implementations.

## Credits

This project is inspired by the teachings of Hitesh Choudhary, popularly known as "Hitesh Sir". His instructional content has helped countless developers learn and understand various aspects of web development, including React.

You can follow Hitesh Sir on YouTube for more insightful content.

- [YouTube](https://www.youtube.com/playlist?list=PLu71SKxNbfoDqgPchmvIsL4hTnJIrtige)

