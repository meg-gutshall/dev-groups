# Classes and Prototypes

> **Dave on 10/14/20**

## Notes

In this session we'll be building a quiz game. To do this, we need to be able to store our data and functionality together...

**Objects!** Objects store functions with their associated data. This is the principle of encapsulation.

Three ways to create objects:

### Object Literal



```javascript
const user1 = {
  name: "Will";
  score: 3;
  increment: function() {
    user1.score++;
  };
}
```

### Dot Notation

* Declare an empty object
* Add properties with dot notation

```javascript
const user2 = {}; // create an empty object

// assign properties to that object
user2.name = "Tim";
user2.score = 6;
user2.increment = function() {
  user2.score++;
};
```

### `Object.create()`

* `Object.create()` is going to give us fine-grained control over our object later on.
* `Object.create()` always returns an empty object.

```javascript
const user3 = Object.create(null);

user3.name = "Eva";
user3.score = 9;
user3.increment = function() {
  user3.score++;
};
```

## Solutions for Our Problem

### Solution \#1: Generate objects using a function

Problem: Each user has a copy of `.increment` stored in its memory.

### Solution \#2: Using the prototype chain

Store `.increment` in just one object and have the interpreter, if it doesn't find the function in `user1`, look up that object to check if it's in there.

Link `user1` and `functionStore` so the interpreter, on not finding `.increment`, makes sure to check in `functionStore` where it would be found.

Create the link with the `Object.create()` technique.

Every single time you invoke a function, you have an implicit parameter: `this`.

No problems. It's super sophisticated but not standard.

### Solution \#3: 



### Solution \#4: 



