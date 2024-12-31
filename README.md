# MongoDB $inc operator error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string is provided as the increment value, MongoDB will throw an error. 

The `bug.js` file contains code that reproduces this error. The `bugSolution.js` file provides a corrected version that uses the correct numeric value for the increment operation. 