# React Native: Cannot read properties of null (reading '...')

This repository demonstrates a common React Native error: 'Cannot read properties of null (reading '...').' and provides a solution.

The error occurs when attempting to access a property of an object that is null or undefined.  This often happens when dealing with asynchronous data fetching or component state management.

**Problem:** The `bug.js` file showcases a scenario where an attempt is made to access the `name` property of a `user` object before it has been successfully fetched and assigned a value. This results in the error.

**Solution:** The `bugSolution.js` file provides a solution using optional chaining (?.) and nullish coalescing (??). These operators provide safe access to properties even if the object is null or undefined.