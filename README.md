

# Code Challenge - jQuery User Input Calculator

Students will work in groups to create a calculator that accepts user input using jQuery event listeners and JavaScript functions, if/else or switch statements, and jQuery val methods.

## The calculator should do the following:
  
  1. Be object oriented.
  1. the calculator should use jQuery selectors to get the input for 2 separate numbers and 1 operation: '+', '-', '*', '/'.
  2. When the user clicks the equals button, the calculator should update the result `h2` tag with the result. 
    1. If the user leaves a number field blank or inserts some input that is not a number then h2 with id="result" should instead print the error message: "Sorry, one of those is not a valid number!". 
    2. If the operation inserted is not one of the valid accepted operations then the error message should then read "Sorry, not a valid operation!"

See a live working example of the simple calculator [here](http://learn-co-curriculum.github.io/fe-jquery-user-input-calc/)

NOTE: Do not alter any of the code in the "document ready" section of `calc.js`. Once the new instance of your calculator is created, it should automatically fire a function to add an event listener onto the equals button.

##Before You Start
```shell
# Install jasmine:
gem sources -a http://flatiron:33west26@gems.flatironschool.com
gem install learn-co

# Run Jasmine test suite:
learn  # runs only in the terminal
learn -b # runs also in the browser
```

## Resources
US/docs/Web/JavaScript/Reference/Statements/function)
 * [jQuery API - Selectors](http://api.jquery.com/category/selectors/)
 * [jQuery API - Events - Click](http://api.jquery.com/click/)
 * [jQuery API - Text](http://api.jquery.com/text/)
 * [Live Working Example](http://learn-co-curriculum.github.io/fe-jquery-user-input-calc/)
