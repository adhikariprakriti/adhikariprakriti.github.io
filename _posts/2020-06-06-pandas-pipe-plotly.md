---
title: Reusable Button Component in React
categories: [React]
summary: Learn to create reusable components in React, specifically focusing on a Button component.
date: 2020-10-04 20:45:00 +0545
link: https://medium.com/@pas074bct024/reusable-button-component-in-react-485799811920
---

React is made up of a bunch of Components in the Component Tree. Components let us split the entire UI into independent, reusable pieces. Reusable Components are those components which are used in various part of react application. Reusable components speed up the development process ensuring that code is simple, easy to understand and maintenance is stress-free. Such components should be generic i.e. free from any complex business logic.

Let’s create a button component in React;


The Button component renders a button. The above button component is not really reusable because it is hardcoded. Every Button component implements the same behavior and is of the same size and colors.


But let us consider the situation where we need to create different multiple buttons of different behaviors, sizes, and colors.

In your Button.js file add the following code to it:


Button Component receives three properties via props.

The handleClick property is a callback function that is called when the user clicks on the button. This helps us to add different functionality to our button.

The children’s property is for the content of the button. We display the button content dynamically using React’s built-in children’s property (props.children).

The type property helps to dynamically apply different ClassNames to Button component so we can easily modify button designs.

Now, we have just one component of Button but we can reuse it every time we want to create a new button with different behaviors, contents, and designs.


Buttons created using reusable Button Component
This is the power of reusability. Similarly, we can create multiple reusable react components. This helps to create highly scalable and efficient react applications.

