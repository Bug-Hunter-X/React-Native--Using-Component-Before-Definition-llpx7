# React Native: Using Component Before Definition

This repository demonstrates a common yet easily overlooked error in React Native: attempting to use a component before it has been fully defined.  This often leads to runtime errors or unexpected behavior.

## Problem
The `BugComponent.js` file showcases the issue. It attempts to render `ComponentB` before `ComponentB` has been defined in the file, leading to the error `ComponentB is not defined`.

## Solution
The `FixedComponent.js` file provides a corrected version. It ensures that all components are defined and accessible before being rendered.

## How to Reproduce
1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app using a React Native environment.
4. Observe the error in `BugComponent` and the correct rendering in `FixedComponent`.