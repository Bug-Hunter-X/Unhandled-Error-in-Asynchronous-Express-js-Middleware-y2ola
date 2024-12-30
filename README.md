# Unhandled Error in Asynchronous Express.js Middleware

This repository demonstrates a common error in Express.js applications: unhandled errors within asynchronous middleware.  The `bug.js` file showcases an Express.js server that simulates an asynchronous operation.  If this operation fails (a random chance in this case), an error is thrown without proper handling, causing the server to crash.

The `bugSolution.js` file provides a corrected version that uses error handling middleware to gracefully manage exceptions and prevent crashes.