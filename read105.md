## What is the single responsibility principle and how does it apply to components?
- An fundamental rule to consider when writing React components is the single responsibility principle. Single responsibility principle (abbreviated SRP) requires a
component to have one reason to change. A component has one reason to change when it implements one responsibility, or simpler when it does one thing.


## What does it mean to build a ‘static’ version of your application?

- Here is a direct quote: The easiest way is to build a version that takes your data model and enders the UI but has no interactivity. To build a static version of your app that renders your data model, you'll want to build components that reuse other components and pass data using props.

## What are the three questions you can ask to determine if something is state?
- These questions come directly from the React doc linked at the top of this page)

If the answer it yes to any of these questions, it is likely not state.


## How would you break a mock into a component heirarchy?
- A mock design of a feature on a page should be broken down according to how many separate elements are within it. One could draw boxes around the different items that have different functionalities.