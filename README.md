# Shapes and Triple Classes
This repository contains three JavaScript classes: `Shape`, `Square`, and `Triple`, along with their usage examples. Let's explore each part.

## Part One: Shape Class
The `Shape` class represents a geometric shape with properties for its name, the number of sides, and the length of each side. It includes a method to calculate and log the perimeter.

```javascript
const square = new Shape("square", 4, 5);
square.calcPerimeter();

const triangle = new Shape("triangle", 3, 3);
triangle.calcPerimeter();
```

## Part Two: Square Class
The Square class is a subclass of Shape and includes an additional method to calculate and log the area of the square.

```javascript
const square2 = new Square(5);
square2.calcPerimeter();
square2.calcArea();
```

## Part Three: Triple and SquaredTriple Classes
The Triple class introduces a static method to calculate the triple of a given number. The SquaredTriple class is a subclass of Triple and overrides the calculation method to return the square of the triple.

```javascript
console.log(Triple.description);
console.log(Triple.calculate());
console.log(Triple.calculate(6));

console.log(SquaredTriple.calculate(3));
console.log(SquaredTriple.description);
console.log(SquaredTriple.longDescription);
console.log(SquaredTriple.customName);
```


