# React and Forms

## React Docs - Forms

*What is a 'Controlled Component?*

A controlled component are those in which form's data is handled by a component's state. Takes a current value through props and makes different changes on selected callbacks, such as onClick, onChange etc.

*Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.*

Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types into the form.

*How do we target what the user is entering if we have an event handler on an input field?*



## The Conditional (Ternary) Operator Explained

*Why would we use a ternary operator?*

A ternary operator evaluates a condition and executes a block of code based on the condition. The ternary operator evaluates the test condiition, if the condition is true, expression1 is executed, if false, expression 2 is executed

*Rewrite the following statement using a ternary statement:*

```js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

```js
if (condition) {
  value if true;
 } else {
  value if false;
 }
 ```

This could also be written as: ``` x === y ? console.log(true) : console.log(false);```
