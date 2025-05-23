# Development Setup

This guide outlines how to run the local development environment for both the Laravel backend and the Vue frontend.

## 1. Run the Laravel backend

Navigate to the Laravel project directory and start the server with one of the following commands:

```bash
# Option 1: Use the built-in PHP server
php artisan serve

# Option 2: Run via Laravel Octane (requires the octane package)
php artisan octane
```

## 2. Start the Vue frontend with Vite

From the Vue project directory, run:

```bash
npm install    # Install dependencies if needed
npm run dev    # Start Vite development server
```

## 3. Start the WebSocket server

In another terminal, run the WebSocket server:

```bash
php artisan websockets:serve
```

The backend, frontend, and WebSocket server can now communicate locally.
