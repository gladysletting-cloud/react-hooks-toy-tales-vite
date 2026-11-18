# Toy Tales

A React app for managing a toy collection. It connects to a JSON Server backend and supports full CRUD: view, add, like and donate (delete) toys.

![Toy Tales screenshot](screenshot.png)

## Features

- **View toys:** all toys load from the backend when the page opens (GET).
- **Add a toy:** the "Add a Toy" form creates a new toy with 0 likes (POST).
- **Like a toy:** the Like button adds 1 like and keeps the toy in the same position (PATCH).
- **Donate a toy:** the Donate button removes the toy from the page and the backend (DELETE).

## Setup

1. Clone the repo: `git clone <your-repo-url>`
2. Install dependencies: `npm install`
3. Start the backend: `npm run server`
4. In a second terminal, start the app: `npm run dev`
5. Run the tests: `npm run test`

## Built with

React, Vite, JSON Server

## Author

Gladys Chepchumba Letting