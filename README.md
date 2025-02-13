# React Native TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications: `TypeError: Cannot read properties of undefined (reading 'property')`.  This error typically arises when attempting to access a property of an object that's currently `undefined` or `null`. The example focuses on data fetching scenarios, a frequent source of this issue. 

The `bug.js` file showcases the erroneous code, while `bugSolution.js` presents the corrected implementation.  Understanding this error is crucial for building robust React Native applications.

## Reproduction

Clone the repository and run the provided example. You'll observe the error in the initial render due to the asynchronous nature of data fetching. 

## Solution

The solution involves using optional chaining (?.) and nullish coalescing (??), or a conditional rendering approach to gracefully handle potential `undefined` or `null` values before accessing their properties.  See `bugSolution.js` for a detailed solution. 