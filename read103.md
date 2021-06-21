## react docs -link :
## What does .map() return?
- The map() function is used to iterate over an array and manipulate or change data items. In React, the map() function is most commonly used for rendering a list of data to the DOM Each time the callback executes, the returned value is then added to a new array.

## Each list item needs a unique ... unique key........
## What is the purpose of a key?
- A “key” is a special string attribute you need to include when creating lists of elements in  React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists.

## the spread operator?
## what is spread operatpr?
- he Spread operator lets you expand an iterable like an object, string, or array into its elements while the Rest operator does the inverse by reducing a set of elements into one array.
## List 2 things that the spread operator can do?
- copping array
- merge two object 
-compine two array

## Give an example of using the spread operator to combine two arrays.?
- const arr1 = [1,2,3]
- const arr2 = [4,5,6]
- const arr3 = [...arr1, ...arr2] //arr3 ==> [1,2,3,4,5,6]



- const a = ['to', 'code'];
- const b = ['learning', ...a, 'is', 'fun']; 
- console.log(b); //> ['learning', 'to', 'code', 'is', 'fun']
