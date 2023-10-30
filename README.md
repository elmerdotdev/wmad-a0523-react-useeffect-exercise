# React useEffect Exercise

## Exercise 1

1. Create a state called `isToggle` with a default boolean value of *false*
2. Add a useEffect hook with `isToggle` as the dependency
3. Create a button that toggles the state value of `isToggle` to either true/false
4. Inside your useEffect, change the background color of a `<div>` to black if `isToggle` is false, to white if `isToggle` is true
5. Use `useRef` to target the `<div>` element

## Exercise 2

1. Create a state called `data` with a value of an empty array
2. Inside a `useEffect` hook, pull data from `https://dummyjson.com/products`
3. Add a link to each `<li>` that when clicked, will change the product's title to *'UNAVAILABLE'*
