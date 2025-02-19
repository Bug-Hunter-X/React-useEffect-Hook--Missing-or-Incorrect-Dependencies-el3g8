# React useEffect Hook: Missing or Incorrect Dependencies

This repository demonstrates a common error in React's `useEffect` hook: issues with dependency arrays.

The `bug.js` file shows an example where the dependency array is incorrect, leading to an infinite loop. The `bugSolution.js` file provides the corrected version.  Understanding how dependency arrays control when effects run is crucial for building reliable React applications.

## How to reproduce the bug:

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the console output and the behavior of the counter.

## How to fix the bug:

Refer to `bugSolution.js` for the corrected code, where the dependency array is correctly defined to only trigger the effect when the `count` value changes.