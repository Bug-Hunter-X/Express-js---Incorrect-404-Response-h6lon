# Express.js 404 Response Bug
This repository demonstrates a common error in Express.js applications where a 404 error is returned as plain text instead of a JSON object.  The bug is present in `bug.js`, and the solution is in `bugSolution.js`.

**Bug:** The application fails to send a JSON response when a user is not found, resulting in a less user-friendly and potentially problematic response for client applications expecting JSON.

**Solution:** The `bugSolution.js` file corrects this by sending a JSON response with an appropriate error message and status code.