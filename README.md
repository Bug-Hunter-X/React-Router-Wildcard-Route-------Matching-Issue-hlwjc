# React Router Wildcard Route Issue

This repository demonstrates a common issue with React Router's wildcard route ('*').  The wildcard route, intended to catch any unmatched paths, can inadvertently match paths even when a more specific route exists.

This leads to unexpected routing behavior, often preventing other routes from working as intended.

The `bug.js` file shows the problem. The solution is demonstrated in `bugSolution.js`.