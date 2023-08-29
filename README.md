I used object-oriented programming to create a Rectangle class and a Square class. The Square class is a subclass of Rectangle and inherits methods and attributes from the Rectangle class.

The Rectangle class has the following methods:

* `set_width()`
* `set_height()`
* `get_area()`
* `get_perimeter()`
* `get_diagonal()`
* `get_picture()`
* `get_amount_inside()`

The Square class has the following methods:

* `set_side()`

When an instance of a Rectangle is represented as a string, it should look like: `Rectangle(width=5, height=10)`

When an instance of a Square is represented as a string, it should look like: `Square(side=9)`

I created a usage example that shows how to use the Rectangle and Square classes. The code returns the following:

```
50
26
Rectangle(width=10, height=3)
**********
**********
**********
81
5.656854249492381
Square(side=4)
****
****
****
****
8
```

The unit tests for this project are in `test_module.py`. I wrote my code in `shape_calculator.py`. For development, I used `main.py` to test my `shape_calculator()` function. Click the "run" button and `main.py` will run.

The tests are imported from `test_module.py` to `main.py` for convenience. The tests will run automatically whenever I hit the "run" button.
