# Component Based UI

The basic building blocks of a react app are components. A component is a piece of UI on the page that has its own tag.

A component is similar to an html tag in the fact that it's surrounded by pointy brackets and depict a text of code. But they’re different because React components are custom and only require one tag.

JSX is a JavaScript extension that allows users to write code similar to HTML in JavaScript. It is recommended for React applications because of its convenience and because it allows us to combine html and javascript.

To write JavaScript expressions in javascript, you would have to surround the JavaScript in curly Brackets `{}`

React has no special features for conditional logic, so just use if else statements like in regular JavaScript.

To listen to users' inputs in React, use an event handler function that is built into React. `onClick`,`onSubmit`, etc.

Hooks are built in functions in React, they can only be used at the start of components. Hooks start with the word `use`.

For two components to share data you would need to add the state to its parent container.

## Render and Commit

The three steps for refreshing a Render UI are `triggering`, `rendering`, and `committing`.

To trigger an update after its initial commit, use a `set` function to update the components `state`, this will refresh the component.

For the first render, React will create eack DOM node. For re-renders React will track which components have changed and update that one only.

After the DOM is updated all that is left to do is for the browser to update the screen

## Additional Questions

One pattern you'll notice on the style guide is that the style commands are written inside the component tags before the closing tag.

For this module I am excited to revisit React and see how it will interact with the new concepts that we learned for our backend.

At the end of this class my goal is to practice previously learned concepts so that I learned from this course by the end.
