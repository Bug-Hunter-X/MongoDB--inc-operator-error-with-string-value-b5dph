# MongoDB $inc operator error with string value
This repository demonstrates a common error in MongoDB update operations involving the `$inc` operator.
The `$inc` operator is used to increment a numeric field in a document.  However, if a string value is provided instead of a number, an error will occur.

## Bug
The `bug.js` file contains code that attempts to increment a counter field using a string value. This results in an error because MongoDB expects a numerical value for the increment.

## Solution
The `bugSolution.js` file shows how to correctly use the `$inc` operator with a numeric value to increment the field successfully.

To run the code, make sure you have MongoDB installed and running.  You can then execute the files using a MongoDB shell or a Node.js environment.