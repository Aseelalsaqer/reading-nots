# There are two types of “model” data in React: props and state.

To make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state.

React is all about one-way data flow down the component hierarchy.

For each piece of state in your application:


* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.


* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
