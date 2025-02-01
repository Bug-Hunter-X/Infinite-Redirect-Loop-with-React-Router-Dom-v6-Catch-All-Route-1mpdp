# React Router Dom v6 Catch-All Route Bug

This repository demonstrates a bug in React Router Dom v6 where a catch-all route (`/*`) causes an infinite redirect loop.  The issue arises from a conflict or misconfiguration of routes, potentially involving nested routes or route parameters. The solution involves careful route order or using a more specific route for error handling.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the infinite redirect loop in the browser's console.

## Solution

The solution is provided in `AppSolution.js`.  By adjusting route order, the conflict is resolved and the issue is corrected.