## What is functional programming?
-  is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions. Contrast with object oriented programming, where application state is usually shared and colocated with methods in objects.
## What is a pure function and how do we know if something is a pure function?
- A pure function is a function which: Given the same input,
will always return the same output. Produces no side
effects.
## What are the benefits of a pure function?
- pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration
## What is immutability?
- the state of not changing, or being unable to be changed: His poetry conveys a sense of the mmutability of nature.
## What is Referential transparency?
pure functions + immutable data = referential transparency NodeJS:

Split code up into logical modules Can call modules whenever needed Bare minimum added in each module To run a specific file through node in the console you can type node file_name.extension or node file_name To bring one file into another using node is by typing require './file_name.extension' at the top of the file where needed To bring in one file, you must say module.exports = function_name or module.exports = class_name at the bottom of the file the data is sent out from
## What is a module?
- one part (or file) with a specific functionality to achieve a part of a larger goal (many files / functions / classes)
## What does the word ‘require’ do?
- import data from file another 
