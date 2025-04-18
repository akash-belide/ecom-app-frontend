# Ecom-App Frontend

A React & Vite   frontend for the Ecom-App backend. This single‑page application provides a user-friendly interface to manage an e‑commerce product catalog—listing, searching, adding, updating, and deleting products, plus image uploads and previews.

> ⚙️ **Spring Boot Backend**: The corresponding REST service is available at [https://github.com/akash-belide/ecom-app](https://github.com/akash-belide/ecom-app).

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Features
- Responsive UI for browsing and managing products
- Create, read, update, delete (CRUD) operations
- Image upload and preview support
- Keyword-based product search
- Toggle Dark/Light Mode
- Seamless integration with Spring Boot backend API

## Technologies
- React 18
- Tailwind CSS
- Axios for HTTP requests
- React Router for client-side routing

## Getting Started
### Prerequisites
- npm or Yarn

### Setup & Run
```bash
# Clone the repo
git clone https://github.com/akash-belide/ecom-app-frontend.git
cd ecom-app-frontend

# Install dependencies
npm install   # or yarn install

# Start development server
npm run dev     # or yarn start
```
By default, the app expects the backend API at `http://localhost:8080/api`. To change this, see [Configuration](#configuration).

## Configuration
Create a `.env` file in the project root to override the default API URL:
```env
REACT_APP_API_BASE_URL=https://your-backend-domain.com/api
```


## Project Structure
```
ecom-app-frontend
├── public
│   └── index.html
├── src
│   ├── components      # Reusable React components
│   ├── pages           # Route-level page components
│   ├── services        # API client (Axios) wrappers
│   ├── App.jsx
│   └── main.jsx        # ReactDOM entry point
├── .env
├── package.json
└── tailwind.config.js
```

## Contributing
Contributions are welcome!

---
Built by Akash Belide


