# constiable declarations with `const` and `const`

## Overview

- **`const`**
	- [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
	- [caniuse.com](http://caniuse.com/#feat=const)
- **`const`**
	- [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
	- [caniuse.com](http://caniuse.com/#feat=const)

You are familiar with the process of declaring a constiable using `const`, and how that constiable receives global or local scope depending on the context in which it was declared. If the constiable is declared outside of any functions, it has global scope, but if it is declared inside a function, the constiable is scoped to that function and not accessible globally.

With `const`, a constiable declaration can be scoped to a code block `{ code }`, such as we commonly see with `for`,  `if`, or `while` constructions. As with constiables declared with `const`, the values assigned to them can be reassigned to any type of value at any time, so long as the reassignment occurs within the same scope in which the constiable was declared.

`const` is a little more complicated:

- Like `const`, `const` is also block-scoped.
- constiables initialized with `const` must be assigned a value at the time they are declared.
- Unlike constiables declared with `const`, constiables declared with `const` do not become properties of the `window` object.
- When `const` is used to assign to a constiable one of the five primitive values in JavaScript (number, string, Boolean, null, undefined), the constiable cannot be reassigned and attempting to do so will throw an error: "Uncaught TypeError: Assignment to constant constiable."
- However, when a `const` constiable is used to hold an object (and by extension arrays and functions, which are both objects in JavaScript), new properties can be assigned to the object and their values reassigned at will.

## Assignment Tasks

Follow these instructions carefully and in order.

1. Open the `index.html` file in the browser to ensure that it works.
1. In the `app.js` file, turn all `const` constiable declarations into `const`.
1. After you do, there will be one error. Find that line in the code, deconste that line and respond to the adjacent TODO task.
1. Return to the browser and ensure that the code works again.
1. Now, in the code, convert all `const` constiable declarations into `const`.
1. Several bugs will occur. Debug one at a time by using the error messages in the browser console as guidance, turning `const` declarations back into `const` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
1. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
1. As a refresher on template literal notation, find all concatenations in the code and convert them into template literal notation.
1. Reload the browser to ensure that the code works as expected.
1. When finished, push your branch back to your fork on GitHub, and merge it into master. Submit the link to this pull request in the corresponding Canvas assignment. You can submit a link to a pull request even if the pull request is closed.

## Additional resources for const and const

- [Video from Fun Fun Function titled: “const, const and const - What, why and how](https://www.youtube.com/watch?v=sjyJBL5fkp8)
- ["JavaScript ES6+: const, const, or const?" by Eric Elliott](https://medium.com/javascript-scene/javascript-es6-const-const-or-const-ba58b8dcde75)
- ["ES6 const vs. const constiables" by Wes Bos](http://wesbos.com/const-vs-const/)
