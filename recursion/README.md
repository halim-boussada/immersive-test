## basic-recursion

Using **recursion**, write a function called **repeatString** that takes two parameters: a string _str_,
which is the string to be repeated, and _count_, a number
representing how many times the string str should be repeated.

```javascript
repeatString("dog", 0); // => ''
repeatString("dog", 1); // => 'dog'
repeatString("dog", 2); // => 'dog' + 'dog' => 'dogdog'
repeatString("dog", 3); // => 'dog' + 'dog' + 'dog' => 'dogdogdog'
```

## advanced-recursion

- [ ] Complete the function `getNumericValues`.
- [ ] It takes a single argument, an object containing nested objects of any depth.
- [ ] It returns all of the values of the objects that are numeric.
- [ ] Your function will only be tested with objects that have strings, numbers, or other objects as properties.

```javascript
var exampleNestedObject = {
  name: "Tolstoy",
  age: 99,
  home: {
    roommates: 2,
    address: {
      street: "discombobulated",
      number: 13,
      city: "stilton",
      zip: 94618,
    },
  },
};

getNumericValues(exampleNestedObject); // returns [99, 2, 13, 94618]
```

### Available Resources for this Prompt

- MDN
