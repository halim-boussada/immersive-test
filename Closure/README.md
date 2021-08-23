## basic-closure

Using closures create **makeSafe** Function that accepts an _initial integer value_ to specify the _storage size limit_

- _makeSafe_ should contain **addItem** function that accepts two parameters the item and the itemSize as Strings
- _itemSize_ should be either **"big"**, **"medium"** and **"small"**:

      - big sized items will hold 3 slots in the storage
      - medium sized items will hold 2 slots in the storage
      - small sized items will hold 1 slot in the storage

- return "Can't fit" if you try to add an item that exceeds the storage size limit
- when the safe is full return a string representing all the items that are in the safe

Example:

```javascript
  var safe = makeSafe(5)
  safe('watch','small')
  safe('gold-bar','big')
  safe('silver-bar','big') => "Can't fit"
  safe('money','small') => "watch gold-bar money"
```

## closure-with-methods

**makeGetterSetter** should return a function that is a getter setter.

When the getter/setter is invoked with a single argument, it should set
the value.

When the getter/setter is invoked without any arguments,
it should return the previously set value.

```javascript
var getterSetter = makeGetterSetter();
getterSetter(); // returns undefined
getterSetter(5);
getterSetter(); // returns 5
getterSetter("hi");
getterSetter(); // returns 'hi'
```

### Available Resources for this Prompt

- MDN
