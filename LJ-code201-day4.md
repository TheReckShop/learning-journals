# Notes 1/5/17

## HTML Box Model

Almost every element in HTML is represented by a box on the actual screen

For example an < h1> < /h1> tag has a size and shape for its CONTENT, PADDING, BORDER, and MARGIN

## JAVASCRIPT FUNCTIONS

a function must be DECLARED and then called...

#### TO DECLARE A FUNCTION:

    function testFunction() {
        block of code;
      }

This will allow you to declare the function as a function called testFunction that executes the block of code when called...

#### TO CALL A FUNCTION:

    testFunction();
This will then execute the block of code found within the function testFunction...

#### EXAMPLE OF A VARIABLE CONTAINING A FUNCTION

    var subtractTwoValues = function(num1, num2) {
      return num1 - num2;
    };

    subtractTwoValues(5,2);
    3
