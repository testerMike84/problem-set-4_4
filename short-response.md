# Problem Set 4-4

## Closures, Prototypes, and Constructors

1. What is a closure?

2. Below are a factory function for making a `Square` object and a constructor function for making a `Rectangle` object. Modify the code below to initialize an instance of each (replace the `REPLACE_ME`).

```js
function makeSquare(sideLength) {
    return {
        sideLength: size,
        getArea() {
            return this.sideLength * this.sideLength;
        }
    }
}

class Rectangle {
    constructor(w, h) {
        this.width = w;
        this.height = h;
    }
    getArea() {
        return this.width * this.height;
    }
}

const mySquare = REPLACE_ME
const myRectangle = REPLACE_ME
```

3. What are the similarities and differences between constructor functions and factory functions?

4. What is a prototype? How does an _instance_ of a constructor access the constructor's prototype?
