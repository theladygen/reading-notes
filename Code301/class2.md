# Class 1

## Reading

### [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1.***Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?***

Render happens first.

2.***What is the very first thing to happen in the lifecycle of React?***

The constructor is created.

3.***Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`***

* `constructor`
* `render`
* `componentDidMount`
* `React Updates`
* `componentWillUnmount`

4.***What does `componentDidMount` do?***

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.

## Videos

### [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1.***What types of things can you pass in the props?***

Props are used to pass in various types of data as arguments to a component.

2.***What is the big difference between props and state?***

State is handled inside a component and you can update it inside the component, where props are passed into a component and handled outside of the component and must be updated outside the component.

3.***When do we re-render our application?***

When you change the state inside an application or pass in new props it will re-render that section of the application.

4.***What are some examples of things that we could store in state?***

Counters (votes/likes/etc), forms (input elements/checkboxes/etc), or anything that will be updated inside of the component.

## Bookmark and Review

[React Docs - State and Lifecycle](https://legacy.reactjs.org/docs/state-and-lifecycle.html)

[React Docs - handling events](https://legacy.reactjs.org/docs/handling-events.html)

[React Tutorial through ‘Developer Tools’](https://react.dev/learn/tutorial-tic-tac-toe)

[React Bootstrap Documentation](https://react-bootstrap.github.io/)
[Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)

[Netlify](https://www.netlify.com/)
