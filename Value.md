The most fundamental unit of information in a program. In [[Javascript]], it could be **[[Primitive]]** or **[[Object]]**.

Values are applied using **literals**.

In this case `console.log("Activating yeyu mode")` `"Activating yeyu mode"` is a [[Primitive]] [[String]] literal.

Values:
```
typeof 42;                  // "number"
typeof "abc";               // "string"
typeof true;                // "boolean"
typeof undefined;           // "undefined"
typeof null;                // "object" -- oops, bug!
typeof { "a": 1 };          // "object"
typeof [1,2,3];             // "object"
typeof function hello(){};  // "function"
```
