1.What is React? What are its features.
React  is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications.
React allows developers to create large web applications that can change data, without reloading the page.
It's used for handling the view layer for web and mobile apps.

Its features:-
Virtual DOM.
Sinle Page Application.
JavaScript XML or JSX.
component  based structure.
easy Learning Curve.
Large coumminity support.



2. What is Virtual DOM ?
DOM stands for 'Document Object Model'.It is a structured representation of the HTML elements that are present in a webpage. DOM represents the entire UI of your application. The DOM is represented as a tree data structure.
 Virtual Dom is a collection of modules designed to provide a declarative way to represent the DOM for an application.
 A virtual DOM object is a representation of a DOM object, like a lightweight copy.

 The virtual DOM (VDOM) is a programming concept where an ideal, or “virtual”,
 representation of a UI is kept in memory and 
synced with the “real” DOM by a library such as ReactDOM.
 This process is called reconciliation.


3.What is SPA ?
In Single Page Application when you  navigate, the browser will only rerender the content without refreshing the website.




4.React life cycle?
There are three Phases of React LifeCycle:-

1. Mounting
2.Updating
3.Unmounting

In Mounting Phase:-

(i)Constructor
(ii)getDerivedStateFromProps
(iii)render
(iv)componentDidMount

In Updating Phase:-
(i)getDerivedStateFromProps
(ii)shouldComponentUpdate
(iii)render
(iv)getSnapShotBeforeUpdate
(v)componentDidUpdate

In Unmounting Phase:-

(i)componentWillUnmount

Explanation:-

In Mounting Phase:-

(i)Constructor:-Constructor method is the first method which is called, when the component is initiated,and it is used to set up the intial state and initial values.

(ii)getDerivedStateFromProps:- The getDerivedStateFromProps() method is called right before rendering the element(s) in the DOM. This is the natural place to set the state object based on the initial props. It takes state as an argument, and returns an object with changes to the state.

(iii)render:- The render() method is required, and is the method that actually outputs the HTML to the DOM.

(iv)componentDidMount:- The componentDidMount() method is called after the component is rendered. This is where you run statements that requires that the component is already placed in the DOM.

In Updating Phase:-


(i)getDerivedStateFromProps:- This is the first method that is called when a component gets updated. This is the natural place to set the state object based on the initial props.

(ii)shouldComponentUpdate:- In the shouldComponentUpdate() method you can return a Boolean value that specifies whether React should continue with the rendering or not. The default value is true.

(iii)render:-The render() method is of course called when a component gets updated, it has to re-render the HTML to the DOM, with the new changes.

(iv)getSnapShotBeforeUpdate:-In the getSnapshotBeforeUpdate() method you have access to the props and state before the update, meaning that even after the update, you can check what the values were before the update.

(v)componentDidUpdate:-The componentDidUpdate method is called after the component is updated in the DOM.

In Unmounting Phase:-

(i)componentWillUnmount:- The componentWillUnmount method is called when the component is about to be removed from the DOM.







5.Difference between Class Component and Functional 
Component?
Functional Component
(i)A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element.
(ii)There is no render method used in functional components.
(ii)Also known as Stateless components as they simply accept data and display them in some form
(iv)Constructors are not used.

Class Component
(i)A class component requires you to extend from React. Component and create a render function which returns a React element.

(ii)Also known as Stateful components because they implement logic and state.
(iii)It must have the render() method returning JSX (which is syntactically similar to HTML)
(iv)Constructor are used as it needs to store state.







6.What is routing ?
ReactJS Routing is mainly used for developing Single Page Web Applications. React Router is used to define multiple routes in the application. When a user types a specific URL into the browser, and if this URL path matches any 'route' inside the router file, the user will be redirected to that particular route.
browser router
all the router is wrapped in routes
