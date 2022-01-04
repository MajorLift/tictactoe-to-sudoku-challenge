### Master the Full Stack with the Tic-Tac-Toe to Sudoku Challenge!
#### I. Tic-Tac-Toe: *Frontend - React, Redux*
  1. Implement a Tic-Tac-Toe game in **TypeScript** using **React** class components.
  2. Refactor to use **Function Components** and **useState**, **useEffect** hooks.
  3. Refactor to use **Context API** and **useReducer**.
  4. Refactor to use **Redux** and **Redux Toolkit** to handle global state.
#### II. Sudoku: *Polymorphism, Advanced Algorithms*
  1. Refactor into **Generic Components** and implement a standard nine-3x3-blocks Sudoku game that can display sample puzzles and user input. 
  2. Write a checker to verify the legality of each move. 
  3. Write an automated solver using **Backtracking** with **Forward Checking**.
  4. Rewrite into a two-player competitive game. Write an optimized solver that memoizes a pruned search tree by performing full **Look-Ahead**, and optionally marks illegal squares red on each turn.
  5. Write a Sudoku game generator that outputs puzzles with unique solutions and no redundant hints.
  6. Generalize components to support any valid Sudoku game of arbitrary order n.
  7. Generalize for n players.
  8. (Generalize for rectangular Sudoku.)
  9. (Reuse the components to implement Checkers. Chess or Go even! Take an open source engine and go wild with any grid-based board game you desire.)
#### III. Online Multiplayer: *Backend - Event-Driven Architecture, Microservices*
  1. Write **Async Middleware** in the frontend and deploy a **REST API** to implement "correspondence chess" style gameplay.
  2. Using **WebSockets**, stream pub/sub messages over **AWS API Gateway** and **AWS Lambda** for real-time remote gameplay.
  3. Refactor to use **GraphQL Subscriptions** with **AWS AppSync** instead, and implement *time attack* mode, where the players don't take turns, but compete to fill as many squares as quickly as possible. Avoid race conditions.
  4. Refactor and scale to support multiple game room instances, each with multiple(>2) players and spectators by deploying a messaging system like **Apache Kafka** or **RabbitMQ**.
  5. Add **WebRTC** video chat and WebSockets cursor position sharing for a more social interactive experience. 
