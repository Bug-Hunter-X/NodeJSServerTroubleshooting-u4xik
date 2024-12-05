# Node.js Server Not Responding to Requests

This repository demonstrates a common issue in Node.js where a server starts but fails to respond correctly to incoming HTTP requests.  The problem arises from improper handling of asynchronous operations within the request handling callback.

## Bug Report
The provided `bug.js` file contains a server implementation that listens on port 3000. Although it starts successfully, it does not respond to requests.  This is because the server is not correctly handling asynchronous operations.  The solution involves ensuring that responses are sent appropriately within the request callback.