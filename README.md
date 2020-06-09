# What do you call this in JavaScript?

This is a list of ambiguous symbols used in JavaScript that may be confusing to search for on the web.

## The list

| Symbol | Description    | Colloquial verbiage |
| ------ | -------------- | ------------------- |
| `=>`   | Arrow function | _"Hash rocket", "fat arrow"_ |
| `===`   | [Strict equality comparison](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness) | _"Threequal", "identity"_ |
| `==`   | [Abstract equality comparison](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness) | _"Loose equality"_ |
| `{ ...object }` | [Object spread operator](https://redux.js.org/recipes/using-object-spread-operator) | _"Splat"_ |
| `function fn(...args)` | [Rest parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters) | _"Stargs"_ |
| `const { a, b } = ...` | [Destructuring assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) | |
| `{ [name]: "..." }` | [Computed property names](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#Computed_property_names) | |

## Proposals

Some features that may not be available in mainstream JavaScript yet.

| Symbol | Description    | Colloquial verbiage |
| ------ | -------------- | ------------------- |
| `??` | [Nullish coalescing](https://github.com/tc39/proposal-nullish-coalescing) | |
| `?.` | [Optional chaining](https://github.com/tc39/proposal-optional-chaining) | _"Safe navigation operator"_ (Groovy), _"Elvis operator"_, _"Lonely operator"_ (Ruby) |
| `@foo()` | [Class decorators](https://github.com/tc39/proposal-decorators) | | 
| `#{...}` | [Record](https://github.com/tc39/proposal-record-tuple) (immutable) | |
| `#[...]` | [Tuple](https://github.com/tc39/proposal-record-tuple) (immutable) ||

## Thanks

Inspired by [JuanitoFatas/what-do-you-call-this-in-ruby](https://github.com/JuanitoFatas/what-do-you-call-this-in-ruby).
