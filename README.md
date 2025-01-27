# JavaScript Type Coercion Pitfall with Null and Undefined

This repository demonstrates a subtle but common error in JavaScript related to how the language handles null and undefined values, particularly during type coercion.

The `bug.js` file contains a function that attempts to handle both null and undefined input.  However, it only explicitly checks for null, leading to unexpected behavior when undefined is passed in.

The `bugSolution.js` file provides a corrected version of the function, showcasing best practices for handling both null and undefined inputs to avoid type coercion problems.

This example highlights the importance of explicitly checking for both null and undefined values to prevent unexpected results and ensure robust code.