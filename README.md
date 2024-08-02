# VECTOR3

VECTOR3 is an open source library for anyone using 3D design with JavaScript. Even if it is small, it can help your code to use fewer characters to calculate a normalized vector, for example. Go deeper and you will definitely find it interesting (be honest :P).

## ALL functions

    * normalizes vectors
    * calculates the dot product
    * add/subtract (necessary, right?)
    * simplifies in directions (you can doubt as many times as you want :D)

## usage

### creating one vector

You can create a vector simply using vector3(vector):

```JavaScript
const vector = vector3({
    x: 1, // x
    Y: 1, // y
    z: -1, // z
});

vector.vector // return the vector 1, 1, -1
```

### normalize

use vector.normalized:

```JavaScript
vector.normalized;
// Object { x: 0.5773502691896258, y: 0.5773502691896258, z: -0.5773502691896258 }
```

### dot product

use the function vector.dot(v) where v is another vector:

```JavaScript
vector.dot({x: -2, y: -3, z: -5});
// 0 (are perpendicular)
```

### add/subtract

use vector.add or vector.subtract, with one vector in the argument

```JavaScript
vector.subtract({ x: 1, y: 2, z: 3 }); // exit: (0, -1, -4)
vector.add({ x: 1, y: 2, z: 3 }); // exit: (2, 3, 2)
```

## CREDITS

made in brazil
i'm, artur bernardo, beginer in english and JavaScript, I'd rather help everyone than keep to myself, even if they're gangsters
