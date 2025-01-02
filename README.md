# Express.js Route Handler Missing Error Handling for Invalid User IDs

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  Specifically, the example shows a route that fetches a user by ID.  The code attempts to parse the ID as an integer but fails to handle cases where the ID is not a valid number, leading to potential crashes or unexpected behavior.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version with comprehensive error handling.