# A High level Overview of React

*What is React?*

React is an agnostic user interface library. We use it to create user interfaces, websites, apps etc. It doesn't care where you send your final components,
and it will always need to be used with a second library, such as, 'React360', 'ReactDOM', 'ReactServer'. It can work in a lot of different environments.

*What is a component?*

A component is a small piece of code that fills a certain part of the UI that you're building with React.

*What is the dataflow of React?*

Data flows down one way through a React app. Data flows down from one component to each other, using simple functions in javascript. The data from the parent is known as 'properties' or 'props', for short. Child components cannot update or modify data by themselves, which makes sure that the clean data flow is adhered to.

*How do we make a React element a DOM element?*

React does not become ReactDOM, until it is passed through ReactDOM.

*React is a User Interface ______.*

React is a User Interface Library.

*Which direction does data flow in React?*

One-way data flow, or unidrectional. From parent to child.

*Every component manages its own ____.*

Every component manages its own data. This is done by React having a built-in object called 'state'. So this means that unlike props, components cannot pass data with state, but they can create/manage data.
