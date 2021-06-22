## What is a ‘Controlled Component?
- A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange . A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component.


## forms?
- The component renders a form control with Bootstrap styling

- The component directly renders the or other specified component.

- If your application contains a large number of form groups, we recommend building a higher-level component encapsulating a complete field group that renders the label, the control, and any other necessary components.

- Provide valuable, actionable feedback to your users with form validation feedback.

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. no Specifying the value prop on a controlled component prevents the user from changing the input unless you desire so. If you’ve specified a value but the input is still editable, you may have accidentally set value to undefined or null. How do we target what the user is entering if we have an event handler on an input field? handleChange(event) { this.setState({value: event.target.value}); }
## Why would we use a ternary operator?
- The ternary operator in the react js works in the same way how it works in the Javascript
With the help of the ternary operator, we can display the contents on the basis of one 
condition where everything depends on the condition true and false we can put the 
contents on the conditional basis.