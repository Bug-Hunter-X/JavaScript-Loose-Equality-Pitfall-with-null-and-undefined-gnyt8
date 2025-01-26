# JavaScript Loose Equality Pitfall with null and undefined

This repository demonstrates a common JavaScript pitfall involving loose equality (==) and the handling of null and undefined values.  The `bug.js` file contains code that incorrectly treats null and undefined as 0 due to the use of loose equality. The `bugSolution.js` file provides a corrected version using strict equality (===).