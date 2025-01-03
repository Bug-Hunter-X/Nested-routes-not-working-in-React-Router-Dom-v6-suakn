# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem is that nested routes, while defined correctly, fail to render when navigating to them. 

The `bug.js` file contains the flawed implementation.  The `bugSolution.js` file provides the corrected code and explanation.

## Problem

The application uses nested routes, but only the top level routes render properly.  Attempts to navigate to nested routes result in a blank page or rendering the parent route only.

## Solution

The solution involves careful examination of the route definitions and the use of the `useParams` hook.  This ensures proper nesting and rendering of child routes. The solution file demonstrates the correct implementation.