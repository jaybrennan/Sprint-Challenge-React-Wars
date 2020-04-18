# Answers

1. What is React JS and what problems does it solve? Support your answer with concepts introduced in class and from your personal research on the web.

ReactJS is a JS library for building user interfaces. React reduces server load and speeds up web applications with state management. It only updates components as the data changes. Data is only reloaded when state changes.

1. Describe component state.

Component state holds information within a component and updates the component to reflect a new value and/or state as the data within it changes. This is especially useful in web applciations where lots of data is getting updated.

1. Describe props.

Props are properties of an object using dot notation. Typically you use this with objects and with API requests to pull certain data out of the object/API to display within a component. 

1. What are side effects, and how do you sync effects in a React component to changes of certain state or props?

Side effects happen when a component updates and it causes something on the global scope to update/change as well. For example if you were to have a football scoreboard that is keeping track of the score, when points are added it will reset the downs as well. The downs can be in another component separate from the points component. You can sync effects in React using useEffect.

