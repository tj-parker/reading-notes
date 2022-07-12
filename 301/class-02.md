# Class 02 Reading Notes

## React Lifecycle

In a React lifecycle, first comes the render phase, then the pre-commit phase, and then the commit phase (componentDidMount)

The constructor for a React component is called before it is mounted

constructon --> render --> React updates --> componentDidMount --> componentWillUnmount

componentDidMount() if invoked immediately after a component is mounted. Anything that needs to be loaded that uses a network request or initializes the DOM should go here, and it is also a good place to set up any subscriptions

## React State Vs Props

You can pass what you want to initialize your component to and what you want your component to render

State is inside of a component, while props is passed into a component from outside.

An application is re-rendered properly when a change is store in state

State is usuful for storing data that is continuously updated based on user input, such as a form
