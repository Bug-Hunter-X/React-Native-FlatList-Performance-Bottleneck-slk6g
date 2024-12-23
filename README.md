# React Native FlatList Performance Issue

This repository demonstrates a common performance problem in React Native's `FlatList` component when handling large datasets and complex item rendering. The `renderItem` function's inefficiency leads to dropped frames and a poor user experience.

The `FlatListBug.js` file contains the buggy implementation, while `FlatListBugSolution.js` provides an optimized solution using techniques like memoization, virtualization, and efficient data structures.

## Reproduction

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npx react-native run-android` or `npx react-native run-ios` to start the app.
4. Observe the performance with a long list. You will see performance degradation in the original implementation. The solution demonstrates improvement with optimized techniques.