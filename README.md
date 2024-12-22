# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The bug causes an infinite rendering loop due to a missing dependency array in the `useEffect` hook. 

The `bug.js` file contains the buggy code. The `bugSolution.js` provides the corrected implementation.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the infinite loop in the console and browser.

## Solution

The solution involves adding a dependency array to the `useEffect` hook to specify that the effect should only run when the `count` variable changes.