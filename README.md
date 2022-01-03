### Master the Full Stack with the Tic-Tac-Toe to Sudoku Challenge!
#### I. Tic-Tac-Toe
  1. Implement a Tic-Tac-Toe game using React **class components**.
  2. Refactor to use **function components** and **useState**, **useEffect** hooks.
  3. Refactor to use **Context API** and **useReducer**.
#### II. Sudoku
  1. Using **TypeScript**, refactor Board and Box as **Generic Components** to implement a standard nine-3x3-blocks Sudoku game with sample input puzzles. Write checker to verify the legality of the player's moves at each turn.
  2. Write automated solver using **Backtracking** with **Forward Checking**.
  3. Rewrite into two-player competitive game. Write an optimized solver that memoizes a pruned search tree by performing full **Look-Ahead**, and optionally marks illegal squares red on each turn.
  4. Write a Sudoku game generator that outputs puzzles with unique solutions and no redundant hints.
  5. Generalize components to support any valid Sudoku game of arbitrary order n.
  6. Generalize for n players.
  7. (Generalize for rectangular Sudoku.)
#### III. State Management
  1. Refactor to use **Redux** and **Redux Toolkit** to handle global state.
  2. Refactor to use **Zustand** and **Immler** to handle global state.
#### IV. Online Multiplayer
  1. Write **Async Middleware** and deploy a **REST API** to implement "correspondence chess" style gameplay.
  3. Using **WebSockets**, stream pub/sub messages and deploy over **AWS API Gateway** and **Lambda** for real-time remote gameplay.
  3. Refactor to use **GraphQL Subscriptions** with **AWS AppSync** instead.
  4. Refactor and scale to support multiple game room instances, each with multiple(>2) players and spectators by deploying a message broker like **RabbitMQ** in a distributed architecture. 
  5. Add **WebRTC** video chat and **WebSockets** cursor position sharing for interactive experience. 
