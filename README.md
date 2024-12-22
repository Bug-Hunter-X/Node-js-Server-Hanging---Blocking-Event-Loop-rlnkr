# Node.js Server Hanging - Blocking Event Loop

This repository demonstrates a common Node.js issue: blocking the event loop with a synchronous, long-running operation.  The server hangs for 5 seconds on each request, resulting in poor performance and unresponsive behavior.

The `server.js` file contains the buggy code.  The `serverSolution.js` file shows how to resolve this using asynchronous operations.