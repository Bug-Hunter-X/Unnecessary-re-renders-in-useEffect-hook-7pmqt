# Unnecessary Re-renders in React's useEffect Hook

This repository demonstrates a common React performance issue: an inefficient use of the `useEffect` hook. The provided `MyComponent` causes unnecessary re-renders and console logs on every state update.

The solution showcases how to optimize this by selectively updating useEffect only when necessary changes occur.