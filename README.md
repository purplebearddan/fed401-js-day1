# Variables and Data Types

## Lesson Objectives

To understand...

- Variables
- Primitive Data types
  - Strings
  - Numbers (Integers/Float)
  - Booleans (true/false)
  - Arrays (lists)
  - Generic Objects (labeled lists)
- Dot Notation
  - Built-in Methods and Properties

## Intros

### `JavaScript`

`JavaScript` is a high-level programming language that is widely used to create interactive and dynamic web pages. It is a client-side scripting language, which means that it is executed on the user's browser, rather than on the server. `JavaScript` was originally designed to add interactivity to HTML pages, but it has evolved to become a versatile language that can be used for a wide range of applications, including web and mobile app development, game development, and server-side programming.

```js
const someName = "some value"

// Do something with someValue
someName.toUpperCase() // "SOME VALUE"
```

### Primitive Data Types in `JavaScript`

In `JavaScript`, there are five primitive data types: strings, numbers, booleans, arrays, and generic objects. These data types are used to represent different types of values in a program. Strings are used to represent text, while numbers are used to represent numeric values, which can be either integers or floating-point numbers. Booleans are used to represent true/false values. Arrays are used to store collections of values, while generic objects are used to store key-value pairs.

```js
const myString = "I'm a string"
const myIntegerNumber = 23 // Number
const myFloatNumber = 23.5 // Number
const myBool = true //can be false
const myIntegerArray = [1,2,3,4,5]
const myStringArray = ["doll", "racecar", "ball"] // aka List
const myObject = { key: "value", otherKey: "otherValue"} // aka Dictionary
```

### Strings in `JavaScript`

`Strings` are one of the `primitive data types` in `JavaScript`. They are used to represent `text` and are enclosed in `single` or `double quotes`. Strings can be concatenated using the `+` operator, and individual characters can be accessed using *bracket notation*. `Strings` also have a number of built-in `methods` that can be used to manipulate and transform them.

```js
const myFirstName = "Dan"
const myLastName = "Monaghan"


// need to include the space      \/
const myFullName = myFirstName + " " + myLastName

console.log(myFullName) // "Dan Monaghan"

// Computers running JS start counting at 0
// accessing the first letter in myFullName
console.log(myFullName[0]) // "D"
// accessing the 3rd letter
console.log(myFullName[2]) // "n"
```

### Numbers (Integers/Floats) in `JavaScript`

Numbers are another primitive data type in `JavaScript`. They are used to represent `numeric values` and can be either `integers` or `floating-point numbers`. `Numbers` can be manipulated using `mathematical operators` like `+` (add), `-` (subtract), `*` (multiply), and `/` (divide), and they also have a number of built-in `methods` that can be used to perform `mathematical operations` on them.

```js
3
( 3 + 3 - (2 * 3) ) / 4
```

### Booleans (true/false) in `JavaScript`

`Booleans` are a *primitive data type* in `JavaScript` that are used to represent true/false values. They are often used in *conditional `statements`* and *logical `expressions`* to control the flow of a program.

`Booleans` can be created using the `true` and `false` keywords, and they also have a number of built-in `methods` that can be used to perform *logical operations* on them.

```js
true
// or
false
```

### Arrays (Lists) in `JavaScript`

Arrays are a data structure in `JavaScript` that are used to store collections of values. They can be created using square brackets and can contain any combination of data types, including strings, numbers, and other arrays. Arrays have a number of built-in methods that can be used to manipulate and transform them, including methods for adding and removing elements, sorting, and searching.

```js
// 0   ,   1    ,   2     (index)
['red', 'green', 'blue']
```

### `Generic Objects` in `JavaScript`

Generic `objects` are another *data structure* in `JavaScript` that are used to store key-value pairs. *They are often used to represent complex data structures, such as JSON data.*

`Objects` can be created using *curly braces* `{}` and *can contain any combination of* `data types` *as values, as well as keys to access those values.* `Objects` also have a number of built-in `methods` that can be used to manipulate and transform them.

```js
//
// a simple cafe customer
//
const customer = { name: 'John', order: "Chips", loyaltyPoints: 33};

//
// a more complex example
//
const hero = {
  name: 'Link',
  hearts: 3,
  alive: true
  inventory: [ "Sword", "Shield", "Bow" ],
};

```

### `Dot Notation` in ``JavaScript``

`Dot notation` is a `syntax` used in ``JavaScript`` to access `properties` and `methods` of an object. It involves using a dot `.` followed by the name of the property or method to access it. Dot notation is often used with built-in objects and methods in `JavaScript`, such as

```js
Math.PI
```

or

```js
console.log("Something to say")
```

It can also be used to access properties and methods of custom objects and functions.

### Built-in `Methods` and `Properties` in `JavaScript`

``JavaScript`` provides a number of built-in `methods` and `properties` that can be used to perform common tasks and operations. These include `methods` for working with `strings`, `numbers`, `arrays`, and `objects`, as well as `properties` for accessing information about the `browser` and the `environment` in which the `script` is running. Built-in `methods` and `properties` are often used in conjunction with `dot notation` to access and manipulate data in a program.

## Resources

### W3 Schools

- [`JavaScript`](https://www.w3schools.com/js/DEFAULT.asp)
- [Syntax](https://www.w3schools.com/js/js_syntax.asp)
- [Data Types](https://www.w3schools.com/js/js_datatypes.asp)
- [Strings](https://www.w3schools.com/js/js_strings.asp)
- [Numbers](https://www.w3schools.com/js/js_numbers.asp)
- [Booleans](https://www.w3schools.com/js/js_booleans.asp)
- [Arrays](https://www.w3schools.com/js/js_arrays.asp)
- [Variables](https://www.w3schools.com/js/js_variables.asp)
  - [Let](https://www.w3schools.com/js/js_let.asp)
  - [Const](https://www.w3schools.com/js/js_const.asp)
- [Objects](https://www.w3schools.com/js/js_objects.asp)

### MDN Docs

- [`JavaScript`](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`)
- [Syntax](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Guide/Grammar_and_types)
- [Data Types](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Data_structures)
- [Strings](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Global_Objects/String)
- [Numbers](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Global_Objects/Number)
- [Boolean](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Global_Objects/Boolean)
- [Variables](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Statements/var)
  - [Let](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Statements/let)
  - [Const](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Statements/const)
- [Objects](https://developer.mozilla.org/en-US/docs/Web/`JavaScript`/Reference/Global_Objects/Object)
