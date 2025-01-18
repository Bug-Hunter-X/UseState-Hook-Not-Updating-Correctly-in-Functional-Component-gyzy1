# React 19 useState Hook Bug

This repository demonstrates a bug encountered in React 19 where the `useState` hook within a functional component fails to update correctly.  The counter does not increment as expected.

## Bug Description

The `useState` hook in `MyComponent` should increment the `count` state variable when the button is clicked. However, the count remains unchanged.  The issue is likely related to how the state update function is used within the `incrementCount` function.

## Solution

The provided solution utilizes the functional update approach of `setCount` to ensure the state update is applied correctly and reactively.