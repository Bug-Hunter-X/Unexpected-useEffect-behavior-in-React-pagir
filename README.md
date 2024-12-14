# Unexpected useEffect Behavior in React

This repository demonstrates a common issue with the `useEffect` hook in React where it runs more often than intended.  The example showcases a counter component where the useEffect logs to the console after every render, even though the dependency array specifies that it should only run when the `count` state variable changes. This can lead to unnecessary re-renders and performance problems, especially in complex components.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version demonstrating the proper use of the `useEffect` dependency array.